# gpt-podcast
[![Twitter Follow](https://img.shields.io/twitter/follow/mattshumer_?style=social)](https://twitter.com/mattshumer_) [![Open Main Version In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/179mR2aNTIsMSrN57jRAg61C28z6nCASq?usp=sharing)

By Matt Shumer (https://twitter.com/mattshumer_)

Generate a fictional podcast in minutes with AI.

**This is not for commercial use -- purely for research and fun!**

## Features

- **Dynamic Participants**: Define the participants in your podcast. Be creative!

- **Voice Cloning**: The system clones the voices of the participants from provided YouTube clips. This makes your podcast sound like an actual conversation between the participants.

## Setup
1. [Open the notebook in Google Colab](https://colab.research.google.com/drive/179mR2aNTIsMSrN57jRAg61C28z6nCASq?usp=sharing) or in a local Jupyter notebook.

2. Define your podcast participants, topic, and number of turns. For example:

```
speaker_one = "Joe Rogan"
speaker_two = "Rick Sanchez, of Rick and Morty"

topic = "Artificial Intelligence"

number_of_turns = 7
```

3. Provide YouTube clips and voice descriptions for the participants:

```
speaker_one_clip = "https://www.youtube.com/watch?v=CM_LWxh33Z8" # a video of speaker_one speaking
speaker_one_voice_description = "American male, deep voice."

speaker_two_clip = "https://www.youtube.com/watch?v=GKPcHInn14c" # a video of speaker_two speaking
speaker_two_voice_description = "A bit gruff and raspy, often slurred due to his constant state of inebriation. His speech is punctuated with frequent burps and stammers. He speaks with a cynical and sarcastic tone, often sounding dismissive or condescending. His voice also has a certain manic energy to it, reflecting his chaotic personality."
```

4. Run the cells to generate the podcast.

## Contributions are welcome!

## License

This project is [MIT](https://github.com/mshumer/gpt-podcast/blob/master/LICENSE) licensed.

## Contact

Matt Shumer - [@mattshumer_](https://twitter.com/mattshumer_)

Project Link: [https://github.com/mshumer/gpt-podcast](https://github.com/mshumer/gpt-podcast)

Lastly, if you want to try something even cooler than this, sign up for [Personal Assistant](https://www.hyperwriteai.com/personal-assistant) (most of my time is spent on this). It's basically an AI that can operate your web browser to complete tasks for you.
