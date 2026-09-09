# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Spice Mantra | Indian Food in New York, NY | Naan, Roti, About, Hours
purpose: The whole site — a one-page Indian restaurant site carrying the full menu, hours, gallery, reviews and FAQ.
sections:
- `#hero` "Indian Food in Midtown , New York" — hero with the tagline and the ordering and reservation calls to action
- `#about` "Where Tradition Meets Taste" — the restaurant's story and cooking approach
- `#reviews` "What Our Customers Say" — customer review quotes
- `#menu` "Our Menu" — the menu section, holding the parallax image column and the category list below
- `#menuImageCol` — the image column that sits beside the menu
- `#menuParallaxImg` — the parallax image inside that column
- `#menuCategories` — every dish on the menu, 91 priced items running from soups and starters through curries, tandoor, biryani, breads, desserts and drinks: Mulligatawny Soup, Sweet Corn Soup, Sprout Salad, Avocado Salad, Bhel Puri, Dahi Aloo Puri, Samosa, Gobi Malligai, Onion Bhaji, Tofu Tandoori, Kalmi Kabab, Coriander Chicken, Jhinga Ka Nasha, Tandoori Soy Chaap, Gobi Manchurian, Chilli Paneer, Chicken Chilli, Chicken Manchurian, Hakka Noodle, Tadka Dal, Dal Makhani, Chana Masala, Allepey Veg Curry, Aloo Gobi, Saag Paneer, Malai Kofta, Mirch Baigan Salan, Mattar Paneer, Baingan Bharta, Aamchur Bhindi, Navaratna Korma, Paneer Tikka Masala, Chicken Tikka Masala, Chicken Chettinad, Chicken Madras, Kadai Chicken, Chicken Korma, Butter Chicken, Lamb Vindaloo, Lamb Saag, Lamb Madras, Lamb Pasanda, Lamb Roganjosh, Goat Curry, Shrimp Kabab Masala, Shrimp Madras, Shrimp Vindaloo, Allepey Fish Curry, Tandoori Salmon, Chicken Tandoori, Chicken Tikka, Paneer Tikka, Chicken Malai Kabab, Seekh Kabab, Tandoori Shrimp, Lamb Chops, Lemon Rice, Coconut Rice, Veg Biryani, Chicken Biryani, Lamb Biryani, Shrimp Biryani, Naan, Garlic Naan, Onion Kulcha, Roti, Lachcha Paratha, Pudina Paratha, Aloo Paratha, Peshawari Naan, Keema Naan, Chilli Garlic Naan, Rasmalai, Gulab Jamun, Gajar Halwa, Kheer, Kulfi, Raita, Mango Chutney, Mixed Pickle, Basmati Rice, Mango Lassi, Sweet Lassi, Salted Lassi, Ginger Ale, Perrier, Poland Spring Water
- `#contact` "Hours" — the weekly opening hours and the address
- `#gallery` "A Visual Feast" — photographs of the dishes and the room
- `#faq` "Frequently Asked" — an accordion covering: vegetarian, reservation, takeout or delivery, hours of operation
also: The dish rows repeat the same markup per dish, so a change to one row's structure has to be made to all 91 rows.
also: The FAQ answers name the Reserve a Table and Order Online buttons by their on-screen labels, so renaming either button leaves the FAQ telling the visitor to look for something that is no longer there.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `robots.txt` — crawler rules and the sitemap link — derived from the site by the deploy, not written by hand
- `sitemap.xml` — the list of page URLs — derived from the site by the deploy, not written by hand

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
