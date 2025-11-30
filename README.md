## 🎄 The Twelve Days of Christmas: A Prolog Code Golf Challenge

This project is a highly optimized **Prolog** implementation of the song *The Twelve Days of Christmas*. Developed for a university Code Golf competition where it secured **1st Place**, this solution prioritizes **extreme byte-efficiency** while maintaining complete and correctly formatted output.

### 🧠 Technical Achievement

This solution demonstrates the creative application of logic programming principles to solve a complex output formatting challenge under strict size requirements. It required innovative use of **recursion** and **unification** to generate all 12 unique, cumulative verses with minimal code duplication.

The core challenge was to generate the entire song, ensuring every verse was correctly formatted (including line breaks, but no extra spaces or newlines), all while operating under a severe size constraint. The entire solution is executed fully via the required entry point: `run/0`.

The result is a clean, byte-efficient solution that successfully won the competition.

### 🚀 Usage

To load and execute the song generation in SWI-Prolog:

```prolog
?- [12DaysOfChristmas].   % Load the program
?- run.                   % Execute the song generation
```

### 💡 Further Optimization

I welcome any suggestions for further byte reduction while strictly adhering to the `run/0` rule and maintaining the complete, correct song output\!

