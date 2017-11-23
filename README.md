# QJ-Button

react component button

## Install

```shell
npm install qj-button
```

## Usage

```javascript
import React from 'react';
import ReactDOM from 'react-dom';
import qjButton from 'qj-button'

const element = document.getElementById('root');

ReactDOM.render(<qjButton>button</qjButton>, element);
```

## API

Button

| Name            | Type        | Default           | Description                   |
| --------------- | ----------- | ----------------- | ----------------------------- |
| prefixCls       | string      | 'qj-button'       | prefixCls of this component   |
| children        | string/node |                   |                               |
| type            | string      | 'default'         | type of style                 |
| disabled        | bool        | false             | disable click event           |
| group           | bool        | false             | button is in group            |
| inline          | bool        | false             | button is inline              |
| loading         | bool        | false             | button is loading and disable |
| activeClassName | string      | 'qj-button-active | custom pressed className      |
| iconClass       | string      | null              | className of icon             |
| className       | string      | ''                | custom className              |
| onClick         | func        | ()=>{}            | callback after click          |
|                 |             |                   |                               |

