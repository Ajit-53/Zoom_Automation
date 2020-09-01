# Zoom Automation
A python script that automatically joins a zoom meeting based on your timetable.

## What does it do?
It performs the following processes:
1. Checks the "meetingschedule.csv" file to look for meetings that are going to start.
2. As soon as the current time matches any meeting time it opens the Zoom Desktop application.
3. Navigates the cursor automatically to various steps to join the meeting.
4. The meeting ID and passcode are extracted from "meetingschedule.csv" and entered into the Zoom app automatically.

## Prerequisites
1. Zoom app must be installed in your system.
2. You must be logged in to your Zoom account.
3. Meeting time for the day along with Meeting ID and passcode must be entered manually into the "meetingschedule.csv"

## How to use?
1. The best way to use my script is to firstly clone the git repo where you want to.
2. Be sure to add the location where Zoom.exe is installed in your system in the line 20 of the Code file.
2. Open "meetingschedule.csv" and fill in the Meeting Time, Meeting ID and Passcode of each meeting you want to join automatically.
3. Open "Zoom.py".

NOTE: Meeting Time must be in Hours and Minutes format only!

