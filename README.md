# Play "Pirates of the Caribbean" Theme Song on Arduino and Buzzer 🎵

This file contains the code to play the "Pirates of the Caribbean" Theme Song on a Arduino via a Buzzer

Youtube in action: https://www.youtube.com/watch?v=sjPAj1lXgtk

## 💻 Local testing

1. Download `Pirates_of_the_Caribbean_-_Theme_Song.ino`

2. Connect `Pin 10` of the Arduino to the `positive side` of a buzzer or a microphone

3. Connect any `resistor` (220 ohms for example) to the `negative side` of a buzzer and to the `ground pin` of the Arduino

4. Upload the sketch and enjoy!

## 😎 Vitual testing

Don't have an Arduino with you right now? No worry. You can test it vitually on my [simulated TinkerCAD circuit](https://www.tinkercad.com/things/f9QN4skaguI-play-pirates-of-the-caribbean-theme-song-on-buzzer).

1. Click `Simulate`

2. Click `Start Simulation` and enjoy!

## 📖 Learn more

Want to learn more about the science behind `sound`, `buzzer`, `Arduino tone library`? Check out [my learning note on TipStory](https://www.tipstory.org/learning/h2lUMccm5MeuSds) where I share a step by step walkthrough of the science and how I made this. I would appreciate a helpful vote and an interesting upvote from you on TipStory.

🚀Happy engineering and designing!

---

This project was first created in 2016. It is recently updated on `2021.03.25`, 5 years later. I know, sorry, I lost track of it, lol. There are a couple of improvements that can be made and have been made with this update:

1. You can remove the paper seal on the buzzer to make it sound better (Thanks [Ricardo Moreno](https://www.youtube.com/channel/UCbDCjdszaIdDOyXNRgMlgIg) for the suggestion)

2. `songSpeed` and `wait` are converted to `float` type (Thanks [Andrew Lalis](https://www.youtube.com/channel/UC9X4mx6-ObPUB6-ud2IGAFQ) for catching the bug)

3. `noTone` is used to handle malperformacnce of some Arduinos (Thanks [Anthony Pelletier](https://www.youtube.com/channel/UCezmpHibpkbXa_3wSeJNLAQ) for bringing up this issue)

4. Better coding style, format, variable names... (I have learned a lot more about coding since I first exposed to C++ 5 years ago)
