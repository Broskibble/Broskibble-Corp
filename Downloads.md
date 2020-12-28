<downloads-button
  button-type="submit"
  type="primary"
  icon="basket"
  size="large"
  shape="full"
  :loading="addingToCart"
  :disabled="product.stock > 0"
  :autofocus="false"
  :action="addToCart">
  Add to cart
</downloads-button>
