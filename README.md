# simple_cart

This is jquery plugin for a simple cart functionality. The simple shopping cart will be able to

* Add items to cart
* Remove Items from cart (to remove any items make the count to '0').
* Display count of each item
* Display each item total cost & Total cart cost
* Save the cart to local storge.

# How to Use

**Include boostarp css/js & Jquery links.**
```
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="../lib/js/jquery-3.3.1.min.js" ></script>
```
**Include simple Cart css/js**
```
<script src="../lib/js/jQuery.SimpleCart.js" ></script>
<link href="../lib/css/simple_cart.css" rel="stylesheet">
```

## Include HTML there are tow parts 'Products' & 'Cart'

**Products HTML**

    Check the Example HTML for the sample code. Or you can just add class 'sc-add-to-cart' to the products add button.
    
**Cart HTML**
```
<div class="col-md-3">
        <div id="cart"></div>
</div>
```

**Invoke Simple Cart Plugin**
```
<script type="text/javascript">
    $(document).ready(function(){
        $('#cart').simpleCart();
    });
</script>
```
**Example**

![example](https://user-images.githubusercontent.com/40199915/41341960-afaaf7f0-6f18-11e8-8bf7-c04770b599ed.png)
