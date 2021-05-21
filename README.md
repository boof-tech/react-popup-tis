# react-popup-tis

>

[![NPM](https://img.shields.io/npm/v/react-popup-tis.svg)](https://www.npmjs.com/package/react-popup-tis) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
![react-popup-tis Banner](https://user-images.githubusercontent.com/76048512/119125621-42238300-ba47-11eb-9555-a91102364fa5.gif)

## Install

```bash
npm i react-popup-tis
```

or

```bash
yarn add react-popup-tis
```

## Usage

```jsx
import React from 'react'

import { Popup } from 'react-popup-tis'
import 'react-popup-tis/dist/index.css'

const App = () => {
  return (
    <Popup
      className='Popup'
      msg='Visit GitHub'
      darkMode={false}>
        <a href='http://github.com'>
          GitHub
        </a>
    </Popup>
  )
}

export default App
```

## License

MIT © [boof-tech](https://github.com/boof-tech)
