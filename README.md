# Gigatron
A collection of software and tools I developed for the [Gigatron TTL microcomputer](https://gigatron.io).

## Software
### Video Poker
**WORK IN PROGRESS**

A 5-card poker game for Gigatron developed in [at67's gtBASIC](https://forum.gigatron.io/viewtopic.php?f=4&t=232).

![Screenshot](screenshots/videopoker-alpha-01.png?raw=true)

**What Works:**
- Deal cards
- Draw cards
- Select card
- Hold card

**In Progress:**

- Win conditions
  - [X] Jacks or Better
  - [X] Two Pair
  - [X] Three of a Kind
  - [X] Straight
  - [X] Flush
  - [ ] Full House
  - [ ] Four of a Kind
  - [ ] Straight Flush
  - [ ] Royal Flush

**To-Do:**
- Bank (credits)
- Display winning hands and payouts
- Better looking design on back of cards
- Sounds

## Tools
### CustomFish
A personalized version of the BabelFish firmware which supports Arduino Mega as well as breadboard buttons to load software.

### sendFile.py
Modification of the original which adds support for the Arduino Mega. Sends GT1 or BASIC files to the Gigatron from a computer.
