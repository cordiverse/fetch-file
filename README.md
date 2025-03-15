# @cordisjs/fetch-file

Fetch for `file:` URLs.

## Usage

```ts
import fetchFile from '@cordisjs/fetch-file';

const response = await fetchFile('file:///path/to/file.txt');
```

`fetchFile` has the same API as [`fetch`](https://developer.mozilla.org/zh-CN/docs/Web/API/Fetch_API).
