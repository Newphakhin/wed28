<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phakhin Coffee - ร้านกาแฟออนไลน์</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: linear-gradient(135deg, #6B4E3D 0%, #8D6E63 100%);
            min-height: 100vh;
        }
        .header {
            background: rgba(255, 255, 255, 0.652);
            backdrop-filter: blur(10px);
            padding: 1rem 0;
            box-shadow: 0 2px 20px rgba(0,0,0,0.1);
            position: sticky; top: 0; z-index: 100;
        }
        .nav {
            max-width: 1200px; margin: 0 auto;
            display: flex; justify-content: space-between; align-items: center;
            padding: 0 2rem;
        }
        .logo {
            display: flex; align-items: center; gap: 10px;
            font-size: 1.5rem; font-weight: bold;
            color: #6B4E3D; text-decoration: none;
        }
        .logo img {
            height: 150px; width: auto; border-radius: 50%;
        }
        .cart-btn {
            background: #FF6B35; color: white;
            border: none; padding: 12px 24px; border-radius: 50px;
            cursor: pointer; font-size: 1rem;
            display: flex; align-items: center; gap: 8px;
            transition: all 0.3s ease; position: relative;
        }
        .cart-btn:hover {
            background: #E55A2B; transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(255, 107, 53, 0.3);
        }
        .cart-count {
            background: #fff; color: #FF6B35;
            border-radius: 50%; width: 24px; height: 24px;
            display: flex; align-items: center; justify-content: center;
            font-size: 0.8rem; font-weight: bold;
            position: absolute; top: -8px; right: -8px;
        }
        .hero { text-align: center; padding: 80px 2rem; color: white; }
        .hero h1 { font-size: 3.5rem; margin-bottom: 1rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
        .hero p { font-size: 1.2rem; margin-bottom: 2rem; opacity: 0.9; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 2rem; }
        .menu-section {
            background: white; margin: 2rem 0; border-radius: 20px;
            padding: 3rem 2rem; box-shadow: 0 10px 40px rgba(0,0,0,0.1);
        }
        .section-title { text-align: center; font-size: 2.5rem; color: #6B4E3D; margin-bottom: 3rem; }
        .menu-grid {
            display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .menu-item {
            background: #fff; border-radius: 15px; overflow: hidden;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            transition: all 0.3s ease; position: relative;
        }
        .menu-item:hover { transform: translateY(-10px); box-shadow: 0 15px 40px rgba(0,0,0,0.15); }
        .menu-item-image img { width: 100%; height: 200px; object-fit: cover; }
        .menu-item-content { padding: 1.5rem; }
        .menu-item-name { font-size: 1.3rem; font-weight: bold; color: #333; margin-bottom: 0.5rem; }
        .menu-item-description { color: #666; margin-bottom: 1rem; line-height: 1.4; }
        .menu-item-footer { display: flex; justify-content: space-between; align-items: center; }
        .menu-item-price { font-size: 1.2rem; font-weight: bold; color: #FF6B35; }
        .add-to-cart {
            background: #FF6B35; color: white; border: none;
            padding: 10px 20px; border-radius: 25px;
            cursor: pointer; transition: all 0.3s ease; font-weight: bold;
        }
        .add-to-cart:hover { background: #E55A2B; transform: scale(1.05); }

        /* Cart Modal */
        .cart-modal {
            display: none; position: fixed; top: 0; left: 0;
            width: 100%; height: 100%;
            background: rgba(0,0,0,0.5); backdrop-filter: blur(4px);
            justify-content: center; align-items: center;
            z-index: 200;
        }
        .cart-content {
            background: white; padding: 20px; border-radius: 15px;
            width: 90%; max-width: 500px; max-height: 80vh; overflow-y: auto;
        }
        .cart-item {
            display: flex; justify-content: space-between; align-items: center;
            margin-bottom: 10px; border-bottom: 1px solid #eee; padding-bottom: 10px;
        }
        .cart-item img {
            width: 50px; height: 50px; border-radius: 8px; object-fit: cover;
        }
        .cart-item-info { flex: 1; margin-left: 10px; }
        .cart-item-name { font-weight: bold; }
        .cart-item-controls button {
            background: #FF6B35; color: white; border: none;
            padding: 5px 10px; margin: 0 2px; border-radius: 5px;
            cursor: pointer;
        }
        .cart-total { font-weight: bold; margin-top: 15px; text-align: right; }
        .close-btn {
            background: red; color: white; border: none;
            padding: 8px 15px; border-radius: 8px;
            float: right; cursor: pointer;
        }
        .checkout-btn {
            background: #4CAF50; 
            color: white; 
            border: none; 
            padding: 10px 20px; 
            border-radius: 8px; 
            margin-top: 15px; 
            cursor: pointer; 
            font-size: 1rem; 
            width: 100%;
        }
    </style>
</head>
<body>
    <header class="header">
        <nav class="nav">
            <a href="#" class="logo">
                <img src="9.png" alt="Phakhin Coffee Logo">
                Phakhin Coffee
            </a>
            <button class="cart-btn" onclick="openCart()">
                🛒 ตะกร้า
                <span class="cart-count" id="cart-count">0</span>
            </button>
        </nav>
    </header>

    <section class="hero">
        <h1>ยินดีต้อนรับสู่ Phakhin Coffee</h1>
        <p>กาแฟคุณภาพเยี่ยมที่คัดสรรมาเป็นพิเศษเพื่อคุณ</p>
    </section>

    <div class="container">
        <section class="menu-section">
            <h2 class="section-title">เมนูกาแฟของเรา</h2>
            <div class="menu-grid" id="menu-grid"></div>
        </section>
    </div>

    <!-- Cart Modal -->
    <div class="cart-modal" id="cart-modal">
        <div class="cart-content">
            <button class="close-btn" onclick="closeCart()">ปิด</button>
            <h2>ตะกร้าสินค้า</h2>
            <div id="cart-items"></div>
            <div class="cart-total" id="cart-total"></div>
            <button class="checkout-btn" id="checkout-btn" onclick="checkout()">ชำระเงิน</button>
        </div>
    </div>

    <script>
        const menuItems = [
            { id: 1, name: "เอสเปรสโซ่", description: "กาแฟเข้มข้น หอมกรุ่น", price: 65, image: "1.jpg" },
            { id: 2, name: "คาปูชิโน่", description: "เอสเปรสโซ่ผสมนมฟองนุ่ม", price: 85, image: "3.jpg" },
            { id: 3, name: "ลาเต้", description: "รสชาตินุ่มละมุน", price: 90, image: "4.jpg" },
            { id: 4, name: "มอคค่า", description: "ผสมช็อกโกแลตหวานละมุน", price: 95, image: "6.jpeg" }
        ];

        let cart = [];

        function createMenu() {
            const menuGrid = document.getElementById('menu-grid');
            menuGrid.innerHTML = '';
            menuItems.forEach(item => {
                const menuItemElement = document.createElement('div');
                menuItemElement.className = 'menu-item';
                menuItemElement.innerHTML = `
                    <div class="menu-item-image">
                        <img src="${item.image}" alt="${item.name}">
                    </div>
                    <div class="menu-item-content">
                        <div class="menu-item-name">${item.name}</div>
                        <div class="menu-item-description">${item.description}</div>
                        <div class="menu-item-footer">
                            <div class="menu-item-price">฿${item.price}</div>
                            <button class="add-to-cart" onclick="addToCart(${item.id})">เพิ่มลงตะกร้า</button>
                        </div>
                    </div>
                `;
                menuGrid.appendChild(menuItemElement);
            });
        }

        function addToCart(itemId) {
            const item = menuItems.find(i => i.id === itemId);
            const existingItem = cart.find(i => i.id === itemId);
            if (existingItem) {
                existingItem.quantity += 1;
            } else {
                cart.push({ ...item, quantity: 1 });
            }
            updateCartCount();
        }

        function updateCartCount() {
            const count = cart.reduce((total, item) => total + item.quantity, 0);
            document.getElementById('cart-count').textContent = count;
        }

        function openCart() {
            const cartItemsContainer = document.getElementById('cart-items');
            const checkoutBtn = document.getElementById('checkout-btn');
            cartItemsContainer.innerHTML = '';
            let total = 0;

            cart.forEach(item => {
                total += item.price * item.quantity;
                cartItemsContainer.innerHTML += `
                    <div class="cart-item">
                        <img src="${item.image}" alt="${item.name}">
                        <div class="cart-item-info">
                            <div class="cart-item-name">${item.name}</div>
                            <div>฿${item.price} x ${item.quantity}</div>
                        </div>
                        <div class="cart-item-controls">
                            <button onclick="changeQuantity(${item.id}, 1)">+</button>
                            <button onclick="changeQuantity(${item.id}, -1)">-</button>
                            <button onclick="removeItem(${item.id})">ลบ</button>
                        </div>
                    </div>
                `;
            });

            document.getElementById('cart-total').textContent = `รวมทั้งหมด: ฿${total}`;
            checkoutBtn.style.display = cart.length > 0 ? 'block' : 'none';
            document.getElementById('cart-modal').style.display = 'flex';
        }

        function closeCart() {
            document.getElementById('cart-modal').style.display = 'none';
        }

        function changeQuantity(itemId, change) {
            const item = cart.find(i => i.id === itemId);
            if (item) {
                item.quantity += change;
                if (item.quantity <= 0) {
                    cart = cart.filter(i => i.id !== itemId);
                }
                updateCartCount();
                openCart();
            }
        }

        function removeItem(itemId) {
            cart = cart.filter(i => i.id !== itemId);
            updateCartCount();
            openCart();
        }

        function checkout() {
            alert("ไปหน้าชำระเงิน");
            // window.location.href = 'checkout.html'; // ถ้ามีหน้าชำระเงินจริง
        }

        document.addEventListener('DOMContentLoaded', () => {
            createMenu();
        });
    </script>
</body>
</html>
