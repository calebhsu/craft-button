# craft-button-calebhsu

Parameterized button model.

### Usage
```html
<craft>
    <craft name="button" module="craft-button-calebhsu"/>
    <button></button>
</craft>
```

### Parameters
- width: adjusts width of button
- height: adjusts thickness of button

### Example
```html
<craft>
    <craft name="button" module="craft-button-calebhsu"/>
     <row spacing="1">
        <button transform="scale(2 2 2)"></button>
        <button width="10" height="2"></button>
        <button></button>
    </row>
</craft>
```

![example](example.png)