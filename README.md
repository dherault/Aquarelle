# Aquarelle

Aquarelle is a random profile picture generator, based on famous paintings.

## Example thumbnails

![](https://i.imgur.com/29wqN0T.png) .
![](https://i.imgur.com/lSpkUWJ.png) .
![](https://i.imgur.com/XNk6VR8.png) .
![](https://i.imgur.com/Z0K32ZG.png) .
![](https://i.imgur.com/NrVkJgd.png) .
![](https://i.imgur.com/a8pCTGT.png)

## Installation

`npm i aquarelle --save`

## Usage

```js
const aquarelle = require('aquarelle');

const {
  width,
  height,
  title,
  year,
  author,
  fileName,
  filePath,
  originalFileName,
  originalFilePath,
} = aquarelle(128, 128, 'path/to/output/dir');
```

## License

MIT
