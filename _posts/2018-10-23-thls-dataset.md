---
layout: post
title: THLS - An open source dataset for Brazilian Portuguese speech processing
---

In 2016, during my Master’s program, I was researching about Speech Synthesis and Natural Language Processing. To the development of Speech Synthesis systems, I was spending a lot of time editing Speech databases for Brazilian Portuguese. The work included endless hours at the studio listening, trimming audio and checking if the correspondent translation was correct. That work was importing to the final goal of developing Brazilian Portuguese Text-To-Speech and Speech-To-Text systems. However, that dataset I edited was not open source and the options for open source datasets to Brazilian Portuguese was rather scarce. These days, we have more open source options, and I recommend the really nice works by Igor for Speech-To-Text [Igor's github](https://igormq.github.io/datasets/) and by Edresson for Text-To-Speech [Edresson's github](https://github.com/Edresson/TTS-Portuguese-Corpus).

At that time, my best friend Thalles went to spend some time at my home, when we would also try to practice some of his new compositions in a music studio. Then I tought why not to use that time and also record a small dataset to test statistical parametric Speech Synthesis algorithms or Speech Adaptation. So, we spent one whole morning at the studio recording the 1000 phonetically balanced Brazilian Portuguese sentences proposed in [1]. My friend Thalles was not a professional speaker, so I could see how tiring it was to record the 1000 sentences in that morning. The people in the studio were super nice and we completed successfully the recording.

The dataset recorded in that day at the studio, after edited by me, is named as the THLS open source dataset that can be downloaded in this [gitlablink](https://gitlab.com/lfelipesv/1000-sentences-thls-dataset). The repository contains the audio files recorded in ‘wav’ format, the associated sentence translations and the reference paper that proposed the phonetically balanced sentences.

One sample sentence is presented next.

<audio controls>
  <source src="/img/thls-sounds/THLS_PTBR_1000_FRA_0010.wav" type="audio/wav">
</audio></html>

The associated waveform correspondent to the sample sentence is shown in the next figure.

![Waveform](/img/thls-post/waveform.png)

The associated spectogram correspondent to the sample sentence is shown in the next figure.

![Spectogram](/img/thls-post/spectogram.png)

I hope the dataset is useful for your application. Please cite the Gitlab link if you use it for your research. 

Don’t forget to follow the good research in Speech Recognition and Speech Synthesis using Deep Learning being performed by Igor Quintanilha and Edresson Casanova respectively on Github.

**REFERENCES**

[1] Cirigliano, R. J. R., et al. "Um conjunto de 1000 frases foneticamente balanceadas para o Português Brasileiro obtido utilizando a abordagem de algoritmos genéticos." XXII simpósio Brasileiro de telecomuniçacões (2005).