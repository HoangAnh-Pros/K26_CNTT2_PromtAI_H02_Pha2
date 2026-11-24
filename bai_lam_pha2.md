# BÀI LÀM PHA 2 

- **Họ tên:** Lê Hoàng Anh
- **Lớp:** CNTT2
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** CHAT GPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[\
&#x20; {\
&#x20;   "ma_goi": "SVT",\
&#x20;   "ngay_su_kien": "2026-12-20",\
&#x20;   "nguoi_lon": 2,\
&#x20;   "tre_em": 1,\
&#x20;   "loai_ve": "thuong",\
&#x20;   "ghi_chu": null\
&#x20; },\
&#x20; {\
&#x20;   "ma_goi": "FZ",\
&#x20;   "ngay_su_kien": "2027-01-05",\
&#x20;   "nguoi_lon": 3,\
&#x20;   "tre_em": 0,\
&#x20;   "loai_ve": "thuong",\
&#x20;   "ghi_chu": "hỗ trợ xe lăn"\
&#x20; },\
&#x20; {\
&#x20;   "ma_goi": "VIP",\
&#x20;   "ngay_su_kien": null,\
&#x20;   "nguoi_lon": 4,\
&#x20;   "tre_em": 0,\
&#x20;   "loai_ve": "vip",\
&#x20;   "ghi_chu": "hỗ trợ tìm chỗ cho người khiếm thị"\
&#x20; }\
]
```

**Link trò chuyện:** https://chatgpt.com/share/6b053509-37d8-83ec-8490-a32d585a2d41

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
**Gói vé: SVT – 1.200.000 đồng/người lớn**

**1. Tiền người lớn:**

5 × 1.200.000 = **6.000.000 đồng**

**2. Tiền trẻ em:**

- Trẻ 8 tuổi: 1.200.000 × 70% = 840.000 đồng.
- Trẻ 10 tuổi: 1.200.000 × 70% = 840.000 đồng.
- Bé 3 tuổi: Miễn phí = 0 đồng.

Tổng: 840.000 + 840.000 + 0 = **1.680.000 đồng**

**3. Tiền vé:**

6.000.000 + 1.680.000 = **7.680.000 đồng**

**4. Giảm giá nhóm:**

7.680.000 × 5% = **384.000 đồng**

**5. Phụ thu:**

1 × 300.000 = **300.000 đồng**

**6. Tổng tiền:**

7.680.000 − 384.000 + 300.000 = **7.596.000 đồng**

[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:** https://chatgpt.com/share/6b053567-8178-83ec-b569-186755dc8b66

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text

```

**Link trò chuyện:** 
## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí             | Điểm | Minh chứng                                                                                                                                                                                    | Đề xuất sửa                                                                                        |
| -------------------- | ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Đúng thông tin (50%) | 0/5  | Sai câu: “Vé Sân Vận Động bên em giá 1.000.000đ/người”. Sai giá vé SVT (đúng là 1.200.000đ). Sai câu: “Anh huỷ trước 3 ngày thì được hoàn tiền đầy đủ”. Hủy trước 3–6 ngày chỉ được hoàn 50%. | Sửa giá vé thành 1.200.000đ/người. Thông báo đúng mức hoàn tiền 50% khi hủy trước 3–6 ngày.        |
| Đầy đủ (30%)         | 1/3  | Chưa cung cấp đầy đủ chính sách hoàn tiền theo từng mốc thời gian.                                                                                                                            | Bổ sung: Hủy trước 7 ngày trở lên hoàn 100%; trước 3–6 ngày hoàn 50%; dưới 3 ngày không hoàn tiền. |
| Giọng điệu (20%)     | 2/2  | “Dạ chào anh ạ!”, “Anh cần gì cứ nhắn em nhé!” thể hiện thái độ thân thiện, lịch sự.                                                                                                          | Giữ nguyên giọng điệu thân thiện, chuyên nghiệp.                                                   |

**Tổng điểm: 3/10.**
```

**Link trò chuyện:** https://chatgpt.com/share/6b0535d6-70e4-83ec-8eeb-65fb365fa42e

