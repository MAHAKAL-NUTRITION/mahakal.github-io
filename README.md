<nav class="mahakal nutrition">
    <div class="MN">
        <img src="img/dark-logo.png" class="brand-logo" alt="">
        <div class="nav-items">
            <div class="search">
                <input type="text" class="search-box" placeholder="Search brand, product">
                <button class="search-btn">Search</button>
            </div>
            <a href="#"><img src="img/user.png" alt=""></a>
            <a href="#"><img src="img/cart.png" alt=""></a>
        </div>
    </div>
</nav>
/* nav.css */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
}

.navbar {
    position: sticky;
    top: 0;
    left: 0;
    width: 100%;
    background: #f5f5f5;
    z-index: 9;
}

.nav {
    padding: 10px 10vw;
    display: flex;
    justify-content: space-between;
}

.brand-logo {
    height: 60px;
}

.nav-items {
    display: flex;
    align-items: center;
}

.search {
    width: 500px;
    display: flex;
}

.search-box {
    width: 80%;
    height: 40px;
    padding: 10px;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
    border: 1px solid #d1d1d1;
    text-transform: capitalize;
    background: none;
    color: #a9a9a9;
    outline: none;
}

.search-btn {
    width: 20%;
    height: 40px;
    padding: 10px 20px;
    border: none;
    outline: none;
    cursor: pointer;
    background: #383838;
    color: #fff;
    text-transform: capitalize;
    font-size: 15px;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
}

.search-box::placeholder {
    color: #a9a9a9;
}

.nav-items a {
    margin-left: 20px;
}

.nav-items a img {
    width: 30px;
}
<ul class="links-container">
    <li class="link-item"><a href="#" class="link">Home</a></li>
    <li class="link-item"><a href="#" class="link">Women</a></li>
    <li class="link-item"><a href="#" class="link">Men</a></li>
    <li class="link-item"><a href="#" class="link">Kids</a></li>
    <li class="link-item"><a href="#" class="link">Accessories</a></li>
</ul>
