# VueJS-guide

### Creating a project and starting 
- vue create (project name here)

- cd (project name here)
- npm run serve

### Creating a project using Vue UI
- vue ui

### v-bind directive
v-bind Dynamically bind an attribute to an expressionv-bind Shorthand

### v-if directive
<p v-if="inventory > 10">In Stock</p>
            <p v-else-if="inventory <= 10 && inventory > 0">Almost sold out!</p>
            <p v-else>Out of Stock </p>
  
 This will check inventory and display "In Stock" if inventory is =true otherwise it will display Out of stock, else if inventory is less than or equal to 10 and greater than 0 than it will display Almost sold out  
 ### v-on directive
 <button class="button" v-on:click="cart +=1">Add to Cart</button>
 
 v-on:click="cart +=1"
 
 Click will be the event we are listening for and when it's clicked, it will trigger the expression "cart +=1"
 
 Shorthand for v-on:  @

@click="cart+=1"
 
 ### Vue version of hover
 
 @mouseover
