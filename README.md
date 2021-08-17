# PARCEL REACT SAMPLE


## Dependencies

```
 npm i react react-dom parcel-bundler
 ```

## Script

```js
"start": "parcel public/index.html -p 3000"
```


## public/index.html

```xml
<body>
    <div id="root"></div>
    <script src="../src/index.js"></script>
</body>
```

## index.js

```js
import React from "react"; // required ?
import ReactDOM from "react-dom";

import "./index.css";

import App from "./App";

ReactDOM.render(<App />, document.getElementById("root"));
```

## Build

Script

```js
"build": "parcel build public/index.html"
```

Files are generated in a "dist" directory.