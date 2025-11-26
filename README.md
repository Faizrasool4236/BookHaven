<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookHaven</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            background:#f5f5f5;
        }

        /* NAVBAR */
        nav{
            width:100%;
            background:#fff;
            padding:15px 50px;
            display:flex;
            align-items:center;
            justify-content:space-between;
            box-shadow:0 2px 5px rgba(0,0,0,0.1);
            position:sticky;
            top:0;
            z-index:10;
        }

        .logo{
            font-size:24px;
            font-weight:bold;
            display:flex;
            align-items:center;
            gap:8px;
        }

        .nav-links{
            display:flex;
            gap:30px;
        }

        .nav-links a{
            text-decoration:none;
            color:#333;
            font-size:16px;
        }

        .nav-right{
            display:flex;
            align-items:center;
            gap:20px;
        }

        .login-btn{
            padding:8px 18px;
            background:#111;
            color:#fff;
            border-radius:6px;
            text-decoration:none;
        }

        /* HERO SECTION */
        .hero{
            width:100%;
            display:flex;
            padding:80px 50px;
            background:linear-gradient(to right,#0d78d4,#2c5fd4);
            color:#fff;
        }

        .hero-left{
            width:50%;
            padding-right:40px;
        }

        .hero-left h1{
            font-size:48px;
            margin-bottom:20px;
        }

        .hero-left p{
            font-size:18px;
            margin-bottom:25px;
            opacity:0.9;
        }

        .hero-btn{
            padding:12px 25px;
            background:#fff;
            border-radius:8px;
            color:#333;
            font-size:16px;
            text-decoration:none;
            font-weight:bold;
        }

        .hero-right{
            width:50%;
        }

        .hero-right img{
            width:100%;
            border-radius:12px;
        }

        /* FEATURES SECTION */
        .features {
            padding: 60px 50px;
            background: #fff;
            text-align: center;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 40px;
            margin-top: 40px;
        }

        .feature-card {
            padding: 30px 20px;
            border-radius: 12px;
            background: #f9f9f9;
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .feature-icon {
            font-size: 40px;
            margin-bottom: 15px;
        }

        .feature-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
            color: #0d1b4b;
        }

        .feature-desc {
            color: #666;
            line-height: 1.5;
        }

        /* BOOK SECTION */
        .section{
            padding:40px 50px;
        }

        .section-title{
            font-size:22px;
            margin-bottom:25px;
        }

        .books{
            display:grid;
            grid-template-columns:repeat(2,1fr);
            gap:30px;
        }

        .book-card{
            background:#fff;
            border-radius:12px;
            padding:15px;
            box-shadow:0 3px 8px rgba(0,0,0,0.1);
        }

        .book-card img{
            width:100%;
            height:250px;
            object-fit:cover;
            border-radius:12px;
            margin-bottom:12px;
        }

        .book-title{
            font-size:20px;
            font-weight:bold;
        }

        .book-author{
            font-size:14px;
            color:#666;
        }

        .price{
            margin-top:8px;
            font-size:16px;
        }

        .add-btn{
            margin-top:12px;
            padding:10px;
            width:100%;
            background:#0d1b4b;
            color:#fff;
            border:none;
            border-radius:8px;
            cursor:pointer;
            font-size:16px;
        }

        /* READING JOURNEY SECTION */
        .reading-journey {
            padding: 80px 50px;
            background: linear-gradient(to right, #0d78d4, #2c5fd4);
            color: #fff;
            text-align: center;
            margin-top: 40px;
        }

        .journey-content {
            max-width: 600px;
            margin: 0 auto;
        }

        .journey-content h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .journey-content p {
            font-size: 18px;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .journey-btn {
            padding: 12px 25px;
            background: #fff;
            border-radius: 8px;
            color: #333;
            font-size: 16px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
        }
    </style>

</head>
<body>

    <!-- NAVBAR -->
    <nav>
        <div class="logo">📘 BookHaven</div>

        <div class="nav-links">
            <a style="color:#2c5fd4;" href="#">Home</a>
            
            <a href="books.html">Books</a>
        </div>

        <div class="nav-right">
            🛒
            <a href="login.html" class="login-btn">Login</a>
            
        </div>
    </nav>

    <!-- HERO SECTION -->
    <div class="hero">
        <div class="hero-left">
            <h1>Discover Your<br>Next Great<br>Read</h1>
            <p>Explore thousands of books across all genres. Fast delivery, secure payment, and great prices.</p>
            <a href="#" class="hero-btn">Browse Books →</a>
        </div>

        <div class="hero-right">
            <img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f" alt="">
        </div>
    </div>

    <!-- FEATURES SECTION -->
    <div class="features">
        <h2 class="section-title">Why Choose BookHaven?</h2>
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">🚚</div>
                <h3 class="feature-title">Fast Delivery</h3>
                <p class="feature-desc">Quick and reliable shipping to your doorstep</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">💰</div>
                <h3 class="feature-title">Best Prices</h3>
                <p class="feature-desc">Competitive prices on all our books</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">📚</div>
                <h3 class="feature-title">Wide Selection</h3>
                <p class="feature-desc">Thousands of books across all genres</p>
            </div>
        </div>
    </div>

    <!-- FEATURED BOOKS -->
    <div class="section">
        <h2 class="section-title">Featured Books</h2>

        <div class="books">

            <!-- BOOK 1 -->
            <div class="book-card">
                <img src="https://via.placeholder.com/400x250" alt="">
                <p class="book-title">The Midnight Library</p>
                <p class="book-author">Matt Haig</p>
                ⭐ 4.5
                <p class="price">$16.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 2 -->
            <div class="book-card">
                <img src="https://tse3.mm.bing.net/th/id/OIP.RgKVDGE_x4uyE1JjjKuWWwHaHa?pid=Api&P=0&h=220" alt="">
                <p class="book-title">Atomic Habits</p>
                <p class="book-author">James Clear</p>
                ⭐ 4.8
                <p class="price">$14.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

        </div>

        <br><br>

        <div class="books">

            <!-- BOOK 3 -->
            <div class="book-card">
                <img src="https://tse2.mm.bing.net/th/id/OIP.Ei-67fm6RGwk05DkdAmeHgHaEo?pid=Api&P=0&h=220" alt="">
                <p class="book-title">The Silent Patient</p>
                <p class="book-author">Alex Michaelides</p>
                ⭐ 4.3
                <p class="price">$15.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 4 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794" alt="">
                <p class="book-title">Sapiens</p>
                <p class="book-author">Yuval Noah Harari</p>
                ⭐ 4.7
                <p class="price">$12.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 5 -->
            <div class="book-card">
                <img src="https://tse1.mm.bing.net/th/id/OIP.9j0kj9e2UhR1jB6q-9MviAHaEt?pid=Api&P=0&h=220" alt="">
                <p class="book-title">Project Hail Mary</p>
                <p class="book-author">Andy Weir</p>
                ⭐ 4.7
                <p class="price">$18.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- BOOK 6 -->
            <div class="book-card">
                <img src="https://tse3.mm.bing.net/th/id/OIP.s53-jcSF3qWi0WlNcU-9qgHaGK?pid=Api&P=0&h=220" alt="">
                <p class="book-title">The Psychology of Money</p>
                <p class="book-author">Morgan House</p>
                ⭐ 4.7
                <p class="price">$30</p>
                <button class="add-btn">Add to Cart</button>
            </div>

        </div>

    </div>

    <!-- READING JOURNEY SECTION -->
    <div class="reading-journey">
        <div class="journey-content">
            <h2>Start Your Reading Journey Today</h2>
            <p>Join thousands of readers who trust BookHaven for their reading needs</p>
            <a href="#" class="journey-btn">Explore Our Collection</a>
        </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Books - BookHaven</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f5f5f5;
        }

        /* NAVBAR */
        nav {
            width: 100%;
            background: #fff;
            padding: 15px 50px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 10;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .nav-links {
            display: flex;
            gap: 30px;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-size: 16px;
        }

        .nav-right {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .login-btn {
            padding: 8px 18px;
            background: #111;
            color: #fff;
            border-radius: 6px;
            text-decoration: none;
        }

        /* BROWSE BOOKS SECTION */
        .browse-section {
            padding: 60px 50px;
            background: #fff;
        }

        .browse-header {
            margin-bottom: 30px;
        }

        .browse-header h2 {
            font-size: 32px;
            margin-bottom: 10px;
            color: #0d1b4b;
        }

        .browse-header p {
            color: #666;
            font-size: 16px;
        }

        .search-container {
            margin-bottom: 30px;
            position: relative;
        }

        .search-input {
            width: 100%;
            padding: 15px 20px;
            border-radius: 8px;
            border: 1px solid #ddd;
            font-size: 16px;
        }

        .search-input:focus {
            outline: none;
            border-color: #2c5fd4;
        }

        .categories {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 30px;
        }

        .category-btn {
            padding: 8px 16px;
            background: #f0f0f0;
            border: none;
            border-radius: 20px;
            font-size: 14px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .category-btn.active {
            background: #2c5fd4;
            color: white;
        }

        .category-btn:hover {
            background: #ddd;
        }

        .category-btn.active:hover {
            background: #1a4bb8;
        }

        .results-count {
            margin-bottom: 20px;
            color: #666;
        }

        /* BOOKS GRID */
        .books {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 25px;
        }

        .book-card {
            background: #fff;
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 3px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .book-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.1);
        }

        .book-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 12px;
        }

        .book-title {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .book-author {
            font-size: 14px;
            color: #666;
            margin-bottom: 8px;
        }

        .rating {
            display: flex;
            align-items: center;
            gap: 5px;
            margin-bottom: 8px;
            color: #666;
        }

        .price {
            font-size: 16px;
            font-weight: bold;
            color: #0d1b4b;
        }

        .add-btn {
            margin-top: 12px;
            padding: 10px;
            width: 100%;
            background: #0d1b4b;
            color: #fff;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 14px;
            transition: background 0.3s ease;
        }

        .add-btn:hover {
            background: #1a4bb8;
        }

        /* Responsive adjustments */
        @media (max-width: 1024px) {
            .books {
                grid-template-columns: repeat(3, 1fr);
            }
        }

        @media (max-width: 768px) {
            .books {
                grid-template-columns: repeat(2, 1fr);
            }
            
            nav {
                padding: 15px 20px;
            }
            
            .browse-section {
                padding: 40px 20px;
            }
        }

        @media (max-width: 480px) {
            .books {
                grid-template-columns: 1fr;
            }
            
            .nav-links {
                gap: 15px;
            }
        }
    </style>
</head>
<body>

    <!-- NAVBAR -->
    <nav>
        <div class="logo">📘 BookHaven</div>

        <div class="nav-links">
            <a href="index.html">Home</a>
            <a style="color:#2c5fd4;" href="books.html">Books</a>
        </div>

        <div class="nav-right">
            🛒
            <a href="login.html" class="login-btn">Login</a>
        </div>
    </nav>

    <!-- BROWSE BOOKS SECTION -->
    <div class="browse-section">
        <div class="browse-header">
            <h2>Browse Books</h2>
            <p>Discover your next favorite book from our collection</p>
        </div>

        <div class="search-container">
            <input type="text" class="search-input" placeholder="Search by title or author...">
        </div>

        <div class="categories">
            <button class="category-btn active">All</button>
            <button class="category-btn">Fiction</button>
            <button class="category-btn">Self-Help</button>
            <button class="category-btn">Mystery</button>
            <button class="category-btn">History</button>
            <button class="category-btn">Biography</button>
            <button class="category-btn">Finance</button>
            <button class="category-btn">Science Fiction</button>
            <button class="category-btn">Historical Fiction</button>
            <button class="category-btn">Psychology</button>
        </div>

        <div class="results-count">Showing 12 books</div>

        <div class="books">
            <!-- Book 1 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f" alt="Book cover">
                <p class="book-title">The Psychology of Money</p>
                <p class="book-author">Morgan Housel</p>
                <div class="rating">⭐ 4.7</div>
                <p class="price">$16.50</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 2 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1589998059171-788d7a431ad4" alt="Book cover">
                <p class="book-title">Project Hail Mary</p>
                <p class="book-author">Andy Weir</p>
                <div class="rating">⭐ 4.8</div>
                <p class="price">$19.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 3 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794" alt="Book cover">
                <p class="book-title">Educated</p>
                <p class="book-author">Tara Westover</p>
                <div class="rating">⭐ 4.6</div>
                <p class="price">$17.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 4 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba" alt="Book cover">
                <p class="book-title">The Silent Patient</p>
                <p class="book-author">Alex Michaelides</p>
                <div class="rating">⭐ 4.3</div>
                <p class="price">$15.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 5 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1532012197267-da84d127e765" alt="Book cover">
                <p class="book-title">Atomic Habits</p>
                <p class="book-author">James Clear</p>
                <div class="rating">⭐ 4.8</div>
                <p class="price">$14.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 6 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1531346680769-a1d79b57de2e" alt="Book cover">
                <p class="book-title">The Midnight Library</p>
                <p class="book-author">Matt Haig</p>
                <div class="rating">⭐ 4.5</div>
                <p class="price">$16.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 7 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1621351183012-e2f9972dd9bf" alt="Book cover">
                <p class="book-title">Sapiens</p>
                <p class="book-author">Yuval Noah Harari</p>
                <div class="rating">⭐ 4.7</div>
                <p class="price">$18.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 8 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1589829085413-56de8ae18c73" alt="Book cover">
                <p class="book-title">The Obstacle is the Way</p>
                <p class="book-author">Ryan Holiday</p>
                <div class="rating">⭐ 4.6</div>
                <p class="price">$15.50</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 9 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1531901599638-a89bb60971a3" alt="Book cover">
                <p class="book-title">Zero to One</p>
                <p class="book-author">Peter Thiel</p>
                <div class="rating">⭐ 4.5</div>
                <p class="price">$20.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 10 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1530825894095-9c184b068fcb" alt="Book cover">
                <p class="book-title">The Startup Standard</p>
                <p class="book-author">Various Authors</p>
                <div class="rating">⭐ 4.4</div>
                <p class="price">$22.50</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 11 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1516979187457-637abb4f9353" alt="Book cover">
                <p class="book-title">The Corporate Startup</p>
                <p class="book-author">Tendayi Viki</p>
                <div class="rating">⭐ 4.3</div>
                <p class="price">$19.50</p>
                <button class="add-btn">Add to Cart</button>
            </div>

            <!-- Book 12 -->
            <div class="book-card">
                <img src="https://images.unsplash.com/photo-1554757380-2fb69b9d5e95" alt="Book cover">
                <p class="book-title">Noble Proposition Design</p>
                <p class="book-author">Alan Klement</p>
                <div class="rating">⭐ 4.2</div>
                <p class="price">$17.99</p>
                <button class="add-btn">Add to Cart</button>
            </div>
        </div>
    </div>

    <script>
        // Simple category filter functionality
        document.addEventListener('DOMContentLoaded', function() {
            const categoryButtons = document.querySelectorAll('.category-btn');
            
            categoryButtons.forEach(button => {
                button.addEventListener('click', function() {
                    // Remove active class from all buttons
                    categoryButtons.forEach(btn => btn.classList.remove('active'));
                    
                    // Add active class to clicked button
                    this.classList.add('active');
                    
                    // Alert for demo
                    if (this.textContent !== 'All') {
                        alert(`Filtering by ${this.textContent} category`);
                    }
                });
            });
            
            // Simple search functionality
            const searchInput = document.querySelector('.search-input');
            searchInput.addEventListener('keyup', function(e) {
                if (e.key === 'Enter') {
                    alert(`Searching for: ${this.value}`);
                }
            });
            
            // Add to cart functionality
            const addButtons = document.querySelectorAll('.add-btn');
            addButtons.forEach(button => {
                button.addEventListener('click', function() {
                    const bookTitle = this.parentElement.querySelector('.book-title').textContent;
                    alert(`Added "${bookTitle}" to cart`);
                });
            });
        });
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - BookHaven</title>
    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            display:flex;
            justify-content:center;
            align-items:center;
            height:100vh;
            background:linear-gradient(to right, #0d78d4, #2c5fd4);
        }

        .login-container{
            background:#fff;
            padding:40px;
            border-radius:12px;
            width:400px;
            box-shadow:0 5px 15px rgba(0,0,0,0.2);
            text-align:center;
        }

        .login-container h1{
            font-size:32px;
            margin-bottom:10px;
            color:#0d1b4b;
        }

        .login-container p{
            margin-bottom:30px;
            color:#555;
        }

        .tabs{
            display:flex;
            justify-content:space-between;
            margin-bottom:20px;
        }

        .tabs div{
            width:48%;
            padding:10px 0;
            cursor:pointer;
            border-bottom:2px solid transparent;
            font-weight:bold;
            color:#555;
        }

        .tabs .active{
            border-bottom:2px solid #0d1b4b;
            color:#0d1b4b;
        }

        form{
            display:flex;
            flex-direction:column;
            gap:15px;
        }

        input{
            padding:12px;
            border-radius:6px;
            border:1px solid #ccc;
            font-size:16px;
        }

        button{
            padding:12px;
            border:none;
            border-radius:6px;
            background:#0d1b4b;
            color:#fff;
            font-size:16px;
            cursor:pointer;
            margin-top:10px;
        }

        .guest{
            margin-top:15px;
            color:#0d1b4b;
            text-decoration:underline;
            cursor:pointer;
            font-size:14px;
        }

        .hidden{
            display:none;
        }

    </style>
</head>
<body>

    <div class="login-container">
        <h1>📘 BookHaven</h1>
        <p id="form-text">Welcome back, please login to your account</p>

        <div class="tabs">
            <div id="login-tab" class="active">Login</div>
            <div id="signup-tab">Signup</div>
        </div>

        <!-- Login Form -->
        <form id="login-form">
            <input type="email" placeholder="Email">
            <input type="password" placeholder="Password">
            <button type="submit">Login</button>
        </form>

        <!-- Signup Form -->
        <form id="signup-form" class="hidden">
            <input type="text" placeholder="Full Name">
            <input type="email" placeholder="Email">
            <input type="password" placeholder="Password">
            <button type="submit">Signup</button>
        </form>

        <div class="guest" onclick="window.location.href='index.html'">Continue as Guest</div>
    </div>

    <script>
        const loginTab = document.getElementById('login-tab');
        const signupTab = document.getElementById('signup-tab');
        const loginForm = document.getElementById('login-form');
        const signupForm = document.getElementById('signup-form');
        const formText = document.getElementById('form-text');

        loginTab.addEventListener('click', () => {
            loginTab.classList.add('active');
            signupTab.classList.remove('active');
            loginForm.classList.remove('hidden');
            signupForm.classList.add('hidden');
            formText.textContent = 'Welcome back, please login to your account';
        });

        signupTab.addEventListener('click', () => {
            signupTab.classList.add('active');
            loginTab.classList.remove('active');
            signupForm.classList.remove('hidden');
            loginForm.classList.add('hidden');
            formText.textContent = 'Create a new account';
        });
    </script>

</body>
</html>
