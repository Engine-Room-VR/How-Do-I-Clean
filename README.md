# How-Do-I-Clean
APK submission for the Meta Presence Platform Hackathon

## Inspiration
We wanted to create a game that has a similar kind of catharsis found in games like Powerwash Simulator and House Flipper. Something we found interesting about these games is that the activities done in these games (e.g. powerwashing and painting) would not be exciting to most people in real life- yet, in a virtual environment, those same chore-like activities can be fun, almost satisfying.

## What it does
'How Do I Clean?' takes the scene model of the room you are currently in and places trash around it in a strategic manner. You are also given tools to deal with different kinds of trash and messes. In singleplayer, there are 2 modes: zen and timed. In zen mode, the goal is simply to clean up your room- nothing else. In timed mode, your goal is to clean up your room in a fixed amount of time.

## How we built it
We used the Unity game engine and incorporated the Interaction, Scene, and Passthrough SDK/APIs.

## Challenges we ran into
One of the key features of the game was meant to be a multiplayer feature wherein you could compete with another player to have the cleaner room (with PvP-like gameplay, where you could throw trash into the other player's room to dirty it). However, the room orientation code (mentioned in more detail in the following section) and networking the tools/trash correctly took longer than we expected to fully complete, so regrettably, multiplayer was not able to be fully realized by the deadline.

## Accomplishments that we're proud of
One of the problems the multiplayer mode presented was being able to align your room with someone else's to be able to see in and throw trash into it, and our multiplayer programmer (Jakob) was able to write an algorithm that did just that based on a wall the users selected to be their 'forward.'

## What we learned
We definitely learned to come to hackathons/game jams with more practice coding multiplayer! It's a difficult task even in the best of times.

## What's next for How Do I Clean?
First and foremost, we would love to get the multiplayer fully functional. After that, we would like to add more messes with more specific cleaning tools to combat them. Another thing we want to improve is the visual effects and the graphics.
