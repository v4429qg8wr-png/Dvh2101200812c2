# Dvh2101200812c2 
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Lớp 12C2 - THPT Trường Chinh</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:linear-gradient(to bottom,#fff5f5,#ffe5e5,#fff);
    color:#333;
    overflow-x:hidden;
}

header{
    height:100vh;
    background:
    linear-gradient(rgba(120,0,0,0.45),rgba(120,0,0,0.45)),
    url('https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80&w=1600&auto=format&fit=crop');

    background-size:cover;
    background-position:center;

    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;

    position:relative;
    overflow:hidden;
}

header::after{
    content:'';
    position:absolute;
    bottom:0;
    left:0;
    width:100%;
    height:120px;
    background:linear-gradient(to top,#fff5f5,transparent);
}

.hero{
    max-width:900px;
    animation:fadeIn 2s ease;
}

.hero h1{
    font-size:75px;
    margin-bottom:20px;
    text-shadow:3px 3px 15px rgba(0,0,0,0.5);
}

.hero p{
    font-size:24px;
    line-height:1.8;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 35px;
    background:#d96c6c;
    color:white;
    text-decoration:none;
    border-radius:40px;
    font-weight:bold;
    transition:0.4s;
}

.btn:hover{
    transform:scale(1.08);
    background:#b94b4b;
}

nav{
    background:rgba(217,108,108,0.9);
    backdrop-filter:blur(10px);
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
    flex-wrap:wrap;
}

nav ul li{
    margin:15px 25px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    font-weight:600;
    transition:0.3s;
}

nav ul li a:hover{
    color:#ffe5e5;
}

section{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:90px 20px;
}

.title{
    text-align:center;
    margin-bottom:50px;
}

.title h2{
    font-size:42px;
    color:#c94f4f;
    margin-bottom:15px;
}

.title p{
    color:#666;
    font-size:18px;
}

.profile{
    background:rgba(255,255,255,0.75);
    padding:50px;
    border-radius:30px;
    box-shadow:0 10px 30px rgba(0,0,0,0.08);
    backdrop-filter:blur(10px);
    border:1px solid rgba(255,255,255,0.5);
}

.profile h3{
    font-size:32px;
    color:#c94f4f;
    margin-bottom:20px;
}

.profile p{
    margin:12px 0;
    font-size:18px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:30px;
}

.card{
    background:rgba(255,255,255,0.75);
    padding:35px;
    border-radius:25px;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
    transition:0.4s;
    backdrop-filter:blur(10px);
    border:1px solid rgba(255,255,255,0.5);
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    margin-bottom:15px;
    color:#c94f4f;
}

.quote{
    background:linear-gradient(135deg,#d96c6c,#f2aaaa);
    color:white;
    padding:60px;
    border-radius:30px;
    text-align:center;
    margin-top:50px;
    box-shadow:0 10px 30px rgba(0,0,0,0.15);
}

.quote h2{
    font-size:40px;
    margin-bottom:25px;
}

.quote p{
    font-size:20px;
    line-height:2;
}

footer{
    background:#c94f4f;
    color:white;
    text-align:center;
    padding:35px;
    margin-top:70px;
}

footer p{
    margin:8px 0;
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(40px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }
}

@media(max-width:768px){

.hero h1{
    font-size:45px;
}

.hero p{
    font-size:18px;
}

.title h2{
    font-size:32px;
}

.quote h2{
    font-size:30px;
}

}

</style>

</head>

<body>

<header>

<div class="hero">

<h1>12C2 - THANH XUÂN</h1>

<p>
“Ba năm cấp ba là khoảng thời gian đẹp nhất của tuổi trẻ,
nơi lưu giữ những kỷ niệm, ước mơ và tình bạn không thể quên.”
</p>

<a href="#profile" class="btn">Khám Phá</a>

</div>

</header>

<nav>

<ul>
<li><a href="#profile">Thông Tin</a></li>
<li><a href="#memory">Kỷ Niệm</a></li>
<li><a href="#teacher">Thầy Cô</a></li>
<li><a href="#dream">Hoài Bão</a></li>
<li><a href="#sorry">Xin Lỗi & Cảm Ơn</a></li>
<li><a href="#quote">Câu Đối</a></li>
</ul>

</nav>

<section id="profile">

<div class="title">
<h2>Thông Tin Học Sinh</h2>
<p>Giới thiệu về thành viên lớp 12C2</p>
</div>

<div class="profile">

<h3>Đỗ Văn Huy</h3>

<p><b>Ngày sinh:</b> 21/01/2008</p>

<p><b>Trường:</b> THPT Trường Chinh</p>

<p><b>Lớp:</b> 12C2</p>

</div>

</section>

<section id="memory">

<div class="title">
<h2>Những Kỷ Niệm</h2>
<p>Khoảng thời gian đẹp nhất của tuổi học trò</p>
</div>

<div class="cards">

<div class="card">

<h3>📚 Những Giờ Học</h3>

<p>
Những giờ học cùng bạn bè, những tiếng cười trong lớp
và những lần cùng nhau cố gắng sẽ mãi là ký ức đẹp.
</p>

</div>

<div class="card">

<h3>🎉 Hoạt Động Tập Thể</h3>

<p>
Những lần văn nghệ, cắm trại, thi đấu thể thao
đã giúp lớp 12C2 đoàn kết và gắn bó hơn.
</p>

</div>

<div class="card">

<h3>💖 Tình Bạn</h3>

<p>
Thanh xuân là khi có những người bạn cùng nhau trưởng thành,
cùng chia sẻ niềm vui và khó khăn.
</p>

</div>

</div>

</section>

<section id="teacher">

<div class="title">
<h2>Thầy Cô</h2>
<p>Những người lái đò thầm lặng</p>
</div>

<div class="cards">

<div class="card">

<h3>🌸 Sự Tận Tâm</h3>

<p>
Thầy cô luôn tận tình giảng dạy,
truyền đạt kiến thức và động viên học sinh.
</p>

</div>

<div class="card">

<h3>❤️ Sự Quan Tâm</h3>

<p>
Không chỉ dạy học, thầy cô còn luôn quan tâm,
chia sẻ và giúp học sinh trưởng thành hơn.
</p>

</div>

<div class="card">

<h3>✨ Lòng Biết Ơn</h3>

<p>
12C2 luôn biết ơn những công lao và tình cảm
mà thầy cô đã dành cho lớp.
</p>

</div>

</div>

</section>

<section id="dream">

<div class="title">
<h2>Hoài Bão Tương Lai</h2>
<p>Những ước mơ đang chờ phía trước</p>
</div>

<div class="cards">

<div class="card">

<h3>🚀 Ước Mơ</h3>

<p>
Mỗi thành viên của lớp đều mang trong mình
những ước mơ và mục tiêu riêng.
</p>

</div>

<section id="sorry">

<div class="title">
<h2>Lời Xin Lỗi Và Cảm Ơn</h2>
<p>Những điều muốn gửi đến thầy cô và bạn bè</p>
</div>

<div class="cards">

<div class="card">

<h3>🙏 Xin Lỗi Thầy Cô</h3>

<p>
Chúng em xin lỗi vì đôi lúc còn nghịch ngợm,
chưa chăm chỉ học tập và đôi khi làm thầy cô phải buồn lòng.
Cảm ơn thầy cô đã luôn kiên nhẫn,
dạy dỗ và đồng hành cùng chúng em suốt những năm tháng học trò.
</p>

</div>

<div class="card">

<h3>💖 Xin Lỗi Bạn Bè</h3>

<p>
Thanh xuân chắc chắn sẽ có những lúc hiểu lầm,
giận nhau hay vô tình làm tổn thương nhau.
Mong rằng tất cả sẽ luôn nhớ về nhau bằng những kỷ niệm đẹp nhất.
</p>

</div>

<div class="card">

<h3>🌸 Lời Cảm Ơn</h3>

<p>
Cảm ơn 12C2 đã trở thành một phần đẹp nhất của tuổi trẻ.
Cảm ơn vì những tiếng cười,
những khoảnh khắc bên nhau và những ký ức không thể quên.
</p>

</div>

</div>

</section>

<div class="card">

<h3>🌟 Nỗ Lực</h3>

<p>
Dù con đường phía trước còn nhiều thử thách,
12C2 vẫn luôn cố gắng và không ngừng vươn lên.
</p>

</div>

<div class="card">

<h3>🎓 Thành Công</h3>

<p>
Hy vọng trong tương lai,
mọi người sẽ đạt được thành công và hạnh phúc.
</p>

</div>

</div>

</section>

<section id="quote">

<div class="quote">

<h2>Câu Đối Thanh Xuân</h2>

<p>

“Ba năm đèn sách lưu kỷ niệm đẹp<br><br>

Một thuở học trò giữ mãi tình thân.”


</p>

</div>

</section>

<footer>

<p><b>WEBSITE GIỚI THIỆU LỚP 12C2</b></p>

<p>Thanh xuân - Kỷ niệm - Ước mơ ❤️</p>

<p>© 2026 - Đỗ Văn Huy</p>

</footer>

</body>
</html>
