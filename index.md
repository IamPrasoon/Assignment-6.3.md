
<!DOCTYPE html>
<html>
<head>
    <title>CSS Overflow</title>
    <style>
        .box {
            width: 250px;
            height: 80px;
            border: 2px solid blue;
            margin: 20px;
        }
        .visible { overflow: visible; }
        .hidden { overflow: hidden; }
        .auto { overflow: auto; }
        .scroll { overflow: scroll; }
    </style>
</head>
<body>
    <h1>CSS Overflow Examples</h1>

    <h3>Visible</h3>
    <div class="box visible">
        This is a long paragraph containing extra text
        that will overflow outside the fixed-size box.
        More content is added to demonstrate overflow.
    </div>

    <h3>Hidden</h3>
    <div class="box hidden">
        This is a long paragraph containing extra text
        that will overflow outside the fixed-size box.
        More content is added to demonstrate overflow.
    </div>

    <h3>Auto (Fixed Layout)</h3>
    <div class="box auto">
        This is a long paragraph containing extra text
        that will overflow outside the fixed-size box.
        More content is added to demonstrate overflow.
    </div>

    <h3>Scroll</h3>
    <div class="box scroll">
        This is a long paragraph containing extra text
        that will overflow outside the fixed-size box.
        More content is added to demonstrate overflow.
    </div>
</body>
</html>
