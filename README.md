# craft-button-calebhsu

Parameterized button model.

### Install
    $ npm install craft-button-calebhsu

### Parameters
- width: adjusts width of button
- height: adjusts thickness of button

### Example
```html
<craft>
    <craft name="button" module="calebhsu/craft-button"/>
    <row spacing="1">
        <button transform="scale(3,3,3)"></button>
        <button width="10" height="3"></button>
        <button></button>
    </row>
</craft>
```

![example](example.png)