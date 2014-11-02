<h1>Example JS Code</h1>

```
$(document).ready(function() {
    calculator.ini({
        storage : "localStorage",                // storage object
        selector : {
            screen : "#input",                   // screen selector
            radDeg : "#rad-deg",                 // rad/deg selector
            radDegInvert : "#rad-deg-invert"     // inverted rad/deg selector
        }
        max : 15                                 // max number allowed
    });
});
```

<h1>Functions & VARIABLES</h1>
```
/*-------------------------FUNCTIONS------------------------------
|                                                                |
|  ini(options)               - initiate the calculator          |
|  numberClicked              - called when number is clicked    |
|  screen                     - screen functions                 |
|    set(value)               - set screen value                 |
|    get                      - get screen value                 |
|    length                   - get screen length                |
|    clear                    - clear screen                     |
|
|
|  m                          - memory functions                 |
|    recall                   - get number in memory             |
|    clear                    - clear the current memory number  |
|
|
|
|
|
------------------------------------------------------------------

----------------------------VARIABLES-----------------------------
|                                                                |
|  calculator.max             - max legnth calculator is allowed |
|  calculator.selector.screen - selector for calculator screen   |
|
|
|
|
------------------------------------------------------------------*/
```
