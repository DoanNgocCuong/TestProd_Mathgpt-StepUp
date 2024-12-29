Em tính làm như này, các anh xem ukii hông ạ. 
- Step 1 : OCR ra text ( ví dụ 1 ảnh 5 bài toán => OCR ra đề bài 5 bài toán)
- Step 2: Nhờ GPT chia thành các bài toán riêng. 
JSON 
["bài 1": "<nội dung bài 1>", "bài 2": "<nội dung bài 2>", ...] 

Hiển thị lên UI sẽ là các bài riêng lẻ. 
User thích bài nào thì click vào bài đó. 

- Step 3: Cho qua model Math để xử lý riêng câu đó. 
--------------------
<Thay cho việc khoanh được (Detect được) riêng các bài ngay trên ảnh gốc ạ >