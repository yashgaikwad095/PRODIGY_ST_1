 Test Cases for Simple Calculator

 Positive Test Cases

| Test cases   | Description                      | Steps to Execute                   | Expected Result  |
|--------------|----------------------------------|------------------------------------|------------------|
| TC_01        | Add two numbers                  | Enter 5 + 3 and press =            | 8                |
| TC_02        | Subtract two numbers             | Enter 9 - 4 and press =            | 5                |
| TC_03        | Multiply two numbers             | Enter 6 * 4 and press =            | 24               |
| TC_04        | Divide two numbers               | Enter 20 ÷ 5 and press =           | 4                |
| TC_05        | Add negative and positive number | Enter -3 + 6 and press =           | 3                |
| TC_06        | Multiply with decimal            | Enter 2.5 * 4 and press =          | 10               |
| TC_07        | Add multiple numbers             | Enter 2 + 4 + 6 and press =        | 12               |
| TC_08        | Follow BODMAS rule               | Enter 2 + 3 * 4 and press =        | 14               |
| TC_09        | Subtract from 0                  | Enter 0 - 5 and press =            | -5               |
| TC_10        | Add zero                         | Enter 7 + 0 and press =            | 7                |

 Negative Test Cases

| Test Case ID | Description                     | Steps to Execute                   | Expected Result             |
|--------------|---------------------------------|------------------------------------|------------------------------|
| TC_11        | Divide by zero                  | Enter 9 ÷ 0 and press =            | Error / Cannot divide by 0  |
| TC_12        | Input letters instead of numbers| Enter A + 5 and press =            | Error / Invalid input       |
| TC_13        | Use special characters          | Enter # + % and press =            | Error / Invalid characters  |
| TC_14        | Press = without input           | Open calculator and press = only   | Error / No input provided   |
| TC_15        | Multiple operators without number| Enter + * - and press =           | Error / Invalid operation   |
