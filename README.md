# React SVG Icons Kit

A collection of SVG icons built as React components

## Installation

The package can be installed via [npm](https://github.com/npm/cli):

```
npm install react-svg-icons-kit --save
```

You’ll need to install React and Tailwind CSS separately since those dependencies aren’t included in the package.

Once Tailwind CSS installed, you'll need to add `"./node_modules/react-svg-icons-kit/**/*.{js,ts,jsx,tsx,mdx}"` to `content` in your `tailwind.config.js` file.

Below is a simple example of how to use the SVG Icons Kit in a React view.

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
import React from "react";
import { Add, Arrow, Close, Loading, Remove, Search } from "react-svg-icons-kit";

const Example = () => {
    return (
        <div>
            <Add />
            <Arrow />
            <Close />
            <Loading />
            <Remove />
            <Search />
        </div>
    );
};
```

## Compatibility

### Tailwind CSS

This package has been developed with version 3.4.6.

### React

We're always trying to stay compatible with the latest version of React.