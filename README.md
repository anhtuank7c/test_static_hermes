## Test Static Hermes

Written Javascript code but got C performance???
Let try.

## Required tools

* `cmake`
* `ninja`
* `git`

## Installation

* `brew install cmake git ninja`
* `mkdir test && cd test`
* `git clone -b static_h git@github.com:facebook/hermes.git`

## Build & run

* `npm run build-hermes`
* `npm run build-ts`: You will got a compiled file in the output directory `output/helloTypeScript`
* `npm run build-js`: You will got a compiled file in the output directory `output/helloJavascript`

Run compiled files
```
  ./output/helloTypeScript
  ./output/helloJavascript
```

## References

[Static Hermes: the Next Generation of Hermes](https://youtu.be/q-xKYA0EO-c?si=PzLD8iafX29bWG9u)
[Slide](https://speakerdeck.com/tmikov2023/static-hermes-react-native-eu-2023-announcement?slide=16)
[Static Hermes First look](https://youtu.be/jomW9fWmNJ4?si=n6XvkP-KznnSt3Oe)
