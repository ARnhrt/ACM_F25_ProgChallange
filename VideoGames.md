# Video Games (Medium)
David, Sarah, and Mike are all friends that share their video game collections. They all share different video games so that only one of them needs to own it for them all to play it. Their favorite games right now are <b>NBA2K26</b>, <b>Wii Sports</b>, and <b>HALO Reach</b>. 
<br></br>
Initially, David has NBA2K26, Sarah has Wii Sports, and Mike has HALO Reach. Over time, the games are passed around between the friends and it can be hard to keep track of who has each game.
<br></br>
Given a sequence of requests indicating that a particular friend wants to play a particular game, determine who they have to borrow the game from.
<br></br>
The first line of input should contain a single integer which indicates the number of requests (R). Then R lines follow describing the requests. The lines will always be in the same format (<name> wants to play <game>).

### Input
```
4
david wants to play wii sports  
sarah wants to play wii sports
mike wants to play halo reach
mike wants to play nba2k26
```
### Output
```
david borrows wii sports from sarah
sarah borrows wii sports from david
mike already has halo reach
mike borrows nba2k26 from david
```
