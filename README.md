# Python_alarm_clock
The objective of this project is to implement an alarm clock using Python.

Python consists of very useful libraries such as datetime and tkinter which help us to build this project using the current date and time.

Apart from this, they provide a user interface to set the alarm according to the requirement in 24-hour format.

EXPLANATION:

Define a function named as alarm() which takes the argument of (set_alarm_timer).It contains a while loop with a Boolean function True which makes the program automatic to work.
time.sleep(1) halts the execution of the further commands given until we get the time value from the user later in the code and returns the background thread of the clock time going on at a regular interval.
Get the current time using current_time which takes the argument of datetime.datetime.now().
now is used to print the time and date is used to print the current date by string conversion using strftime().
Define another function here named actual_time() which takes in the user value for setting the alarm in the string format. The same argument of (set_alarm_timer) as alarm before to execute the while loop which we further use while making GUI.
If loop suggests that if the user input time set_alarm_timer matches with the while loop ongoing time now, the message is printed as” Time to Wake up”.
winsound.SND_ASYNC plays the system generated sound as soon the condition satisfies, acting as a reminder for the alarm clock.

