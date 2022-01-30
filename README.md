<div align="center">
<img src="https://avatars.githubusercontent.com/u/85196372?v=4.jpg" alt="SEKHA" width="170" />

</div>

<p align="center">
<a href="##"><img title="sekha-api" src="https://img.shields.io/static/v1?label=package&message=sekha-api&color=green"></a>
</p>
<p align="center">
  <a href="https://github.com/inirey"><img title="Author" src="https://img.shields.io/badge/Author-SEKHA-red.svg?style=for-the-badge&logo=github" /></a>
</p>
<p align="center">
<a href="#"><img title="sekha api modules" src="https://img.shields.io/static/v1?label=FREE&message=sekha-api&color=green"></a>
</p>

## INSTALL Dependents
> npm install sekha-api

## ```EXAMPLE```
``` 
const skh = require('sekha-api');
const title = 'surender'

skh.lyric(title)
    .then(result => {
     console.log(result)
});

// Pinterest Search
const skh = require('sekha-api');
const q = 'loli'

skh.pinterest(q)
    .then(result => {
     console.log(result)
});
```
