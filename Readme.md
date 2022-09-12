# 1. Cấu trúc cơ bản của 1 file html
``` html
    <!DOCTYPE html>
    <html>
    <head>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <title>Page Title</title>
        <meta name='viewport' content='width=device-width, initial-scale=1'>
        <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
        <script src='main.js'></script>
    </head>
    <body>
        <div class="container">
            
            
        </div>
    </body>
    </html>
```

# 2. Các thẻ cơ bản

Cách viết các thẻ vào trong file html

```html
    <TEN-THE></TEN-THE>

    hoặc

    <TEN-THE> (với các thẻ ko cần đóng)
```
Các thẻ hay dùng
- div
- p : đoạn văn bản, tự động cách trên dưới 1 khoảng trắng
- span : đoạn văn bản
- h1: thẻ heading 1
- h2: thẻ heading 2
- h3: thẻ heading 3
- h4: thẻ heading 4
- h5: thẻ heading 5
- h6: thẻ heading 6
- br
- b
- i
- u

# 3. Css
Toàn bộ Css đc viết trong file có đuôi là .css (ví dụ [main.css](./main.css))

Trong các thẻ của html có thể khai báo các attribute là id, class

Cách viết: có 2 cách viết dưới đây
```css
    .font-style {
        font-style: italic;
    }
    #font-bold {
        font-size: 36px;
    }
```

Với các thẻ khai báo class thì dùng cách viết `.font-style`
Với các thẻ có khai báo id thì dùng cách viết `#font-bold`

Các css có thể ghi đè lên nhau. Như trong file [index.html](./index.html) có 
``` html
    <p id="font-bold" class="font-weight-bold">font-weight: bold</p>
```

Tức là đang sử dụng cả 2 css


Các thuộc tính cơ bản cần phải biết

+ Margin và padding

    - Margin là biên giữa hai khối,
    - Padding là lề của nội dung so với khối.
<img src="https://goclamweb.com/wp-content/uploads/2018/02/padding-va-margin.png">
+ Border : viền, 1px (độ dày) black (màu) solid (loại nét)

+ Text-align : canh lề

+ Font-size : kích thước.

+ Font-weight : bold độ đậm nhạt, giống như thẻ <b></b>

+ Font-family : kiểu chữ

+ Font-style: italic : tạo chữ in nghiêng

+ Float : left, dồn sang một bên

+ Text-decoration: none, underline.

+ Line-height: 20px: độ giãn dòng.

+ color: (màu chữ) dùng green, red hay mã màu

+ background-color: (màu nền)black

+ background-image: url(imgage source)

+ Float : dồn sang một bên

+ Border: tạo viền cho khôi