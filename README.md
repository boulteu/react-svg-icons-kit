# React SVG Icons Kit

A collection of SVG icons built as React components

## Installation

The package can be installed via [npm](https://github.com/npm/cli):

```
npm install react-svg-icons-kit --save
```

You’ll need to install React separately since those dependencies aren’t included in the package. Below is a simple example of how to use the SVG Icons Kit in a React view.

```js
import React from "react";
import { Arrow } from "react-svg-icons-kit";

const Example = () => {
  return (
      <Arrow className={`w-2 h-2 fill-slate-400`} transform={`rotate(180)`} />
  );
};
```

## Configuration

You can use the following icons :
- `Add` ➕
- `Arrow` →
- `Close` ✖
- `Loading` 🔄
- `Remove` −
- `Search` 🔍

```js
<Add />
<Arrow />
<Close />
<Loading />
<Remove />
<Search />
```

## Compatibility

### React

We're always trying to stay compatible with the latest version of React.