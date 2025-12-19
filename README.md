# Ex.06 Restaurant Website
## Date:19.12.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Spoon Bistro - Home</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="styles.css">
</head>

<body style="font-family: 'Roboto', sans-serif; background-color: #823c0a5a; margin:0;">

    <!-- Navbar -->
    <nav style="background-color: #4e2803cf; padding: 15px 0;">
        <ul style="display:flex; justify-content:center; list-style:none; margin:0; padding:0;">
            <li style="margin:0 20px;"><a href="index.html" style="color:#eae1cd; text-decoration:none;">Home</a></li>
            <li style="margin:0 20px;"><a href="menu.html" style="color:#f2deb5; text-decoration:none;">Our Menu</a></li>
            <li style="margin:0 20px;"><a href="special.html" style="color:#fff; text-decoration:none;">Specials</a></li>
            <li style="margin:0 20px;"><a href="team.html" style="color:#fff; text-decoration:none;">Our Team</a><li>
            <li style="margin:0 20px;"><a href="contacts.html" style="color:#f7dcb7; text-decoration:none;">Reservations</a></li>
            <li style="margin:0 20px;"><a href="login.html" style="color:#fae2b0; text-decoration:none;">Sign In</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="hero" style="background-color:#5c3408; color:#e6dde0; text-align:center; padding:100px 20px;">
        <div class="hero-content">
            <h1 style="font-family: 'Playfair Display', serif; font-size:60px; margin-bottom:20px;">Golden Spoon Bistro</h1>
            <p style="font-size:20px; margin-bottom:30px;">Where fine dining meets timeless taste</p>
            <a href="menu.html"
               style="padding:14px 35px; background-color:#d4af37; color:#000; text-decoration:none; border-radius:30px; font-weight:bold;">
               View Signature Dishes
            </a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" style="padding:80px 10%; background-color:#f5efe6; display:flex; flex-wrap:wrap; justify-content:space-around; gap:30px;">

        <!-- Farm to Table -->
        <div class="feature-card" style="background-color:#fff; border-radius:15px; overflow:hidden; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.1); text-align:center;">
            <img src="https://images.unsplash.com/photo-1506806732259-39c2d0268443?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=400" 
                 alt="Farm to Table" style="width:100%; height:200px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:24px; color:#6d4c41;">Farm to Table</h3>
                <p style="font-size:16px; color:#333; margin-top:10px;">Fresh, locally sourced ingredients crafted into dishes that nourish both body and soul.</p>
            </div>
        </div>

        <!-- Chef's Specials -->
        <div class="feature-card" style="background-color:#fff; border-radius:15px; overflow:hidden; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.1); text-align:center;">
            <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=400"
                 alt="Chef Specials" style="width:100%; height:200px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:24px; color:#6d4c41;">Chef’s Specials</h3>
                <p style="font-size:16px; color:#333; margin-top:10px;">Seasonal creations by our master chefs, blending classic flavors with modern twists.</p>
            </div>
        </div>

        <!-- Elegant Ambience -->
        <div class="feature-card" style="background-color:#fff; border-radius:15px; overflow:hidden; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.1); text-align:center;">
            <img src="https://images.unsplash.com/photo-1549924231-f129b911e442?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=400" 
                 alt="Elegant Ambience" style="width:100%; height:200px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:24px; color:#6d4c41;">Elegant Ambience</h3>
                <p style="font-size:16px; color:#333; margin-top:10px;">A luxurious and cozy dining atmosphere perfect for special evenings and celebrations.</p>
            </div>
        </div>

    </section>

    <!-- Footer -->
    <footer style="background-color: #3e2723; color: #a613cb; text-align:center; padding:20px;">
        <p>&copy; 2025 Golden Spoon Bistro. Crafted with passion.</p>
    </footer>

</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Spoon Bistro - Menu</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="styles.css">
</head>

<body style="font-family: 'Roboto', sans-serif; background-color: #f5efe6; margin:0;">

    <!-- Navbar -->
    <nav style="background-color: #3e2723; padding: 15px 0;">
        <ul style="display:flex; justify-content:center; list-style:none; margin:0; padding:0;">
            <li style="margin:0 20px;"><a href="index.html" style="color:#fff; text-decoration:none;">Home</a></li>
            <li style="margin:0 20px;"><a href="menu.html" style="color:#fff; text-decoration:none;">Our Menu</a></li>
            <li style="margin:0 20px;"><a href="special.html" style="color:#fff; text-decoration:none;">Specials</a></li>
            <li style="margin:0 20px;"><a href="team.html" style="color:#fff; text-decoration:none;">Our Team</a><li></li>
            <li style="margin:0 20px;"><a href="contacts.html" style="color:#fff; text-decoration:none;">Reservations</a></li>
            <li style="margin:0 20px;"><a href="login.html" style="color:#fff; text-decoration:none;">Sign In</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="hero" style="background-color:#6d4c41; color:#fff; text-align:center; padding:80px 20px;">
        <div class="hero-content">
            <h1 style="font-family: 'Playfair Display', serif; font-size:50px; margin-bottom:20px;">Our Menu</h1>
            <p style="font-size:18px;">Explore our selection of gourmet dishes and chef specials</p>
        </div>
    </section>

    <!-- Special Dishes Section -->
    <section class="special-dishes" style="padding:60px 10%; background-color:#fbeedb; text-align:center;">
        <h2 style="font-family:'Playfair Display', serif; font-size:36px; color:#6d4c41; margin-bottom:40px;">Chef's Special Dishes</h2>
        <div style="display:flex; flex-wrap:wrap; justify-content:center; gap:30px;">
            
            <!-- Truffle Risotto -->
            <div style="background:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden;">
                <img src="1.png" 
                     alt="Truffle Risotto" style="width:100%; height:180px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41; font-size:22px;">Truffle Mushroom Risotto</h3>
                    <p style="color:#333; font-size:15px; margin:10px 0;">Creamy Arborio rice with truffle oil, wild mushrooms, and Parmesan</p>
                    <p style="font-weight:bold; color:#d4af37;">₹2325</p>
                </div>
            </div>

            <!-- Ribeye Steak -->
            <div style="background:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden;">
                <img src="2.png" 
                     alt="Ribeye Steak" style="width:100%; height:180px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41; font-size:22px;">Grilled Ribeye Steak</h3>
                    <p style="color:#333; font-size:15px; margin:10px 0;">Juicy ribeye with garlic butter, served with roasted vegetables</p>
                    <p style="font-weight:bold; color:#d4af37;">₹2905</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu Categories -->
    <section class="menu" style="padding:60px 10%; display:flex; flex-wrap:wrap; gap:30px; justify-content:center;">

        <!-- Starters -->
        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="3.png" 
                 alt="Fresh Garden Salad" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Fresh Garden Salad</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">Mixed greens, cherry tomatoes, cucumber, and house vinaigrette</p>
                <p style="font-weight:bold; color:#d4af37;">₹705</p>
            </div>
        </div>

        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="4.png" 
                 alt="Bruschetta" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Classic Bruschetta</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">Toasted baguette topped with tomatoes, basil, and olive oil</p>
                <p style="font-weight:bold; color:#d4af37;">₹750</p>
            </div>
        </div>

        <!-- Main Courses -->
        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="6.png" 
                 alt="Grilled Salmon" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Grilled Salmon</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">Served with roasted vegetables and lemon butter sauce</p>
                <p style="font-weight:bold; color:#d4af37;">₹1825</p>
            </div>
        </div>

        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="5.png" 
                 alt="Herb Roasted Chicken" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Herb Roasted Chicken</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">Tender chicken roasted with rosemary, thyme, and garlic</p>
                <p style="font-weight:bold; color:#d4af37;">₹1660</p>
            </div>
        </div>

        <!-- Desserts -->
        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=400" 
                 alt="Chocolate Lava Cake" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Chocolate Lava Cake</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">Rich molten chocolate cake served with vanilla ice cream</p>
                <p style="font-weight:bold; color:#d4af37;">₹830</p>
            </div>
        </div>

        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="https://images.unsplash.com/photo-1589302168068-964664d93dc0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=400" 
                 alt="New York Cheesecake" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">New York Cheesecake</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">Classic cheesecake with a buttery graham cracker crust</p>
                <p style="font-weight:bold; color:#d4af37;">₹790</p>
            </div>
        </div>

        <!-- Drinks -->
        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="i.png" 
                 alt="Red Wine" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Red Wine Selection</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">A curated list of premium red wines to complement your meal</p>
                <p style="font-weight:bold; color:#d4af37;">₹995</p>
            </div>
        </div>

        <div class="menu-card" style="background-color:#fff; border-radius:15px; width:280px; box-shadow:0 5px 15px rgba(0,0,0,0.1); overflow:hidden; text-align:center;">
            <img src="https://images.unsplash.com/photo-1586190848861-99aa4a171e90?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=400" 
                 alt="Cocktail" style="width:100%; height:180px; object-fit:cover;">
            <div style="padding:20px;">
                <h3 style="font-family:'Playfair Display', serif; font-size:22px; color:#6d4c41;">Signature Cocktail</h3>
                <p style="font-size:15px; color:#333; margin:10px 0;">A refreshing mix of citrus, herbs, and premium spirits</p>
                <p style="font-weight:bold; color:#d4af37;">₹1160</p>
            </div>
        </div>

    </section>

    <!-- Footer -->
    <footer style="background-color: #3e2723; color: #fff; text-align:center; padding:20px;">
        <p>&copy; 2025 Golden Spoon Bistro. Crafted with passion.</p>
    </footer>

</body>
</html>

special.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Spoon Bistro - Chef's Specials</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
</head>

<body style="font-family: 'Roboto', sans-serif; background-color: #f5efe6; margin:0;">

    <!-- Navbar -->
    <nav style="background-color: #3e2723; padding: 15px 0;">
        <ul style="display:flex; justify-content:center; list-style:none; margin:0; padding:0;">
            <li style="margin:0 20px;"><a href="index.html" style="color:#fff; text-decoration:none;">Home</a></li>
                       <li style="margin:0 20px;"><a href="menu.html" style="color:#fff; text-decoration:none;">Our Menu</a></li>
            <li style="margin:0 20px;"><a href="specials.html" style="color:#fff; text-decoration:none;">Chef's Specials</a></li>
                        <li style="margin:0 20px;"><a href="team.html" style="color:#fff; text-decoration:none;">Our Team</a><li></li>
            <li style="margin:0 20px;"><a href="contacts.html" style="color:#fff; text-decoration:none;">Reservations</a></li>
            <li style="margin:0 20px;"><a href="login.html" style="color:#fff; text-decoration:none;">Sign In</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section style="background-color:#6d4c41; color:#fff; text-align:center; padding:80px 20px;">
        <h1 style="font-family:'Playfair Display', serif; font-size:50px;">Chef's Special Dishes</h1>
        <p style="font-size:18px;">Signature creations curated by our master chefs</p>
    </section>

    <!-- Special Dishes -->
    <section style="padding:60px 10%; background-color:#fbeedb;">
        <div style="display:flex; flex-wrap:wrap; justify-content:center; gap:30px;">

            <!-- Wagyu Beef Tenderloin -->
            <div style="background:#fff; border-radius:15px; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.15); overflow:hidden; text-align:center;">
                <img src="wagyu.png" alt="Wagyu Beef Tenderloin" style="width:100%; height:200px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Japanese Wagyu Tenderloin</h3>
                    <p>Ultra-premium wagyu beef seared to perfection with truffle jus</p>
                    <p style="font-weight:bold; color:#d4af37;">₹6,800</p>
                </div>
            </div>

            <!-- Lobster Thermidor -->
            <div style="background:#fff; border-radius:15px; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.15); overflow:hidden; text-align:center;">
                <img src="lobster.png" alt="Lobster Thermidor" style="width:100%; height:200px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Lobster Thermidor</h3>
                    <p>Atlantic lobster baked with creamy mustard sauce and Gruyère</p>
                    <p style="font-weight:bold; color:#d4af37;">₹5,200</p>
                </div>
            </div>

            <!-- Saffron Lamb Rack -->
            <div style="background:#fff; border-radius:15px; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.15); overflow:hidden; text-align:center;">
                <img src="lamb.png" alt="Saffron Lamb Rack" style="width:100%; height:200px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Saffron Crusted Lamb Rack</h3>
                    <p>New Zealand lamb infused with Kashmiri saffron and herbs</p>
                    <p style="font-weight:bold; color:#d4af37;">₹4,600</p>
                </div>
            </div>

            <!-- Black Cod Miso -->
            <div style="background:#fff; border-radius:15px; width:300px; box-shadow:0 5px 15px rgba(0,0,0,0.15); overflow:hidden; text-align:center;">
                <img src="cod.png" alt="Black Cod Miso" style="width:100%; height:200px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Miso Glazed Black Cod</h3>
                    <p>Silky black cod marinated in white miso with sesame glaze</p>
                    <p style="font-weight:bold; color:#d4af37;">₹4,900</p>
                </div>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer style="background-color:#3e2723; color:#fff; text-align:center; padding:20px;">
        <p>&copy; 2025 Golden Spoon Bistro. Chef's Signature Specials.</p>
    </footer>

</body>
</html>
```
team.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Spoon Bistro - Our Team</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
</head>

<body style="font-family:'Roboto', sans-serif; background-color:#f5efe6; margin:0;">

    <!-- Navbar -->
    <nav style="background-color:#3e2723; padding:15px 0;">
        <ul style="display:flex; justify-content:center; list-style:none; margin:0; padding:0;">
            <li style="margin:0 20px;"><a href="index.html" style="color:#fff; text-decoration:none;">Home</a></li>
            <li style="margin:0 20px;"><a href="menu.html" style="color:#fff; text-decoration:none;">Our Menu</a></li>
            <li style="margin:0 20px;"><a href="specials.html" style="color:#fff; text-decoration:none;">Chef's Specials</a></li>
            <li style="margin:0 20px;"><a href="team.html" style="color:#fff; text-decoration:none;">Our Team</a></li>
            <li style="margin:0 20px;"><a href="contacts.html" style="color:#f7dcb7; text-decoration:none;">Reservations</a></li>
            <li style="margin:0 20px;"><a href="login.html" style="color:#fae2b0; text-decoration:none;">Sign In</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section style="background-color:#6d4c41; color:#fff; text-align:center; padding:80px 20px;">
        <h1 style="font-family:'Playfair Display', serif; font-size:50px;">Meet Our People</h1>
        <p style="font-size:18px;">The heart and soul behind Golden Spoon Bistro</p>
    </section>

    <!-- Team Section -->
    <section style="padding:60px 10%; background-color:#fbeedb;">
        <h2 style="font-family:'Playfair Display', serif; text-align:center; font-size:36px; color:#6d4c41; margin-bottom:40px;">Our Culinary & Service Experts</h2>

        <div style="display:flex; flex-wrap:wrap; justify-content:center; gap:30px;">

            <!-- Executive Chef -->
            <div style="background:#fff; border-radius:15px; width:260px; box-shadow:0 5px 15px rgba(0,0,0,0.15); text-align:center; overflow:hidden;">
                <img src="chef.png" alt="Executive Chef" style="width:100%; height:270px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Chef Arjun Malhotra</h3>
                    <p style="font-weight:bold; color:#d4af37;">Executive Chef</p>
                    <p>Michelin-trained chef specializing in modern European cuisine</p>
                </div>
            </div>

            <!-- Sous Chef -->
            <div style="background:#fff; border-radius:15px; width:260px; box-shadow:0 5px 15px rgba(0,0,0,0.15); text-align:center; overflow:hidden;">
                <img src="souschef.png" alt="Sous Chef" style="width:100%; height:220px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Chef Riya Sen</h3>
                    <p style="font-weight:bold; color:#d4af37;">Sous Chef</p>
                    <p>Expert in gourmet plating and seasonal tasting menus</p>
                </div>
            </div>

            <!-- Restaurant Manager -->
            <div style="background:#fff; border-radius:15px; width:260px; box-shadow:0 5px 15px rgba(0,0,0,0.15); text-align:center; overflow:hidden;">
                <img src="manager.png" alt="Restaurant Manager" style="width:100%; height:220px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Neha Kapoor</h3>
                    <p style="font-weight:bold; color:#d4af37;">Restaurant Manager</p>
                    <p>Ensuring flawless service and an unforgettable dining experience</p>
                </div>
            </div>

            <!-- Sommelier -->
            <div style="background:#fff; border-radius:15px; width:260px; box-shadow:0 5px 15px rgba(0,0,0,0.15); text-align:center; overflow:hidden;">
                <img src="sommelier.png" alt="Sommelier" style="width:100%; height:220px; object-fit:cover;">
                <div style="padding:20px;">
                    <h3 style="font-family:'Playfair Display', serif; color:#6d4c41;">Daniel Cruz</h3>
                    <p style="font-weight:bold; color:#d4af37;">Head Sommelier</p>
                    <p>Curator of premium wines and bespoke pairing experiences</p>
                </div>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer style="background-color:#3e2723; color:#fff; text-align:center; padding:20px;">
        <p>&copy; 2025 Golden Spoon Bistro. Powered by Passion & People.</p>
    </footer>

</body>
</html>
```
contacts.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Spoon Bistro - Contact Us</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f5efe6;
        }

        nav {
            background-color: #3e2723;
            padding: 15px 0;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .contact-hero {
            background-color: #6d4c41;
            color: #fff;
            text-align: center;
            padding: 80px 20px;
        }

        .contact-hero h1 {
            font-family: 'Playfair Display', serif;
            font-size: 48px;
            margin-bottom: 10px;
        }

        .contact-hero p {
            font-size: 18px;
        }

        .contact-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 60px 10%;
            gap: 40px;
        }

        .contact-info, .contact-form {
            background-color: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            flex: 1;
            min-width: 300px;
        }

        .contact-info h2,
        .contact-form h2 {
            font-family: 'Playfair Display', serif;
            color: #6d4c41;
            margin-bottom: 20px;
        }

        .contact-info p {
            font-size: 16px;
            margin-bottom: 10px;
            color: #333;
        }

        .contact-info a {
            color: #6d4c41;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px 15px;
            margin: 10px 0;
            border-radius: 8px;
            border: 1px solid #ccc;
            font-size: 16px;
        }

        .contact-form button {
            background-color: #6d4c41;
            color: #fff;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 10px;
            width: 100%;
        }

        .contact-form button:hover {
            background-color: #5a3e32;
        }

        footer {
            background-color: #3e2723;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        @media(max-width: 900px) {
            .contact-section {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Our Menu</a></li>
            <li><a href="contacts.html">Reservations</a></li>
            <li><a href="login.html">Sign In</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="contact-hero">
        <h1>Contact Us</h1>
        <p>We’d love to hear from you! Get in touch for reservations, feedback, or inquiries.</p>
    </section>

    <!-- Contact Section -->
    <section class="contact-section">

        <!-- Restaurant Info -->
        <div class="contact-info">
            <h2>Golden Spoon Bistro</h2>
            <p><strong>Address:</strong> 123 Culinary Lane, Foodie City, FC 45678</p>
            <p><strong>Phone:</strong> <a href="tel:+1234567890">+1 234 567 890</a></p>
            <p><strong>Email:</strong> <a href="mailto:info@goldenspoonbistro.com">info@goldenspoonbistro.com</a></p>
            <p><strong>Hours:</strong> Mon-Sun: 10:00 AM - 10:00 PM</p>
            <!-- Optional Map -->
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.086591722257!2d-122.41941508468102!3d37.77492977975916!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085808d6b5e5fdf%3A0x3d6c1f8a7b3b91f7!2sGolden%20Gate!5e0!3m2!1sen!2sus!4v1616161616161!5m2!1sen!2sus" 
                width="100%" height="200" style="border:0; border-radius:10px; margin-top:20px;" allowfullscreen="" loading="lazy"></iframe>
        </div>

        <!-- Contact Form -->
        <div class="contact-form">
            <h2>Send Us a Message</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="6" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>

    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Golden Spoon Bistro. Crafted with passion.</p>
    </footer>

</body>
</html>

login.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Spoon Bistro - Login</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f5efe6;
        }

        nav {
            background-color: #3e2723;
            padding: 15px 0;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .login-container {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 80vh;
            padding: 20px;
        }

        .login-form {
            background-color: #fff;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 400px;
            text-align: center;
        }

        .login-form h2 {
            font-family: 'Playfair Display', serif;
            color: #6d4c41;
            margin-bottom: 30px;
            font-size: 28px;
        }

        .login-form input[type="text"],
        .login-form input[type="password"] {
            width: 100%;
            padding: 12px 15px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 16px;
        }

        .login-form button {
            background-color: #6d4c41;
            color: #fff;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 20px;
            width: 100%;
        }

        .login-form button:hover {
            background-color: #5a3e32;
        }

        .login-form .forgot-password {
            margin-top: 15px;
            font-size: 14px;
            color: #6d4c41;
            text-decoration: none;
        }

        .login-form .forgot-password:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #3e2723;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Our Menu</a></li>
            <li><a href="contacts.html">Reservations</a></li>
            <li><a href="login.html">Sign In</a></li>
        </ul>
    </nav>

    <!-- Login Form -->
    <div class="login-container">
        <form class="login-form" action="#" method="post">
            <h2>Member Login</h2>
            <input type="text" name="username" placeholder="Username" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Login</button>
            <a href="#" class="forgot-password">Forgot Password?</a>
        </form>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Golden Spoon Bistro. Crafted with passion.</p>
    </footer>

</body>
</html>

style.css
/* ==========================
   GLOBAL STYLES
========================== */
body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
    background-color: #f5efe6;
    color: #333;
}

a {
    text-decoration: none;
    color: inherit;
}

h1, h2, h3, h4 {
    font-family: 'Playfair Display', serif;
    color: #6d4c41;
    margin: 0 0 15px 0;
}

/* ==========================
   NAVBAR
========================== */
nav {
    background-color: #3e2723;
    padding: 15px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    font-weight: 500;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #d4af37;
}

/* ==========================
   HERO SECTION
========================== */
.hero, .contact-hero {
    text-align: center;
    padding: 80px 20px;
    color: #fff;
    background-color: #6d4c41;
}

.hero h1, .contact-hero h1 {
    font-size: 48px;
    margin-bottom: 15px;
}

.hero p, .contact-hero p {
    font-size: 18px;
}

.cta-button {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background-color: #d4af37;
    color: #3e2723;
    font-weight: bold;
    border-radius: 8px;
    transition: background-color 0.3s;
}

.cta-button:hover {
    background-color: #b38e2b;
}

/* ==========================
   FEATURE CARDS
========================== */
.features {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 30px;
    padding: 60px 10%;
    background-color: #fbeedb;
}

.feature-card {
    background-color: #fff;
    border-radius: 15px;
    padding: 30px 20px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    flex: 1;
    min-width: 250px;
    text-align: center;
}

.feature-icon {
    font-size: 40px;
    margin-bottom: 15px;
}

/* ==========================
   MENU CARDS
========================== */
.menu, .special-dishes {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    padding: 60px 10%;
}

.menu-card {
    background-color: #fff;
    border-radius: 15px;
    width: 280px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    overflow: hidden;
    text-align: center;
}

.menu-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menu-card h3 {
    font-size: 22px;
    margin: 10px 0;
}

.menu-card p {
    font-size: 15px;
    margin: 10px 0;
}

.menu-card p.price {
    font-weight: bold;
    color: #d4af37;
}

/* ==========================
   LOGIN & CONTACT FORMS
========================== */
.login-container, .contact-section {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 40px;
    padding: 60px 10%;
    flex-wrap: wrap;
}

.login-form, .contact-form, .contact-info {
    background-color: #fff;
    padding: 30px 40px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    flex: 1;
    min-width: 300px;
}

.login-form h2, .contact-form h2, .contact-info h2 {
    font-family: 'Playfair Display', serif;
    color: #6d4c41;
    margin-bottom: 20px;
    text-align: center;
}

.login-form input, .login-form button,
.contact-form input, .contact-form textarea, .contact-form button {
    width: 100%;
    padding: 12px 15px;
    margin: 10px 0;
    border-radius: 8px;
    border: 1px solid #ccc;
    font-size: 16px;
}

.login-form button, .contact-form button {
    background-color: #6d4c41;
    color: #fff;
    border: none;
    cursor: pointer;
    margin-top: 10px;
    font-weight: bold;
    transition: background-color 0.3s;
}

.login-form button:hover, .contact-form button:hover {
    background-color: #5a3e32;
}

.login-form .forgot-password {
    margin-top: 15px;
    font-size: 14px;
    color: #6d4c41;
    text-decoration: none;
    display: inline-block;
}

.login-form .forgot-password:hover {
    text-decoration: underline;
}

.contact-info p, .contact-info a {
    font-size: 16px;
    margin-bottom: 10px;
    color: #333;
}

.contact-info a {
    color: #6d4c41;
}

.contact-info a:hover {
    text-decoration: underline;
}

/* ==========================
   FOOTER
========================== */
footer {
    background-color: #3e2723;
    color: #fff;
    text-align: center;
    padding: 20px;
}

/* ==========================
   RESPONSIVE
========================== */
@media(max-width: 900px) {
    .features, .menu, .special-dishes, .login-container, .contact-section {
        flex-direction: column;
        align-items: center;
    }
}


## OUTPUT:
![alt text](<Screenshot 2025-12-18 214251-1.png>)
 ![alt text](<Screenshot 2025-12-18 214339-1.png>) 
 ![alt text](<Screenshot 2025-12-18 214354-1.png>) 
 ![alt text](<Screenshot 2025-12-18 214408-1.png>) 
 ![alt text](<Screenshot 2025-12-18 214424-1.png>)
  ![alt text](<Screenshot 2025-12-18 214433-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
