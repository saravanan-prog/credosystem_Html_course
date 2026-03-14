# Basic Syntax of HTML Events
 Events are added as attributes inside HTML tags.
```
<button onclick="alert('Button clicked')">Click Me</button>
```

## Common HTML Events


#### 1. Click Event (onclick)

``` Triggered when a user clicks an element.

<button onclick="showMessage()">Click</button>

<script>
function showMessage() {
  alert("Hello Saravanan!");
}
</script>
```

###### 2. Double Click (ondblclick)
```
<p ondblclick="alert('Double clicked')">Double click me</p>
```


###### 3. Mouse Events

| Event         | Description           |
| ------------- | --------------------- |
| `onclick`     | Mouse click           |
| `onmouseover` | Mouse enters element  |
| `onmouseout`  | Mouse leaves element  |
| `onmousedown` | Mouse button pressed  |
| `onmouseup`   | Mouse button released |


Example
```
<p onmouseover="this.style.color='red'">
Hover over this text
</p>
```

#### 4. Keyboard Events

| Event        | Description         |
| ------------ | ------------------- |
| `onkeydown`  | Key pressed         |
| `onkeyup`    | Key released        |
| `onkeypress` | Key pressed (older) |


Example
```
<input type="text" onkeyup="console.log('Typing...')">
```

#### 5. Form Events
| Event      | Description         |
| ---------- | ------------------- |
| `onsubmit` | Form submitted      |
| `onchange` | Input value changed |
| `onfocus`  | Input selected      |
| `onblur`   | Input loses focus   |


Example:
```   
<input type="text" onchange="alert('Value changed')">
```


#### 6. Page Events

| Event      | Description    |
| ---------- | -------------- |
| `onload`   | Page loaded    |
| `onresize` | Window resized |
| `onscroll` | Page scrolled  |


Example
```
<body onload="alert('Page loaded')">
```