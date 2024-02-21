# AI With Chat GPT Model

Dự án demo cho AI dùng model ChatGPT để phân tích và xử lý trả lời các câu hỏi FAQ cho khách hàng Ajinomoto

## Quy trình xử lý

- Xây dựng bộ data để training AI
- Training AI và lưu dữ liệu AI đã training vào Vector Database
- User input câu hỏi
- Xử lý embed câu hỏi bằng model embedding của GPT
- Query similarity data sau khi embed với Vector Database
- Xử lý trả lời cho user bằng GPT model


## Testing

cài đặt các package cần thiết

```
pip install -r requirements.txt
```

Thêm hoặc sửa data cần training trong folder `./data`

Chạy AI

```
python3 chatgpt.py
```

demo:

![query with AI](https://github.com/tmtuan8017/ai-chatgpt/blob/master/demo/ai-demo.png?raw=true)
