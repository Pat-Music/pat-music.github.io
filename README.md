# PatMu

## Inspiration
Every person could be a music creator, and music creation should be accessible and fun. However, all current professional digital audio workstations in today's market share a common user frustration: their control panels are complicated and hard to navigate. Inspired by rhythm games, AR technology, and interactive digital music tools, we wanted to create an intuitive way for users to make music using only their hands.

## What it does
Patmu is an AR-powered web game in which users create music using hand gestures. The game utilizes computer vision to detect movements, allowing users to "pat" virtual instruments like drums, piano chords, and melodic sequences. Users' gestures trigger corresponding musical sounds as they interact with the game, creating a dynamic and engaging music-making experience.

## How we built it
We split the team into 1) web page design and 2) AR game design and connected the two sides together. The arcade panel inspired us a lot. We developed the whole program using HTML and Javascript. In the process, we set up the gesture recognition using TensorFlow.js and MediaPipe, built the sounds using Tone.js, and created a feature to record and save the user’s music performance.

## Challenges we ran into
1. Gesture Recognition Precision: there's always a minor delay between input gesture and output sound.
2. Web Integration: we tried a lot of times embedding a real-time AR game into a web page.
3. UIUX Optimization: we tried a retro aesthetic with smooth, intuitive controls.

## Accomplishments that we're proud of
1. Successfully implemented real-time gesture-to-sound mapping. (MVP)
2. Created an engaging, user-friendly, retro-styled interface.
3. Developed a seamless record-and-save functionality.

## What we learned
1. First-time hacking isn't scary, it's fun!
2. We've been more proficient with skills like HTML, Unity, and Javascript.
3. A good team should work in an eatery!

## What's next for Patmu
1. Launch more functions, such as adding more instruments, music challenge tracks, and bassline beats.
2. Fine-tune recognition algorithms for smoother interaction.
3. AR Enhancement: add interactive animations for a more immersive experience.

[Try it out!](pub-music.github.io)
