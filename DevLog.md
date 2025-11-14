## DevLog 01 — 2025-11-02

### Initial Idea

- Player sits in front of radio terminal
- Tune frequencies to catch signals
- Decode bips/messages
- Decoded messages can be listened in a seperate menu
- Time-limited gameplay

### TODO LIST (WEEK-1):

- [x] Setup main level (Player Transmission Room)
- [x] Setup Game Mode and Post Processing Effects.
- [ ] Create radio interface UI
- [ ] Create logic and interface UI for listening decoded messages.
- [ ] Implement frequency switching blueprint
- [ ] Add first sound signals

### Reflection

I'm excited to start working on the **Signal Lost** project for the Game Off 2025 Game Jam. 

This is my first *game jam* ever, which makes it even more special. I see this project as a combination of **atmosphere, sound, and puzzle-solving**, where the gameplay revolves around tuning frequencies and decoding hidden messages.

I'll mainly focus on **UI/UX**, making the terminal and radio interface intuitive and immersive, rather than overcomplicating mechanics.  

My approach will be step by step:  
1. First, create a small room where the player sits and interacts with the terminal.  
2. Then, implement the radio logic and basic mechanics for frequency tuning and sound playback.  
3. Gradually add decoded messages and the puzzle-solving layer.

I feel motivated and confident that, within the one-month timeframe, I can create a **complete, playable experience**.  
This jam is a great opportunity to practice and **experiment with sound-driven gameplay** while refining my design workflow.

## DevLog 02 - 2025-11-14
### Progress Summary

This week ended up much slower than I expected — mostly due to university workload, additional academic writing, job hunting, and several side projects I’m working on simultaneously.

It’s been difficult to keep this project consistently up to date and implement every feature I originally planned, but the foundation is slowly coming together. To keep things realistic, I’ll reduce the Week 3 scope and focus only on the essential features needed for the first working gameplay loop.

### Why It Didn’t Go So Well?

Honestly, I simply overloaded myself.
There’s a reason most developers prefer working in teams during game jams — tasks pile up extremely fast. Since this is my first jam, I wanted to challenge myself and do everything solo, but the timing turned out to be far from ideal.

Despite that, I still believe I can finish this project on time.
The remaining core tasks mostly involve audio logic and UI, which are manageable.

### TODO LIST (WEEK-3)

- [ ] Implement first version of the radio terminal screen

- [ ] Finalize camera-to-screen transition (timeline + interaction state)

- [ ] Create a simple mockup widget with placeholder dial/slider for frequency and zone that shows “Signal found” or stays blank

- [ ] Define 2–3 fixed frequency points where signals exist

- [ ] Based on the beep count, generate a letter (e.g., 1 beep = A, 2 = B)

- [ ] Show decoded letter in a small UI field

- [ ] Build the decoding UI prototype

### END OF THE WEEK-3 DELIVERABLES

- [ ] Player can tune 2-3 signals
- [ ] Each signal has its own beep pattern that can be decrypted
- [ ] Player can input the letters (code) into a simple code panel