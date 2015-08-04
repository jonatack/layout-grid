---
layout: index
---
<div class="container">
    <h1>Configurable Options</h1>

    <div class="lead">
        Modify options on the fly or set them as data attributes
    </div>

    <pre class="code">
&lt;div
 data-arrange="layout-grid"
 data-overlap="false"
 data-compact="true"
 data-resize="true"&gt;
&lt;/div&gt;</pre>

    <div class="checkbox">
        <label>
            <input type="checkbox" onchange="$('#lt-grid').lt_grid('update', 'overlap', this.checked)"> Allow overlap on items when reordering
        </label>
    </div>

    <div class="checkbox">
        <label>
            <input type="checkbox" autocomplete="off" checked onchange="$('#lt-grid').lt_grid('update', 'compact', this.checked)"> Compact items after reorder, by reducing horizontal space
        </label>
    </div>

    <div class="checkbox">
        <label>
            <input type="checkbox" autocomplete="off" checked onchange="$('#lt-grid').lt_grid('update', 'resize', this.checked)"> Resize the container after reorder to encompass all items
        </label>
    </div>

    <div
     id="lt-grid"
     data-arrange="layout-grid"
     class="lt-container
            lt-xs-h-9
            lt-sm-h-6
            lt-md-h-4
            lt-lg-h-3">

        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-0
                lt-xs-w-1
                lt-xs-h-1
                lt-sm-x-0
                lt-sm-y-0
                lt-sm-w-1
                lt-sm-h-1
                lt-md-x-0
                lt-md-y-0
                lt-md-w-1
                lt-md-h-1
                lt-lg-x-0
                lt-lg-y-0
                lt-lg-w-1
                lt-lg-h-1">
            <div class="lt-body bg-info text-center">
                <h3>1</h3>
            </div>
        </div>
        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-1
                lt-xs-w-1
                lt-xs-h-2
                lt-sm-x-1
                lt-sm-y-0
                lt-sm-w-1
                lt-sm-h-2
                lt-md-x-2
                lt-md-y-0
                lt-md-w-1
                lt-md-h-2
                lt-lg-x-1
                lt-lg-y-0
                lt-lg-w-1
                lt-lg-h-2">
            <div class="lt-body bg-info text-center">
                <h3>2</h3>
            </div>
        </div>
        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-3
                lt-xs-w-1
                lt-xs-h-1
                lt-sm-x-0
                lt-sm-y-1
                lt-sm-w-1
                lt-sm-h-1
                lt-md-x-1
                lt-md-y-0
                lt-md-w-1
                lt-md-h-1
                lt-lg-x-0
                lt-lg-y-1
                lt-lg-w-1
                lt-lg-h-1">
            <div class="lt-body bg-info text-center">
                <h3>3</h3>
            </div>
        </div>
        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-4
                lt-xs-w-1
                lt-xs-h-2
                lt-sm-x-0
                lt-sm-y-2
                lt-sm-w-2
                lt-sm-h-2
                lt-md-x-0
                lt-md-y-1
                lt-md-w-2
                lt-md-h-2
                lt-lg-x-2
                lt-lg-y-0
                lt-lg-w-2
                lt-lg-h-2">
            <div class="lt-body bg-info text-center">
                <h3>4</h3>
            </div>
        </div>
        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-6
                lt-xs-w-1
                lt-xs-h-1
                lt-sm-x-0
                lt-sm-y-4
                lt-sm-w-1
                lt-sm-h-1
                lt-md-x-2
                lt-md-y-2
                lt-md-w-1
                lt-md-h-1
                lt-lg-x-0
                lt-lg-y-2
                lt-lg-w-1
                lt-lg-h-1">
            <div class="lt-body bg-info text-center">
                <h3>5</h3>
            </div>
        </div>
        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-7
                lt-xs-w-1
                lt-xs-h-1
                lt-sm-x-0
                lt-sm-y-5
                lt-sm-w-2
                lt-sm-h-1
                lt-md-x-1
                lt-md-y-3
                lt-md-w-2
                lt-md-h-1
                lt-lg-x-1
                lt-lg-y-2
                lt-lg-w-2
                lt-lg-h-1">
            <div class="lt-body bg-info text-center">
                <h3>6</h3>
            </div>
        </div>
        <div
         draggable="true"
         class="lt
                lt-xs-x-0
                lt-xs-y-8
                lt-xs-w-1
                lt-xs-h-1
                lt-sm-x-1
                lt-sm-y-4
                lt-sm-w-1
                lt-sm-h-1
                lt-md-x-0
                lt-md-y-3
                lt-md-w-1
                lt-md-h-1
                lt-lg-x-3
                lt-lg-y-2
                lt-lg-w-1
                lt-lg-h-1">
            <div class="lt-body bg-info text-center">
                <h3>7</h3>
            </div>
        </div>
    </div>

</div>
