# Program Design
## Structure Chart
![Chart](https://github.com/lukehami55/CSC-250---Programming-Assingment-1/blob/main/Structure%20Chart.png?raw=true)

## Data Storage in Main
``` cpp
char date[11]; //C-STRING stores date variable as a character datatype
string date; //STRING stores date variable as string datatype
```
## Function Design
``` cpp
//START C-STRING PROTOTYPES
// function to convert a two-digit number to its word representation
void convertNumberToWord(char* word, int num);

// function to convert a month number to its word representation
void convertMonthToWord(char* word, int month);

// function to print the date in words
void printDateInWords(const char* date);
//END C-STRING PROTOTYPES


//START STRING PROTOTYPES
// function to convert a two-digit number to its word representation
string convertNumberToWord(int num);

// function to convert a month number to its word representation
string convertMonthToWord(int month);

// function to print the date in words
void printDateInWords(const string& date);
//END STRING PROTOTYPES
```
## Time Estimates
|  | Estimated Time    | Actual Time    |
| :---:   | :---: | :---: |
| c-string convertNumberToWord |  10  |  15  |
| c-string convertMonthToWord |  10  |  10  |
| c-string printDateInWords |  50  |  75  |
| string convertNumberToWord |  10  |  5  |
| string convertMonthToWord |  10  |  5  |
| string printDateInWords |  50  |  60  |
| Total Time | 140   | 170   |
