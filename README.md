# Spotlight React Native components.

Spotlitght is a library based on javascript/typescrip created for those people who like to get a better interaction with their and users.  
For more inormations visit our page and read the [documentation](#)

### Features

* Personalized components
* Quick implementation
* Typescript

## installation.

### npm
Installation using `npm`
```js
npm install @react-native-spotlight @react-native-spotlight/components
```

### yarn 
Installation using `yarn`
```js 
yarn add @react-native-spotlight @react-native-spotlight/components
```


### Quick implementation
```js

import React, { useState } from 'react';
import { BasicTextInput } from '@react-native-spotlight/components';

const MyApp() => {
  const [ username, setUsername ] = useState();
  return (
    <BasicTextInput onChangeText={(text)=> setUsername(text)} placeholder="Type your username"/>
  );
}

export default MyApp

```

### Props

| Props                                      | Params               | isRequire        | default                            |
| ------------------------------------------ | -------------------- | ---------------- | ---------------------------------- |
| value                                      | string               | No               | undefine                           |
| onChangeText                               | function             | No               | undefined                          |
| width                                      | string               | no               | 100%                               |
