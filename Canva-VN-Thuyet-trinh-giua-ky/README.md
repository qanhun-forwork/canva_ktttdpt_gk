# Canva — Đã có mặt tại Việt Nam · Bộ thuyết trình giữa kỳ

## 1. Cách trình chiếu

1. Giải nén cả thư mục, **giữ nguyên cấu trúc** (`index.html` cần các thư mục `media/` và `img/` nằm cạnh nó).
2. Mở `index.html` bằng **Chrome hoặc Edge** (không cần mạng, font đã nhúng sẵn).
3. Bấm **F** để toàn màn hình, **S** để mở cửa sổ ghi chú người nói kèm đồng hồ đếm giờ (kéo cửa sổ này sang màn hình laptop khi chiếu).

| Phím | Tác dụng |
|---|---|
| → / Space / click | Slide tiếp theo (mỗi slide tự hiện toàn bộ nội dung, chỉ cần nhấn 1 lần) |
| ← | Slide trước |
| F | Toàn màn hình |
| S | Ghi chú người nói + đồng hồ (vàng sau 22 phút, đỏ sau 25 phút) |
| B | Màn hình đen |
| số + Enter | Nhảy tới slide (ví dụ `17` Enter = slide video) |
| H | Hiện bảng phím tắt |
| **Slide video (17):** K / R / M | Phát–tạm dừng / phát lại từ đầu / tắt–bật tiếng |

- Slide 17 tự phát **cả hai video cùng lúc** sau ~1 giây. Âm thanh lấy từ bản 9:16; bản 16:9 tắt tiếng để không bị vọng, và tự bám nhịp theo bản 9:16.
- Nếu trình duyệt chặn tự phát, trên video sẽ hiện nút ▶: bấm vào là chạy.
- Kiểm tra loa và âm lượng trước giờ thi. Hai video 1080p/60fps chạy cùng lúc cần máy có giải mã phần cứng (hầu hết laptop từ 2018 trở lên đều ổn).
- `Canva-VN-Thuyet-trinh-giua-ky.pdf` là bản PDF 25 trang (chụp từng slide ở độ phân giải 3840 × 2160, giữ nguyên màu gradient và hiệu ứng ánh sáng; video hiển thị bằng khung hình tĩnh). Dùng để nộp bài hoặc làm bản dự phòng nếu máy chiếu không mở được HTML.

## 2. Cấu trúc 25 slide (≤ 25 phút)

| # | Slide | Thời lượng |
|---|---|---|
| 1–2 | Bìa · Lộ trình 4 phần | ~1′ |
| 3–5 | **01 Bối cảnh:** Canva tại Việt Nam 2026 · Bốn điểm chưa tốt | ~3′ |
| 6–8 | **02 Giải pháp:** Vấn đề cốt lõi & mục tiêu · Ý tưởng chiến dịch | ~3′ |
| 9–15 | **03 Bộ Banner:** Tổng quan · Vuông trên Feed · Kiểm tra 3 giây · Story · Cover desktop/mobile · Header web | ~9′ |
| 16–22 | **04 Short Video:** Chiếu song song 9:16 + 16:9 · Cấu trúc Hook–Thân–Kết · Dựng theo nhạc · Chữ & phụ đề · Nhận diện & thông số · **Kiểm chứng thực tế trên Threads** | ~9′ |
| 23–25 | Tổng kết · Cảm ơn & hỏi đáp · Nguồn | ~1′ + hỏi đáp |

## 3. Slide 22: kết quả thực tế trên Threads

Số liệu lấy từ mục **Thông tin chi tiết** của bài [threads.com/@qanhun/post/De_Dyr4Exnd](https://www.threads.com/@qanhun/post/De_Dyr4Exnd), ghi lúc 16:50 ngày 28/10/2026 (bài đăng lúc 12:01 ngày 27/10/2026, tức sau khoảng 29 giờ):

| Chỉ số | Giá trị |
|---|---|
| Lượt xem | 32,6K (97,01% từ bảng feed Trang chủ, 2,07% Khác, 0,55% Instagram, 0,24% Trang cá nhân, 0,13% Tab Hoạt động) |
| Lượt tương tác (theo Threads) | 974 = 826 thích + 118 đăng lại + 28 trả lời + 2 trích dẫn |
| Lượt chia sẻ | 222 |
| Theo dõi mới từ bài | 7 |
| Tỉ lệ tương tác | 974 ÷ 32.600 ≈ 3,0% |
| So với mặt bằng (Buffer, 1,7 triệu bài, đầu 2025) | Trung vị 5, trung bình 58 lượt tương tác mỗi bài → bài của nhóm gấp ~195 lần trung vị, ~17 lần trung bình |

Ảnh chụp dùng trong slide: `img/threads-post.jpg` (bài đăng) và `img/threads-comments.jpg` (bình luận, đã làm mờ tên và ảnh đại diện của người bình luận khác). Ảnh gốc của mục Thông tin chi tiết: `img/threads-insights-views.jpg`, `img/threads-insights-interactions.jpg`.

Số liệu sẽ còn tăng; nếu muốn cập nhật trước buổi thi, gửi số mới để xuất lại slide.

## 4. Thông số bàn giao bộ banner (handoff)

Thư mục `banners/` chứa file PNG xuất đúng kích thước; `banner-src/banner.html` là file nguồn (mở bằng `?v=square|story|cover|web`, thêm `&guides` để thấy vùng an toàn).

| File | Kích thước | Nền tảng | Vùng an toàn đã áp dụng |
|---|---|---|---|
| `banner-vuong-1x1-1200x1200.png` | 1200 × 1200 | Post Facebook / Instagram | Lề 90–96 px; đường mắt Logo → Headline → Sản phẩm → CTA |
| `banner-story-9x16-1080x1920.png` | 1080 × 1920 | Story FB / IG / Zalo | Trống 250 px trên + 250 px dưới; nội dung nằm trong y = 286 → 1660 |
| `banner-cover-facebook-1640x624.png` | 1640 × 624 (@2x của 820 × 312) | Ảnh bìa Fanpage | Chữ trong vùng giữa ~1100 px (≈ 550 px @1x, chặt hơn 640 × 312); nửa dưới bên trái để trống cho ảnh đại diện |
| `banner-header-web-1920x600.png` | 1920 × 600 (16:5) | Header website | Khối chữ trong khung nội dung 1440 px, căn từ x = 240 |

**Design tokens**

| Token | Giá trị | Dùng cho |
|---|---|---|
| `color-night` | #0B0920 | Nền |
| `color-turq` / `color-blue` / `color-purple` | #00C4CC / #5A32FA / #7D2AE8 | Gradient nhận diện, chữ nhấn |
| `color-yellow` | #FFD400 | Chỉ dùng cho ưu đãi (“Miễn phí 30 ngày”) |
| `gradient-cta` | 100° #0B93B8 → #5A32FA 52% → #8E3BF0 | Nút “Thử ngay hôm nay” |
| `font-display` | Inter Display 900 / 800 | Headline “VIỆT NAM”, tagline, CTA |
| `font-text` | Inter 500–700 | Dòng dẫn, nhãn |
| `font-accent` | Lora Italic 600 | Mẫu chữ “Xin chào Việt Nam” |
| Headline | 178 px (vuông) · 206 px (story) · 150 px (cover) · 136 px (web), line-height 1.06 | Chừa chỗ cho dấu mũ và dấu nặng tiếng Việt |

**Thành phần lặp lại:** logo tròn (cắt từ end card video) · huy hiệu “Chính thức ra mắt · 2026” · thẻ editor “Xin chào Việt Nam” có khung chọn · ô chữ có dấu Ă Đ Ơ Ư · thanh Canva AI “Thiết kế poster quảng cáo cho quán trà sữa” · thẻ ưu đãi Pro 30 ngày · nút CTA gradient.

**Độ tương phản (WCAG):** chữ trắng/nền đêm 17,0:1 · vàng/nền đêm 11,9:1 · chữ trắng/nút CTA ≥ 3,6:1 (đạt chuẩn chữ lớn ≥ 3:1).

## 5. Phương án chữ (UX copy) đã cân nhắc

| Vị trí | An toàn | Trực diện (đã chọn) | Phá cách |
|---|---|---|---|
| Headline | Canva đã chính thức có mặt tại Việt Nam | **đã chính thức có mặt tại / VIỆT NAM** | Canva về nhà rồi! |
| Tagline | Thiết kế dễ dàng bằng tiếng Việt | **Thiết kế tiếng Việt, chuẩn từng dấu.** | Đủ dấu. Đủ đẹp. Đủ Việt. |
| CTA | Dùng thử miễn phí | **Thử ngay hôm nay** | Mở Canva, gõ ý tưởng |

- Headline lặp đúng câu chốt của video để người xem nhận ra ngay khi gặp lại trên Feed/Story. Rủi ro: dài, nên tách hai tầng chữ (dòng dẫn nhỏ + “VIỆT NAM” cực lớn).
- “Chuẩn từng dấu” đáp thẳng lỗi “Mai An Tiem” của lễ ra mắt. Rủi ro: là một lời hứa, nên mọi chữ trong bộ ấn phẩm phải đúng dấu tuyệt đối.
- CTA giữ nguyên câu kết của video để thống nhất hành trình. Rủi ro: không nêu ưu đãi, nên đặt thẻ “Dùng thử Canva Pro miễn phí 30 ngày” ngay cạnh.

## 6. Nhật ký rà soát thiết kế (design critique)

| Phát hiện | Mức | Đã xử lý |
|---|---|---|
| Chữ trắng trên đầu nút CTA (#00C4CC) chỉ đạt 2,2:1 | Nghiêm trọng | Đổi điểm đầu gradient sang #0B93B8 → ≥ 3,6:1 |
| Cover: nút CTA ở giữa-dưới bị ảnh đại diện che trên điện thoại | Nghiêm trọng | Bỏ CTA khỏi cover (dùng nút “Thử ngay” của Fanpage), đưa cụm chữ lên cao |
| Dấu nặng của “Ệ” chạm dòng “NAM” khi line-height 0.9 | Vừa | Tăng line-height lên 1.06 ở mọi kích thước |
| Thẻ ưu đãi bị xuống dòng ở banner vuông | Nhẹ | Nới rộng thẻ, giảm cỡ dòng thanh toán |
| Story: dòng tagline chạm đáy thẻ editor | Nhẹ | Dời tagline, thẻ ưu đãi, CTA xuống; CTA kết thúc ở y = 1628 |
| Chữ tô gradient trong slide bị cắt chân: dấu nặng dưới “Việt”, đuôi g/p, dấu chấm của “!” | Nghiêm trọng | Nới vùng tô màu xuống dưới chân chữ; kiểm tra lại toàn bộ tiêu đề |

Lưu ý còn lại: video hiện có logo ở 3 điểm chạm (0:01, 0:03–0:06, 0:26–0:30), chưa có watermark cố định suốt 30 giây như đề gợi ý.

## 7. Nguồn dữ liệu

Báo cáo nghiên cứu đầy đủ (có link từng nguồn): `Canva Việt Nam năm 2026.md`. Thông số video (1080 × 1920, 60 fps, 30,0 s, 0 px viền đen) đo trực tiếp bằng ffprobe/ffmpeg; nhịp ~129 BPM và 12 điểm chuyển cảnh đo từ file âm thanh của video.
