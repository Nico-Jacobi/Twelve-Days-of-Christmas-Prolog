w(X):-print(X).
a(X):-element(X,[first,second,third,four,fif,six,seven,eigh,nin,ten,eleven,twelf],Y),w('On the '),w(Y),(X>3->w(th);!),w(' day of Christmas'),nl,w('my true love sent to me:'),nl.
b(X):-element(X,['Two Turtle Dove','Three French Hen','Four Calling Bird','Five Golden Ring','Six Geese a-Lay','Seven Swans a-Swimm','Eight Maids a-Milk','Nine Ladies Danc','Ten Lords a-Leap','Eleven Pipers Pip','Twelve Drummers Drumm'],Y),w(Y),(X>4->w('ing,');w('s,')),nl,Z is X-1,b(Z).
p:-w('a Partridge in a Pear Tree.'),nl,nl.
r(X):-Y is X+1,a(Y),(b(X);w('and '),p),r(Y).
run:-a(1),p,r(1);!.