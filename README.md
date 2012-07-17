Foundation
================================

Build it strong.

Template
-------------------------

<table>
    <thead>
        <tr>
            <th>Class</th>
            <th>Extends</th>
            <th>Description</th>
            <th>Required</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>page</code></td>
            <td>&nbsp;</td>
            <td>Page object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>liquid</code></td>
            <td><code>page</code></td>
            <td>Turns a fixed layout to a liquid layout</td>
            <td>No</td>
        </tr>
        <tr>
            <td><code>main</code></td>
            <td>&nbsp;</td>
            <td>Main page object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>leftCol</code></td>
            <td>&nbsp;</td>
            <td>Left column object</td>
            <td>No</td>
        </tr>
        <tr>
            <td><code>rightCol</code></td>
            <td>&nbsp;</td>
            <td>Right column object</td>
            <td>No</td>
        </tr>
        <tr>
            <td><code>foot</code></td>
            <td>&nbsp;</td>
            <td>Page footer object</td>
            <td>No</td>
        </tr>
    </tbody>
</table>

### Example ###

```html
<div class="page liquid">
    <div class="head"></div>
    <div class="body">
        <div class="leftCol"></div>
        <div class="rightCol"></div>
        <div class="main"></div>
    </div>
    <div class="foot"></div>
</div>
```

Grid
-------------------------

<table>
    <thead>
        <tr>
            <th>Class</th>
            <th>Extends</th>
            <th>Description</th>
            <th>Required</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>row</code></td>
            <td>&nbsp;</td>
            <td>Grid row object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>col</code></td>
            <td>&nbsp;</td>
            <td>Grid column object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>span</code></td>
            <td><code>col</code></td>
            <td>Defines the span of a grid column object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>lastCol</code></td>
            <td><code>col</code></td>
            <td>Defines the last column of a grid column object</td>
            <td>Yes (on last column only)</td>
        </tr>
    </tbody>
</table>

### Example ###

```html
<div class="row">
    <div class="col span1of5"></div>
    <div class="col span3of5"></div>
    <div class="col span1of5 lastCol"></div>
</div>
```

Module
-------------------------

<table>
    <thead>
        <tr>
            <th>Class</th>
            <th>Extends</th>
            <th>Description</th>
            <th>Required</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>mod</code></td>
            <td>&nbsp;</td>
            <td>Module container object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>inner</code></td>
            <td>Module inner object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>hd</code></td>
            <td>&nbsp;</td>
            <td>Module header object</td>
            <td>No</td>
        </tr>
        <tr>
            <td><code>bd</code></td>
            <td>&nbsp;</td>
            <td>Module body object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>ft</code></td>
            <td>&nbsp;</td>
            <td>Module footer object</td>
            <td>No</td>
        </tr>
    </tbody>
</table>

### Example ###

```html
<div class="mod">
    <div class="inner">
        <div class="hd"></div>
        <div class="bd"></div>
        <div class="ft"></div>
    </div>
</div>
```

Media
-------------------------

<table>
    <thead>
        <tr>
            <th>Class</th>
            <th>Extends</th>
            <th>Description</th>
            <th>Required</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>media</code></td>
            <td>&nbsp;</td>
            <td>Media container object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>img</code></td>
            <td>&nbsp;</td>
            <td>Media image object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>bd</code></td>
            <td>&nbsp;</td>
            <td>Media body object</td>
            <td>Yes</td>
        </tr>
    </tbody>
</table>

### Example ###

```html
<div class="media">
    <div class="img"></div>
    <div class="bd"></div>
</div>
```