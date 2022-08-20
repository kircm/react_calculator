Calculator
---
<img src="Logotype primary.png" width="60%" height="60%" />

Created with *create-react-app*. See the [full create-react-app guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).



Try It
---

[ahfarmer.github.io/calculator](https://ahfarmer.github.io/calculator/)



Install
---
`yarn install`


Usage
---

`npm start`


Backwards compatibility
----

- Installing packages using `npm install` produces error
  
  `TypeError: fsevents is not a constructor`
  
  when starting with `npm start`

- Installing packages using `yarn install`:
  
  - warning:
    
    `warning react-scripts > fsevents@2.1.2: "Please update to latest v2.3 or v2.2"`

  - `npm start` -> OK

