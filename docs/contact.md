# Thông Tin Liên Hệ

Để biết thêm thông tin, đề xuất hợp tác, hoặc yêu cầu tuyển dụng, xin vui lòng liên hệ qua các phương tiện sau hoặc gửi tin nhắn trực tiếp qua mẫu đơn dưới đây:

- :fontawesome-solid-phone: _di động: [0839.914.653]()_
- :fontawesome-solid-envelope: _[philogixstudio@gmail.com](mailto:philogixstudio@gmail.com)_
- :fontawesome-brands-facebook: _[facebook.com/Philogix](https://www.facebook.com/Philogix)_
- :fontawesome-brands-github: _[github.com/philogix](https://github.com/philogix)_
- :fontawesome-brands-artstation: _[philogix.artstation.com](https://philogix.artstation.com)_

## Mẫu Liên Hệ

<div class="contact-form">
<form action="your-form-submission-link" method="post">
  <div class="input-group">
    <div class="input-field">
      </br>
      <label for="name">Họ và Tên</label>
      <input type="text" id="name" name="name" required>
    </div>
    <div class="input-field">
      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>
    </div>
  </div>
  
  <label for="message">Tin Nhắn</label>
  <textarea id="message" name="message" rows="8" required></textarea>
  
  <div class="submit-button">
    <button type="submit">Gửi</button>
  </div>
</form>
</div>

<style>
.material-icons {
  vertical-align: middle;
  padding-right: 5px;
}
.contact-form form {
  display: flex;
  flex-direction: column;
  margin: auto;
}
.input-group {
  display: flex;
  flex-wrap: wrap; /* Thêm để xử lý trường hợp màn hình nhỏ */
}
.input-field {
  display: flex;
  flex-direction: column;
  flex: 1;
  margin-right: 1em;
}
.input-field:last-child {
  margin-right: 0;
}
.contact-form label {
  margin-bottom: 0.5em;
}
.contact-form input[type="text"],
.contact-form input[type="email"],
.contact-form textarea {
  padding: 0.5em;
  border: 1px solid gray;
  background-color: transparent;
  border-radius: 10px;
  margin-bottom: 2em; /* Khoảng cách dưới mỗi trường nhập */
}
.submit-button {
  text-align: right; /* Căn phải nút gửi */
}
.contact-form button[type="submit"] {
  padding: 0.5em 5em; /* Điều chỉnh kích thước nút gửi */
  border: 01px solid gray; /* Viền trắng */
  background-color: transparent; /* Nền trong suốt */
  color: white;
  border-radius: 10px;
  cursor: pointer;
  transition: background-color 0.3s ease; /* Hiệu ứng khi hover */
}
.contact-form button[type="submit"]:hover {
  background-color: white; /* Màu nền khi hover */
  color: #333; /* Màu chữ khi hover */
}
</style>
