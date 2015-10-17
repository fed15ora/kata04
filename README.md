Build Engineer Exercise
=======================

1. Create a new project on github.com
2. Connect your Github project to travis-ci.org to run your tests
3. Implement Part One, Two and Three of Kata04: http://codekata.com/kata/kata04-data-munging/

Send your travis-ci build page to it@chemaxon.com .
On the face to face interview we will talk about the Kata Questions.

A Java solution is strongly preferred.
Your mission, should you choose to accept it, is the following:

- Use Gradle wrapper
- Set up a basic project
- Package your project, complete with manifest information
- Have a proper dependency handling to external libraries
- Publish Test Report, also, print test execution outcome to command line so it's visible on the Travis CI console log

Otherwise complete a similar task with your favourite language.

=============================

Here’s an exercise in three parts to do with real world data. Try hard not to read ahead—do each part in turn.

Part One: Weather Data
In weather.dat you’ll find daily weather data for Morristown, NJ for June 2002. Download this text file, then write a program to output the day number (column one) with the smallest temperature spread (the maximum temperature is the second column, the minimum the third column).

Part Two: Soccer League Table
The file football.dat contains the results from the English Premier League for 2001/2. The columns labeled ‘F’ and ‘A’ contain the total number of goals scored for and against each team in that season (so Arsenal scored 79 goals against opponents, and had 36 goals scored against them). Write a program to print the name of the team with the smallest difference in ‘for’ and ‘against’ goals.

Part Three: DRY Fusion
Take the two programs written previously and factor out as much common code as possible, leaving you with two smaller programs and some kind of shared functionality.
