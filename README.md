# Software-Engineering-Project-
Cricket Score Management System
This program is a basic Cricket Score Management System implemented in C. It allows you to input and display details of batsmen and bowlers in a cricket match, calculate individual and team statistics, and retrieve match summaries and records.

Features
Add Batsman and Bowler Details:
For batsmen: name, runs scored in terms of ones, twos, threes, fours, sixes, and balls faced.
For bowlers: name, runs given, overs bowled, and wickets taken.
Display Individual Batsman and Bowler Details:
For batsmen: total runs scored, balls faced, number of fours, sixes, and strike rate.
For bowlers: overs bowled, runs conceded, wickets taken, and economy rate.
Display Match Summary:
Lists all batsmen and their runs, balls, fours, sixes, and strike rates.
Lists all bowlers and their overs, runs conceded, wickets taken, and economy rates.
Record Tracking:
Shows the highest runs scored, maximum fours and sixes hit by a batsman, and maximum wickets taken by a bowler.
Program Structure
The program is divided into two primary structures:

struct batsman: Represents a batsman with attributes like name, runs, balls faced, and the count of different types of runs (ones, twos, threes, fours, sixes). It also stores calculated stats like strike rate.
struct bowler: Represents a bowler with attributes like name, runs conceded, overs bowled, wickets taken, and economy rate.
Menu Options
After entering details for batsmen and bowlers, the program presents a menu with the following options:

Batsman Detail:
Displays details for a specific batsman, including runs scored, balls faced, fours, sixes, and strike rate.

Bowler Detail:

Displays details for a specific bowler, including overs bowled, runs given, wickets taken, and economy rate.
Match Summary

Shows a summary of all batsmen and bowlers, including total runs, fours, sixes, and strike rates for batsmen and overs, runs given, wickets taken, and economy rates for bowlers.
Record Summary

Shows highest runs scored by any batsman, maximum fours and sixes hit, and maximum wickets taken by any bowler.
Exit

Exits the program.
