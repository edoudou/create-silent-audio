# create-silent-audio
Create a silent audio blob to use in a &lt;audio> tag.

Inspired from https://www.russellgood.com/how-to-convert-audiobuffer-to-audio-file/

How to install :
```
npm install create-silent-audio
```

How to use it :

```js
import { createSilentAudio } from 'create-silent-audio';
...
document.getElementById('audioTag').src = createSilentAudio(10,44100);
...
```

Arguments 

| Argument | type      | required | default |
| -------- | --------- | -------- | ------- |
| time     | `Integer` | `true`   | none    |
| frequency| `Integer` | `false`  | 44100   |

