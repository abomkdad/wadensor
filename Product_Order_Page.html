<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>نظام إدارة المبيعات والمخزون</title>
  <style>
    body {
      font-family: Tahoma, sans-serif;
      background-color: #f9f9f9;
      padding: 20px;
    }
    h1 {
      text-align: center;
    }
    #searchBar {
      display: block;
      margin: 10px auto;
      width: 300px;
      padding: 8px;
      font-size: 16px;
    }
    .products-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }
    .product-card {
      background: #fff;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 8px;
      width: 240px;
    }
    .product-card img {
      max-width: 100%;
      border-radius: 5px;
    }
    .product-card .info {
      margin: 5px 0;
    }
    #cart {
      margin-top: 30px;
      background: #fff;
      padding: 15px;
      border-radius: 10px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    #cartList {
      list-style: none;
      padding: 0;
    }
    #submitBtn, #downloadBtn {
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>نظام إدارة المبيعات</h1>
  <input type="text" id="searchBar" placeholder="🔍 ابحث عن منتج بالاسم أو الكود...">
  <div class="products-container" id="products"></div>

  <div id="cart">
    <h2>🛒 العربة</h2>
    <ul id="cartList"></ul>
    <div id="cartTotal">الإجمالي: 0 ₪</div>
    <button id="submitBtn">إرسال الطلب</button>
    <button id="downloadBtn">📥 تحميل المخزون Excel</button>
  </div>

  <script>
    const updateEndpoint = "https://script.googleusercontent.com/macros/echo?user_content_key=AehSKLhwaQdLVCPtdkcey_lYHM5FdGMDAIjnGd1AtuaK8tbWR9DQQSh44qYq_ty2Sm8VAYq8sh6cvadMa-8CJgAaZZZ1keCDDa1puNiE1tccMoDlnHhGwz7Pi1wbhrJsALnBJgGKlLON2br65KHn1eXYEO0osRodSWhjZTSw9x-v26FElzMNLFTtMByHe1Ipxq-lhtWP-8XPiwMwB3nScAqmEgb6QBgHuumCy41n9BrfLu2lxwdyYdM4XVHxiquQuFDCJgeSTjp8y1o6bVLw9X7Ibwg7qhBaOAHOYyj00I8Z&lib=MksP0qUVOj74sQYkhNyfJJkZ-95pyv5QT";

    let allProducts = [];

    async function fetchProducts() {
      try {
        const res = await fetch(updateEndpoint);
        const products = await res.json();
        allProducts = products;
        renderProducts(products);
      } catch (error) {
        alert("⚠️ تعذر تحميل المنتجات. تحقق من اتصالك أو من عنوان السكربت.");
      }
    }

    function renderProducts(products) {
      const container = document.getElementById("products");
      container.innerHTML = "";
      products.forEach(product => {
        const card = document.createElement("div");
        card.className = "product-card";
        card.innerHTML = `
          <img src="${product.image_url}" alt="${product.product_name_ar}">
          <div class="info"><strong>${product.product_name_ar}</strong></div>
          <div class="info">الكود: ${product.product_code}</div>
          <div class="info">السعر: ${product.price} ₪</div>
          <div class="info">المتوفر: <span class="stock">${product.quantity}</span></div>
          <input type="number" value="6" min="1" max="${product.quantity}">
          <button onclick="addToCart(this, '${product.product_code}', '${product.product_name_ar}', ${product.price})">➕ أضف</button>
        `;
        container.appendChild(card);
      });
    }

    document.getElementById("searchBar").addEventListener("input", function() {
      const q = this.value.trim().toLowerCase();
      const filtered = allProducts.filter(p =>
        p.product_name_ar.toLowerCase().includes(q) || p.product_code.toLowerCase().includes(q)
      );
      renderProducts(filtered);
    });

    fetchProducts();

    function addToCart(btn, code, name, price) {
      const qty = parseInt(btn.parentElement.querySelector("input").value);
      const available = parseInt(btn.parentElement.querySelector(".stock").textContent);
      if (qty <= 0 || qty > available) return alert("كمية غير صالحة");

      const total = qty * price;
      const li = document.createElement("li");
      li.textContent = `${name} (كود: ${code}) × ${qty} = ${total} ₪`;
      li.dataset.code = code;
      li.dataset.qty = qty;
      li.dataset.total = total;
      document.getElementById("cartList").appendChild(li);

      updateCartTotal();
    }

    function updateCartTotal() {
      let total = 0;
      document.querySelectorAll("#cartList li").forEach(li => {
        total += parseFloat(li.dataset.total);
      });
      document.getElementById("cartTotal").textContent = `الإجمالي: ${total} ₪`;
    }

    document.getElementById("submitBtn").addEventListener("click", async () => {
      const items = document.querySelectorAll("#cartList li");
      if (!items.length) return alert("العربة فارغة!");

      for (const item of items) {
        const code = item.dataset.code;
        const qty = parseInt(item.dataset.qty);

        try {
          const res = await fetch(updateEndpoint, {
            method: "POST",
            headers: { "Content-Type": "application/json" },
            body: JSON.stringify({ code, quantity: qty })
          });
          const text = await res.text();
          if (!res.ok || !text.includes("تم")) {
            alert(`❌ فشل إرسال المنتج: ${code}\n${text}`);
          }
        } catch (err) {
          alert(`⚠️ فشل الاتصال بالخادم:\n${err}`);
        }
      }
      alert("✅ تم إرسال الطلب بنجاح");
      document.getElementById("cartList").innerHTML = "";
      updateCartTotal();
    });

    document.getElementById("downloadBtn").addEventListener("click", () => {
      window.open(`${updateEndpoint}?action=download`, '_blank');
    });
  </script>
</body>
</html>
