# position-pictures-centrally

![alt text](http://was-one.de/wp-content/themes/was/images/was_logo.png "position-pictures-centrally")

With these few lines of Css,
all images can be positioned centrally in a container.

Regardless of whether it is in
* portrait
* landscape
* rectangular
* square
format.


In this example I used bootstrap to create the reason.
But you do not need it.


## Example

### HTML
```javascript
<div class="img-wrap">
  <img src="http://via.placeholder.com/400x400" alt="Placeholder">
</div>
```

***

### CSS
```javascript
.img-wrap{
  position: relative;
  overflow: hidden;
  min-height: 200px;
}
.img-wrap img{
  position: absolute;
  top: -100%;
  right: -100%;
  bottom: -100%;
  left: -100%;
  margin: auto;
  max-width: 100%;
  max-height: 100%;
}
```
