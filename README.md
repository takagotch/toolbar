### toolbar
---
https://github.com/paulkinzett/toolbar

```
<div class="btn-toolbar"></div>
<div class="btn-toolbar btn-toolbar-primary"></div>

<div data-toolbar="user-options"></div>

<script src="jquery.toolbar.js"></script>

<link href="jquery.toolbar.css" rel="stylesheet" />

<div id="toolbar-options" class="hidden">
  <a href="#"><i class="fa fa-plane"></i></a>
  <a href="#"><i class="fa fa-car"></i></a>
  <a href="#"><i class="fa fa-bicycle"></i></a>
</div>

<div
  data-toolbar="user-options"
  data-toolbar-event="click"
  data-toolbar-style="primary"
>
```

```js
$('#element').toolbar( options );

$('#button').toolbar(
  content: '$toolbar-options'
);

$('#button').toolbar(
  content: '#toolbar-options'
  position: 'bottom'
);

$('#button').toolbar(
  content: '#toolbar-options',
  position: 'buttom',
  style: 'primary'
);

$('#button').toolbar(
  content: '#toolbar-options',
  position: 'bottom',
  style: 'primary',
  animation: 'flip'
);

$('#button').toolbar(
  content: '#toolbar-options',
  position: 'bottom',
  style: 'primary',
  event: 'click'
);

$('#button').toolbar({
  content: '#toolbar-options',
  position: 'button',
  style: 'primary',
  event: 'click',
  hideOnClick: true
});

$('a').toolbar({
  content: '#tool-options',
  position: 'top',
  adjustment: 35
});

$('div[data-toolbar="user-options"]').toolbar( options );

$('#element').on('toolbarShown',
  function( event ){
  }
);

```

```
```

