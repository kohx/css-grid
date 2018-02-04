## std-grid

css grid systam made with css grid layout

## Usage

Load "std-grid.css" CSS

If you use media query then load "std-grid-mq.css" CSS too.

```
<link href="css/std-grid.css" rel="stylesheet" type="text/css"/>
<link href="css/std-grid-mq.css" rel="stylesheet" type="text/css"/>
```

### Examples

```html
<!--1st-->
<div class="grid3 mgrid1 gap2 mgap3"><span>grid3 mgrid1 gap2 mgap3</span>
    <div class="col1">col1</div>

    <div class="col2 mcol1"><span>col2 mcol1</span>

        <!--2nd-->
        <div class="grid3 mgrid2 sgrid1 gap1 mgap2 sgap3">
            <span>grid3 mgrid2 sgrid1 gap1 mgap2 sgap3</span>
            <div class="row1 col3 mcol2 scol1">row1 col3</div>
            <div class="row1 col1">row1 col1</div>
            <div class="row2 col1">row2 col1</div>
            <div class="row3 col1">row3 col1</div>
            <div class="row2 col1">row2 col1</div>
            <div class="row1 col2 mcol2 scol1">row1 col3</div>
            <div class="row1 col1">row1 col1</div>
            <div class="row1 col1">row2 col1</div>
            <div class="row3 col1">row3 col1</div>
            <div class="row1 col1">row1 col1</div>
            <div class="row1 col1">row1 col1</div>
            <div class="row2 col2 scol1">row2 col2</div>
        </div>
        <!--/2nd-->

    </div>
</div>
<!--/1st-->
```

### sample page
https://kohx.github.io/std-grid/
