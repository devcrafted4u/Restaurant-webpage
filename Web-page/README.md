# Ravi's Kitchen 🍽️

A modern, responsive restaurant website for **Ravi's Kitchen**, designed with a warm luxury restaurant style inspired by the provided reference design.

## ✨ Features

- Responsive restaurant homepage
- Elegant navigation bar
- Hero section with restaurant introduction
- View Menu and Book a Table buttons
- Fresh Ingredients, Expert Chefs, Authentic Flavors, and Warm Atmosphere sections
- Restaurant story / About section
- Menu with All, Vegetarian, and Non-Veg filters
- Food cards with images, descriptions, and prices
- Restaurant gallery
- Table reservation form
- WhatsApp reservation integration
- Contact and opening-hours section
- Responsive mobile navigation
- Desktop, tablet, and mobile support
- Separate HTML and CSS files

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Unsplash images
- WhatsApp link integration

## 📁 Project Structure

```text
ravi-kitchen/
│
├── index.html
├── style.css
└── README.md
```

## 🚀 How to Run

### Using VS Code + Live Server

1. Open the project folder in Visual Studio Code.
2. Make sure `index.html` and `style.css` are in the same folder.
3. Install the **Live Server** extension.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. The website will open in your browser.

### Open Directly

You can also double-click `index.html` to open the website in a browser.

## 🎨 Design

The website uses a restaurant-focused visual style:

- **Dark Green** — premium restaurant feel
- **Gold** — buttons and highlights
- **Cream/White** — clean content sections
- **Playfair Display** — elegant headings
- **DM Sans** — clean body text

## 🍴 Menu

The sample menu includes:

- Butter Chicken
- Palak Paneer
- Veg Biryani
- Chicken Tikka
- Dal Tadka
- Gulab Jamun

The menu filter allows visitors to display all dishes, vegetarian dishes, or non-vegetarian dishes.

## 📅 Table Reservation

The reservation form collects:

- Name
- Phone number
- Date
- Time
- Number of guests
- Special request

After submission, the reservation details are prepared and opened in WhatsApp.

### Important

Before publishing, update the WhatsApp number in `index.html`.

Search for:

```text
919876543210
```

and replace it with the restaurant's actual WhatsApp number, including the country code.

## 📞 Restaurant Information

The website contains sample:

- Address
- Phone number
- Email
- Opening hours

Replace these with the actual restaurant information before deployment.

## 🖼️ Images

The current design uses online images from Unsplash.

For a real restaurant website, replace the sample image URLs with your own:

- Restaurant interior photos
- Food photos
- Chef photos
- Exterior photos
- Gallery images

## 📱 Responsive Design

The website is designed for:

- Desktop
- Laptop
- Tablet
- Mobile phone

The navigation automatically changes to a mobile menu on smaller screens.

## 🔧 Customization

### Change Restaurant Name

Search for:

```text
Ravi's Kitchen
```

in `index.html` and replace it with your restaurant name.

### Change Colors

Open `style.css` and edit the variables at the top:

```css
:root {
  --green-950: #07140f;
  --green-900: #0c2119;
  --green-800: #12382b;
  --gold: #e5ad4d;
  --gold-light: #f7c766;
  --cream: #f6f7f1;
}
```

### Change Menu Items

Edit the menu cards inside `index.html` under the **OUR MENU** section.

## 🌐 Deployment

This frontend website can be deployed using:

- GitHub Pages
- Netlify
- Vercel
- Standard web hosting

The basic version does not require a backend server.

## 📌 Future Improvements

Possible future additions:

- Online food ordering
- Shopping cart
- Real database for reservations
- Admin dashboard
- User login and registration
- Online payment
- Table availability
- Customer reviews
- Google Maps integration
- Backend API
- Email reservation confirmation
- Authentication system

## 👨‍💻 Project Information

**Project:** Ravi's Kitchen Restaurant Website  
**Type:** Responsive Restaurant Website  
**Frontend:** HTML, CSS, JavaScript

---

Made with ❤️ for good food.
