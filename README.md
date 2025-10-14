STEP 1 — Understand the Task First
  You are asked to create a shopping list, where:
  The user can add items.
  Each item has:
  name
  quantity
  price per item
  The program must calculate the total price (quantity × price).
  Then, display the shopping list sequentially in a table.
STEP 2 - prepare code what be used like:
- create a variabel for save data from user
- create a variabel for ask the user how many items they want
- used for loop for repeat as many times to be the same as variabel use how many items want like:
  a.name of goods
  b.purchased items
  c.price of goods
  d.sum from all purchased item
- create a variable for count result,like:purchased items X price of goods
- create a variable for sort item
- preaper in array
- result all from item example code:
   let totalKeseluruhan = 0;

  for (let i = 0; i < daftarBelanja.length; i++) {
    const item = daftarBelanja[i];
    totalKeseluruhan += item.total;
STEP 3 - Create display for in browser
  - show shooping table
  - show all result shooping 
