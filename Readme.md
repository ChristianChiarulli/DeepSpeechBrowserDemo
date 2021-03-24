# Web Microphone Websocket

This example is taken from here: [link](https://github.com/mozilla/DeepSpeech-examples)

This is an example of a ReactJS web application streaming microphone audio from the browser
to a NodeJS server and transmitting the DeepSpeech results back to the browser.

#### Download the pre-trained model (1.8GB):

```
wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm
wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.scorer
```

#### Install:

```
npm install
```

#### Run ReactJS Client:

```
npm start
```

#### Run NodeJS Server (in a separate terminal window):

```
npm server.js
```
