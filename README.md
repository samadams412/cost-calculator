# React Practice #1 - Cost Calculator

### Tech Used:
* Axios to fetch dummy product data
* useReducer to manage products and cart as it is more scalable and effecient than useState. I was able to add all the logic in one place. This app includes 4 reducers: "ADD_PRODUCTS", "ADD_TO_CART", "REMOVE_FROM_CART", "CHANGE_CART_QTY".
* useEffect to render the fetched products on page load
* Other methods used include: Array.prototype.some() to return true if a product was included in the cart, Array.prototype.map() to render each product from the axios.get('https://dummyjson.com/products') and the products added to the cart, and Array.prototype.reduce() to calculate the total cost of all items in the cart
* To save time only in-line styles were used

## Future development
* Could be made much more advanced with Context API

![image](/cost-calculator/public/cost-calc.JPG)