<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Wislist của Bòi Bói Boi🫃🏻</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Quicksand:wght@400;600&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  font-family:'Quicksand',sans-serif;
  background: radial-gradient(circle at top,#2b0b12,#000);
  color:white;
}

.header{
  padding:20px;
  text-align:center;
  border-bottom:1px solid #333;
}

.title{
  font-family:'Playfair Display';
  font-size:22px;
  color:#ff7b9c;
}

.subtitle{
  font-size:13px;
  color:#aaa;
}

.container{
  max-width:520px;
  margin:auto;
  padding:15px;
}

.card{
  background:#111;
  border-radius:20px;
  padding:15px;
  margin-top:15px;
  box-shadow:0 0 20px rgba(255,0,80,0.2);
}

input,select,textarea{
  width:100%;
  margin-top:10px;
  padding:12px;
  border-radius:12px;
  border:none;
  background:#1c1c1c;
  color:white;
}

.priority{
  display:flex;
  gap:5px;
  margin-top:10px;
}

.priority div{
  flex:1;
  padding:8px;
  border-radius:10px;
  text-align:center;
  background:#222;
  cursor:pointer;
  font-size:12px;
}

.activeP{
  background:#ff4f87;
}

button{
  width:100%;
  margin-top:12px;
  padding:12px;
  border:none;
  border-radius:12px;
  background:linear-gradient(90deg,#ff4f87,#ff8fb1);
  color:white;
  font-weight:bold;
}

.item{
  background:#111;
  border-radius:15px;
  padding:10px;
  margin-top:10px;
}

img{
  width:100%;
  border-radius:10px;
  margin-top:5px;
}

.done{
  opacity:0.5;
  text-decoration:line-through;
}

.actions{
  display:flex;
  gap:5px;
  margin-top:5px;
}

.actions button{
  font-size:11px;
}
</style>
</head>

<body>

<div class="header">
  <div class="title">🌹 Wislist của Bòi Bói Boi🫃🏻</div>
  <div class="subtitle">Mọi điều em muốn, anh sẽ nhớ 💌</div>
</div>

<div class="container">

<div class="card">

<input id="name" placeholder="💝 Tên quà tặng" />
<select id="category">
  <option>💖 Quà đôi & lãng mạn</option>
  <option>👕 Thời trang</option>
  <option>💻 Công nghệ</option>
</select>

<input id="price" placeholder="💰 Giá (VND)" />
<input id="link" placeholder="🔗 Link sản phẩm" />
<input id="image" placeholder="🖼️ Link ảnh" />
<textarea id="note" placeholder="💬 Ghi chú thêm"></textarea>

<div class="priority">
  <div onclick="setP(this,1)">🤍 Ước</div>
  <div onclick="setP(this,2)">🌷 Thích</div>
  <div onclick="setP(this,3)">🥺 Muốn</div>
  <div onclick="setP(this,4)">🔥 Phải có</div>
</div>

<button onclick="addItem()">➕ Thêm vào danh sách 💖</button>

</div>

<div id="list"></div>

</div>

<script>
let items=JSON.parse(localStorage.getItem("lv4"))||[];
let priority=1;

function save(){
 localStorage.setItem("lv4",JSON.stringify(items));
}

function setP(el,p){
 priority=p;
 document.querySelectorAll(".priority div").forEach(x=>x.classList.remove("activeP"));
 el.classList.add("activeP");
}

function render(){
 let list=document.getElementById("list");
 list.innerHTML="";

 items.forEach((item,i)=>{
  let div=document.createElement("div");
  div.className="item";

  div.innerHTML=`
   <div class="${item.done?'done':''}">
    <strong>${item.name}</strong> (${item.category})
    <div>💰 ${item.price||0}</div>
    <div>${item.note||""}</div>
    ${item.image?`<img src="${item.image}">`:""}
    ${item.link?`<a href="${item.link}" target="_blank">🛒 Xem</a>`:""}
   </div>

   <div class="actions">
    <button onclick="toggle(${i})">✔️</button>
    <button onclick="del(${i})">❌</button>
   </div>
  `;

  list.appendChild(div);
 });
}

function addItem(){
 let name=nameInput.value;
 if(!name) return alert("Nhập quà 😾");

 items.push({
  name,
  category:category.value,
  price:price.value,
  link:link.value,
  image:image.value,
  note:note.value,
  priority,
  done:false
 });

 save();
 render();

 nameInput.value="";
 linkInput.value="";
 imageInput.value="";
 noteInput.value="";
 priceInput.value="";
}

function del(i){
 items.splice(i,1);
 save();
 render();
}

function toggle(i){
 items[i].done=!items[i].done;
 save();
 render();
}

render();
</script>

</body>
</html>
