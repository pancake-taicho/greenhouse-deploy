<template>
  <div id="expense-input-container">
    <form id="expense-input-form" action="">
      <label for="expense-input">
        <input class="expense-input-button" type="date" name="date-input">
        <br>
        <input class="expense-input-button" type="text" name="amount-input" placeholder="Amount">
        <br>
        <input class="expense-input-button" type="text" name="description-input" placeholder="Description">
      </label>
      <div id="category-button-container">
        <input id="groceries" class="category-button" type="radio" name="groceries" value="groceries">
        <label for="groceries">Groceries</label>
        <input id="bills" class="category-button" type="radio" name="bills" value="bills">
        <label for="bills">Bills</label>
        <input id="transport" class="category-button" type="radio" name="transport" value="transport">
        <label for="transport">Transport</label>
        <input id="misc" class="category-button" type="radio" name="misc" value="misc">
        <label for="misc">Misc</label>
      </div>
      <div id="eco-action-container">
        <input id="eco-bag-no-bag" class="eco-action-checkbox" type="checkbox" name="eco-bag-no-bag" value="eco-bag-no-bag">
        <label for="eco-bag-no-bag">Eco bag/no bag</label>
        <br>
        <input id="no-impulse-buy" class="eco-action-checkbox" type="checkbox" name="no-impulse-buy" value="no-impulse-buy">
        <label for="no-impulse-buy">No impulse buy</label>
        <br>
        <input id="eco-conscious-transport" class="eco-action-checkbox" type="checkbox" name="eco-conscious-transport" value="eco-conscious-transport">
        <label for="eco-conscious-transport">Eco-conscious transport</label>
      </div>
      <button form="expense-input-form" type="submit" name="submit" value="submit">Submit</button>
    </form>
  </div>  
</template>

<script>
export default {
  name: "ExpenseInput",
  props: {
  },
  methods: {    
  },
}
</script>

<style scoped>

</style>