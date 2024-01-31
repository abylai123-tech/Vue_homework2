<template>
  <div>
    <Header title="My Awesome Store" />
    <ProductCard
      productName="Product 1"
      description="This is a great product."
      price="$19.99"
    />
    <Button buttonText="Buy Now" buttonColor="#27ae60" />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import ProductCard from "./components/ProductCard.vue";
import Button from "./components/Button.vue";

export default {
  components: {
    Header,
    ProductCard,
    Button
  }
};
</script>

<style scoped>

</style>  