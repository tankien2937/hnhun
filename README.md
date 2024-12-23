<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>hnhun cuti</title>
  <style>
    #content {
      display: none; /* Ẩn nội dung mặc định */
    }
    #message {
      text-align: center;
      margin-top: 50px;
      font-size: 20px;
    }
  </style>
</head>
<body>
  <div id="message">Trang này chỉ mở vào một thời gian cụ thể.</div>
  <div id="content">
    <h1>Happy Birhthday</h1>
<img src="https://www.icegif.com/wp-content/uploads/2022/07/icegif-403.gif">
    <p>Chúc em tuổi mới luôn bình an, tràn đầy sức khoẻ, vui vẻ, chúc tất cả những điều tốt đẹp sẽ đến với bé iu của anh.Anh mong sẽ được cùng em đón những sinh nhật sau này. Happy biỉthday my love 🎂🎉 </p>
  </div>

  <script>
    // Thời gian bắt đầu và kết thúc (giờ, phút)
    const startTime = new Date();
    startTime.setHours(0, 0, 0); // Bắt đầu lúc 00:00 Sáng
    const endTime = new Date();
    endTime.setHours(12, 0, 0); // Kết thúc lúc 12:00 Trưa

    // Kiểm tra thời gian hiện tại
    const now = new Date();

    if (now >= startTime && now <= endTime) {
      document.getElementById("message").style.display = "none"; // Ẩn thông báo
      document.getElementById("content").style.display = "block"; // Hiển thị nội dung
    } else {
      document.getElementById("message").innerText =
        "Đúng 12h đêm nó sẽ mở cho bé nha ❤";
    }
  </script>
</body>
</html>
