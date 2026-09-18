# FoodieGo

FoodieGo is a frontend food delivery and recipe discovery app where cravings meet creativity. Browse meals, customize favourites, discover recipes, manage a cart, apply coupons, and simulate delivery tracking.

## Features
- Responsive home, menu, food detail, customization, cart, tracking, login, and register pages
- Search and category filtering for food and recipes
- Cart quantities, customized items, coupon `FOOD10`, and localStorage persistence
- Client-side form validation and order status simulation
- Accessible labels, toast feedback, empty cart state, and responsive layouts

## Technologies Used
**Frontend project built using HTML, CSS, JavaScript and Bootstrap 5.** Bootstrap Icons and Google Fonts are loaded from CDNs.

## Pages
`index.html`, `menu.html`, `recipe.html`, `food-details.html`, `customize.html`, `cart.html`, `tracking.html`, `login.html`, and `register.html`.

## How to Run
Run the project from this folder so relative paths such as `css/style.css` and `js/script.js` resolve correctly.

### Recommended: VS Code task
1. Open the `FoodieGo` folder in VS Code.
2. Run `Terminal > Run Task > FoodieGo: Start local server`.
3. Open http://127.0.0.1:5500/index.html.

### Terminal method
```powershell
cd "c:\Users\Snarm\OneDrive\Desktop\FoodieGo"
python -m http.server 5500
```

Then open http://127.0.0.1:5500/index.html. Stop the server with `Ctrl+C`.

Internet access is recommended because food photography, Bootstrap, icons, and fonts use public CDNs.
