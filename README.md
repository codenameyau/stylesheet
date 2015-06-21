# stylesheet

Wrapper for stylesheets with JavaScript.

```
bower install stylesheet --save-dev
```

## Usage Example

```javascript
var stylesheet = new StyleSheet();

// Specify the selector to work on.
stylesheet.setSelector('.pause-hud');

// Insert rules.
stylesheet.insertRule('width: 100%');
stylesheet.insertRule('height: 100%');
stylesheet.insertRule('display: none');
stylesheet.insertRule('z-index: 100');
stylesheet.insertRule('background: rgba(0, 0, 0, 0.5)');
stylesheet.insertRule('cursor: default');

// Apply rules.
stylesheet.applyRules();
```
