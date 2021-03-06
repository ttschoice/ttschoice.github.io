We’ve created this page as a living resource to supplement our research paper on TTS voice evaluation, published at the ACM Conference on Human Factors in Computing Systems (CHI) 2020.

Listening to long-form content is increasingly common, and the voice reading that content plays a significant role in shaping the user experience. In our work, we developed a method for evaluating the quality of voices for listening to long-form content. The analysis presented in the paper reports on a large-scale evaluation of 21 voices (18 TTS, 3 human). Below, you’ll find examples of those voice clips and additional information beyond what appeared in the paper. We may also expand our original analysis by including additional voices in the future, and will welcome community contributions using our method to evaluate voices as well.


## Listen to the TTS voices
In our research study, participants listened to one of 21 voices reading an article [Reduce Your Stress in Two Minutes a Day](https://getpocket.com/explore/item/reduce-your-stress-in-two-minutes-a-day).

Here are brief clips of each of those voices reading the first two sentences of the article:

_"Bill Rielly had it all: a degree from West Point, an executive position at Microsoft, strong faith, a great family life, and plenty of money.  He even got along well with his in-laws!"_

|Voice Name|Clip|
|:---------|:--------------|
|Android UK Male|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/UK%20Male.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Google A|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Google%20A.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Google C|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Google%20C.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Human 1|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Human1.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Human 2|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Human2.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Human 3|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Human3.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|iOS |<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/iOS.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Judy GL1|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/JudyGL1.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Judy GL2|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/JudyGL2.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Judy W1|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/JudyW1.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Judy W2|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/JudyW2.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|LJ Speech|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/LJSpeech.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Mac Default|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/mac_default.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Nancy 1|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Nancy1.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Nancy 2|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Nancy2.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Polly Joanna|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/PollyJoana.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Polly Matthew|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/PollyMatthew.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Polly Sally|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/PollySally.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Voicery Nichole|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/VoiceryNichole.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Windows Zira|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Windows_Zira.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|
|Windows David|<audio controls src="https://github.com/ttschoice/ttschoice.github.io/blob/master/voice_clips/Windows_David.wav?raw=true">Your browser does not support the <code>audio</code> element.</audio>|

## Technical features
What&mdash;more "objectively"&mdash;may have contributed to the observed differences in listeners’ preferences? While our focus is primarily on informing end users of TTS voices rather than speech synthesis engineers, we present this information as another feature that may help select synthesized voices, particularly for voices where the model details are known, but no listening test has been conducted.

One important word of caution: our TTS recordings were generated through end-user APIs and, without direct contact with the developers, it is difficult to identify the synthesis models or technical features of the voices with absolute certainty. Please note that (except where indicated), the synthesis approach listed is based on the best guess of experts in the speech synthesis field.

The F0 and Intensity values below were determined using Praat from the clips above in which each voice reads the first two sentences of the article (~10 second clips each).

|Voice Name|Average F0 (Hz)|Average Intensity (dB)|Synthesis model|Source|
|:---------|:--------------|:---------------------|:-------------|:------|
|UK Male|116.8|67.1|_TBD_||
|Google A|133.2|74.7|WaveNet|https://cloud.google.com/text-to-speech/docs/wavenet|
|Google C|160.7|75.1|WaveNet|https://cloud.google.com/text-to-speech/docs/wavenet|
|Human 1|126.9|68.1|_N/A_|_N/A_|
|Human 2|186.7|71.9|_N/A_|_N/A_|
|Human 3|119.6|67.4|_N/A_|_N/A_|
|iOS|166.3|77.5|_TBD_||
|Judy GL1|188.7|76.5|Tacotron + Griffin Lim|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|Judy GL2|197.3|72.7|Tacotron2 + Griffin Lim|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|Judy W1|187.3|76.9|Tacotron + WaveRNN|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|Judy W2|195.5|78.0|Tacotron2 + WaveRNN|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|LJ Speech|215.4|73.4|Tacotron + GriffinLim|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|Mac Default|113.6|65.6|_TBD_||
|Nancy 1|197.7|75.2|Tacotron + Griffin Lim|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|Nancy 2|189.0|75.9|Tacotron2 + WaveRNN|https://github.com/mozilla/TTS/wiki/Mean-Opinion-Score-Results|
|Polly Joanna|155.3|72.6|_TBD_||
|Polly Matthew|99.6|72.8|_TBD_||
|Polly Sally|192.2|73.1|_TBD_||
|Voicery Nichole|194.0|68.2|_TBD_||
|Windows Zira|176.9|66.1|_TBD_||
|Windows David|91.9|66.7|_TBD_||

_Did we get something wrong?_ If you were involved in the development of any of these voices or notice an error, please let us know so we can correct it by [filing an issue](https://github.com/ttschoice/ttschoice.github.io/issues) or [submitting a pull request](https://github.com/ttschoice/ttschoice.github.io/pulls). We’d appreciate it!


## Cite our work

```
BibTeX coming soon!
```
