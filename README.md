Example Code

$(document).ready(function() {
    calculator.ini({
        storage : "localStorage",
        selector : {
            screen : "#input",
            radDeg : "#rad-deg",
            radDegInvert : "#rad-deg-invert"
        },
        options: {
            log : true
        },
        max : 15
    });
});
