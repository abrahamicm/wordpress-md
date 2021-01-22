aqui hay tutorial web sobre esto

[businessbloomer](https://www.businessbloomer.com/woocommerce-easily-get-product-info-title-sku-desc-product-object/)

~~~php
// Get $product object from product ID
  
$product = wc_get_product( $product_id );
  
// Now you have access to (see above)...
  
$product->get_type();
$product->get_name();
// etc.
// etc.

~~~

desde fuera de wordpress de puede usar esta [alternativa](https://stackoverflow.com/questions/41730193/using-wc-get-product-with-a-php-variable-for-product-id)


