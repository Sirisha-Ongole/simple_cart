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
```
<div class="col-md-9 search-grid">
<div class="product-container">
<!-- Menu List of items -->
<div class="menu-list">
<div class="panel panel-default" id="content1">
<div class="panel-heading">Products</div>
<div class="panel-body">
<div class="row">
<div class="col-md-6">
    <div class="menu-item-container"><div class="item-name">Veg biriyani</div><div><i class="veg-icon"></i></div>
        <div class="item-price-container">
            <div class="item-price">
                <i class="fa fa-rupee"></i>199
            </div>
            <div class="spacer"></div>
            <div class="add-button">
                <button class="btn btn-primary sc-add-to-cart" data-name="Veg biriyani" data-price="199" type="submit">ADD</button>
            </div>
        </div>
    </div>
</div>
<div class="col-md-6">
    <div class="menu-item-container"><div class="item-name">Sweet Corn Soup</div><div><i class="fa fa-dot-circle-o veg-icon"></i></div>
        <div class="item-price-container">
            <div class="item-price">
                <i class="fa fa-rupee"></i>50
            </div>
            <div class="spacer"></div>
            <div class="add-button">
                <button class="btn btn-primary sc-add-to-cart" data-name="Sweet Corn Soup" data-price="50" type="submit">ADD</button>
            </div>
        </div>
    </div>
</div>
<div class="col-md-6">  
    <div class="menu-item-container"><div class="item-name">Corn fried Rice</div><div><i class="fa fa-dot-circle-o veg-icon"></i></div>
        <div class="item-price-container">
            <div class="item-price">
                <i class="fa fa-rupee"></i>112
            </div>
            <div class="spacer"></div>
            <div class="add-button">
                <button class="btn btn-primary sc-add-to-cart" data-name="Corn fried Rice" data-price="112" type="submit">ADD</button>
            </div>
        </div>
    </div>
</div>
<div class="col-md-6">
    <div class="menu-item-container"><div class="item-name">Orange Juice</div><div><i class="fa fa-dot-circle-o veg-icon"></i></div>
        <div class="item-price-container">
            <div class="item-price">
                <i class="fa fa-rupee"></i>50
            </div>
            <div class="spacer"></div>
            <div class="add-button">
                <button class="btn btn-primary sc-add-to-cart" data-name="Orange Juice" data-price="50" type="submit">ADD</button>
            </div>
        </div>
    </div>
</div>
<div class="col-md-6">
    <div class="menu-item-container">
        <div class="item-name">Aloo Tikis</div>
        <div><i class="fa fa-dot-circle-o veg-icon"></i></div>
        <div class="item-price-container">
            <div class="item-price">
                <i class="fa fa-rupee"></i>89
            </div>
            <div class="spacer"></div>
            <div class="add-button">
                <button class="btn btn-primary sc-add-to-cart" data-name="Aloo Tikis" data-price="89" type="submit">ADD</button>
            </div>
        </div>
    </div>
</div>
</div>
</div>
</div>
</div>
<!-- //Menu List of items -->
</div>
</div>
```
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
