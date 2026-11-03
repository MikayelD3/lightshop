LIGHT SHOP WEBSITE

Files
  index.html   the whole website (open it in any browser)
  images/      logos, room photos and product photos

Change your contact details
  Open index.html in a text editor (Notepad, TextEdit, VS Code).
  Find "1) SHOP DETAILS" near the top and replace phone, email, address, hours,
  social links and currency.

Add a product
  1. Put the photo in the images folder, e.g. images/ls-005.jpg
     (square photos look best, about 800 x 800 px).
  2. In index.html find "2) PRODUCTS" and copy one block, for example:

  {
    code: "LS-005",
    name: "Brass table lamp",
    category: "Table lamps",
    price: 120,
    image: "images/ls-005.jpg",
    size: "H 45 cm",
    finish: "Brushed brass",
    light: "E27 bulb",
    description: "Bedside lamp with a clear glass shade."
  },

  3. Paste it after the last product, change the values, save, and refresh the browser.
  Rules: text in "quotes", price is a number without a symbol (0 = Price on request),
  every block ends with a comma except the last one, codes must be unique.
  A new category name creates a new filter button automatically.
