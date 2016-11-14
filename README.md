# Bootstrap auto dismiss alerts

### Simple plugin to auto dismiss/close Bootstrap 3.x alert

## Usage

Add `data-auto-dismiss` attribute to alert component.

```html
<div class="alert alert-warning alert-dismissible" data-auto-dismiss role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>
```

### Set custom timeout

By default timeout is  5000ms, it can be overridden.

```html
<div class="alert alert-success" role="alert" data-auto-dismiss="2000">
  Example
</div>
```

## Events

Bootstrap events are triggered since Bootstrap dismiss alert functionality is used. [Bootstrap Alerts Javascript Documentation](http://getbootstrap.com/javascript/#alerts)