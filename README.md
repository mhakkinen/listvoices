# Listing TTS Voices available within the Browser

The [W3C WebSpeech API](https://wicg.github.io/speech-api/) for [Speech Synthesis](https://wicg.github.io/speech-api/#tts-section) makes it possible to send textual content from a web page to be spoken by a speech synthesizer, also known as a Text To Speech (TTS) engine or service. Today's platforms come with a variety of pre-installed TTS voices. The web page implemented here will retrieve a list of the available TTS engines using the Web Speech API. You can view a [live page](https://talkinginterfaces.org/webtts/listvoices.html) to see what TTS voices are available with your browser.

In retrieving TTS voices across browsers and platforms,I have noted some inconsistencies in the data returned via two of the atributes of the [SpeechSynthesisVoice attributes](https://wicg.github.io/speech-api/#speechsynthesisvoice-attributes): `default` and `voiceURI`.  This is something to investigate further.  

If you have questions, feel free to reach out to me at mhakkinen at acm.org or file an issue on github. Also, if you are interested in allowing authors to improve the quality of spoken presentaton using TTS on the web, check out the [W3C Pronunciation Task Force](https://www.w3.org/WAI/APA/task-forces/pronunciation/).
