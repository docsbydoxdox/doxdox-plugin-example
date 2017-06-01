# [doxdox-plugin-example](https://github.com/neogeek/doxdox-plugin-example) *1.0.4*

> Example template plugin for doxdox.


### index.js


#### plugin(data) 

Example template plugin for doxdox.




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| data | `Array`  | Methods parsed using a doxdox parser. | &nbsp; |




##### Examples

```javascript
parseInputs(inputs, {'parser': 'dox', 'layout': 'example'}).then(content => console.log(content));
```


##### Returns


- `Promise`  Promise with generated content.




*Documentation generated with [doxdox](https://github.com/neogeek/doxdox).*
