Hey Day Script
=============

The goal of this project is to make a flexible program to allowing users to enter their name and get a response that greets the user, using their name.

## Motivation

The purpose of this project is to create a working script to celebrate the Auburn Univeristy tradition called "Hey Day". The tradition started in 1947, shortly after WWII, as a way to welcome back students that served in the war. Each year on Hey Day, everyone wears a nametag and is encouraged to greet one another to promote a feeling of unity and belonging on campus.

For more information about the Hey Day tradition, click [here.](http://sga.auburn.edu/hey-day/)

## Running the Program

This is a flexible program. Upon running, the program prompts users to enter their name. After entry, the program will send a message that reads, "Hey (entered name)". 

    #!/bin/bash
    echo "Please enter your name"
    read name
    echo "Hey $name"
    
## Example Input and Output

    bash HeyDay.sh
    # Please enter your name
    Josie
    # Hey Josie
