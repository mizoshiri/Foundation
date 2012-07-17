Foundation
================================

Build it strong.

Template
-------------------------

```html
<div class="page">
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
            <th>Property</th>
            <th>Description</th>
            <th>Required?</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>mod</code></td>
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
            <td>Module header object</td>
            <td>No</td>
        </tr>
        <tr>
            <td><code>bd</code></td>
            <td>Module body object</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><code>ft</code></td>
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

```html
<div class="media">
    <div class="img"></div>
    <div class="bd"></div>
</div>
```