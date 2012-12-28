Code Details
==========

FizzBuzzBash is a simple test script designed to print a list of numbers or the text "Fizz", "Buzz", and/or "Bash" if the number is divisible by 3, 5, and/or 7 respectively.

The LogReader program is designed to read through a list of log files and search for order or task numbers. It is designed to dynamically call servers and analyze a number of log files based on user input. It then makes DB calls for more information and stores all relevant data to a .csv file. The LogReaderMain class orchestrates the program's overall action. The Dao class controls most of the processing and all of the DB calls. The RunningObject class deals with processing/validating all user inputs.

ProvPlanAnalyzer is a program designed to look through a large number of workflows and determine if there are any identical matches. Workflows are considered identical if they have the same number of tasks and all tasks contained in the first flow are also contained in the second. The ProvPlanAnalyzerMain class orchestrates the program's overall action, while the ProvPlanAnalyzerDao class controls most of the processing and all of the the DB calls.

RecycledNumbers and SpeakingInTongues are both small programs created for the Google Code Jam as a coding exercise.
