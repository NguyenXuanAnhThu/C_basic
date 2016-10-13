## Tìm hiểu về Markdown
>Tài liệu: Tìm hiểu về Markdown
>
>Thực hiện: Vũ Thị Thuỷ Tiên
>
>Cập nhật lần cuối: 14/10/2016

### Markdown là gì ?
- Là ngôn ngữ đánh dấu siêu văn bản
- Sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản
- Văn bản được viết bằng Markdown có thể chuyển đổi sang HTML và ngược lại

### Markdown dùng để làm gì ?
- Dùng để viết tài liệu và đánh dấu siêu văn bản

### Các cú pháp thường gặp
####1.Tiêu đề
- Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu để, có thể dùng từ 1 đến 6 kí tự # liên tiếp mức độ giảm dần từ 1 đến 6
Ví dụ:
```sh
#Tiêu đề 1
##Tiêu đề 2
###Tiêu đề 3
####Tiêu đề 4
```
sẽ được
#Tiêu đề 1
##Tiêu đề 2
###Tiêu đề 3
####Tiêu đề 4

####2.Chèn ảnh, chèn link
- Để chèn hyperlink bạn chỉ cần paste luôn linh đó vào file .md
Ví dụ: https://github.com
Hoặc bạn cũng có thể sử dụng cú pháp sau để thu ngắn đường dẫn của link
`[tên](đường link)`
Ví dụ: `[GitHub](https://github.com)` sẽ được [GitHub](https://github.com) 
- Để chèn ảnh thì bạn hãy sử dụng cú pháp sau:
`<img src="link ảnh của bạn">`
Ví dụ: `<img src="http://imgur.com/a/3qg0Y">` sẽ được <img src="http://imgur.com/a/3qg0Y">

####3.Kí tự in đậm, in nghiêng
- Để in đậm một đoạn text bạn chỉ cần dùng cú pháp: `**từ cần in đậm**` sẽ được **từ cần in đậm**
- Để in nghiêng một đoạn text bạn chỉ cần dùng cú pháp: `*từ cần in nghiêng*` sẽ được *từ cần in nghiêng*

####4.Trích dẫn, bo chữ
- Để bo một đoạn text thì bạn chỉ cần dùng cú pháp: ``đoạn cần bo`` sẽ được
`đoạn cần bo`

####5.Gạch đầu dòng
- Để sử dụng gạch đầu dòng bạn chỉ cần sử dụng cú pháp sau:
```sh
- Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>
```
sẽ được
- Gạch đầu dòng thứ nhất
  <ul>
  <li>Thụt với đầu dòng 1</li>
  <li>Thụt với đầu dòng 1</li>
  </ul>
- Gạch đầu dòng thứ hai
  <ul>
  <li>Thụt với đầu dòng 2</li>
  <li>Thụt với đầu dòng 2</li>
  </ul>

####6. Tạo bảng
Kí tự | bắt đầu một hàng
Kí tự - tách phần header của bảng
Kí tự = tách phần footer
Ví dụ:
```sh
| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
```
sẽ được
| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
## Hết