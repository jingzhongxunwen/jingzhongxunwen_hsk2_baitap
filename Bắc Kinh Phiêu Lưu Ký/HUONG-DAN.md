# Bắc Kinh Ký · HSK2 Bài 1

Game ôn bài “她请我们吃了北京烤鸭”, chuyển thể từ tài liệu 静中寻文 mà giáo viên cung cấp.

## Bản sửa lỗi chuyển câu · 07/10/2026

Đã sửa lỗi màn hình trống khi bấm **Thẻ tiếp theo** trong **Vali trí nhớ**, **Thám tử ngữ pháp** và **Đạo diễn hội thoại**. Đáp án, gợi ý, cụm đang ghép và kết quả cũ được xóa đồng thời khi chuyển sang thẻ mới; không cần tải lại trang giữa các câu. Giữ nguyên nội dung bài học, điểm hộ chiếu và cách lưu lịch ôn.

Để cập nhật GitHub Pages đang dùng: giải nén ZIP mới, tải các tệp bên trong lên đúng thư mục đang chứa `index.html` và ghi đè bản cũ, rồi **Commit changes**. Chờ GitHub Pages cập nhật xong. Nếu vẫn thấy bản cũ, tải lại trang bằng **Ctrl + Shift + R** (Windows) hoặc **Command + Shift + R** (Chrome/Edge trên Mac). Không cần xóa dữ liệu trình duyệt hay tạo repository mới.

Bản sửa đã tái hiện lỗi cũ và vượt qua 9 tình huống kiểm tra tương tác thành phần: hoàn thành liên tiếp 6 câu ở từng trò, câu sai/gợi ý/xem đáp án và ôn lại, ghép câu, lượt ôn trộn, đóng/mở lại và chơi lượt mới. Các kiểm tra chạy bằng React; chưa kiểm tra trực tiếp trong trình duyệt vì môi trường xem thử không khả dụng.

## Chơi ngay trên máy tính

Giải nén gói tải về, mở `index.html` bằng trình duyệt có hỗ trợ WebGL 2 (Chrome hoặc Edge hiện đại). Toàn bộ mã game, cảnh 3D và câu hỏi nằm trong tệp này; không cần cài ứng dụng. Nếu máy tắt tăng tốc đồ họa, bật lại trong cài đặt trình duyệt. Giọng đọc phụ thuộc vào giọng tiếng Trung đã có trên thiết bị.

1. Chọn nhân vật nam hoặc nữ và nhập tên/biệt danh.
2. Dùng WASD hoặc phím mũi tên. Có thể nhấp/chạm mặt đất hoặc chọn số trên bản đồ để tự đi tới.
3. Đến gần người ở điểm đánh số, nhấn E hoặc chạm nút trò chuyện.
4. Hoàn thành 4 câu ở mỗi điểm để nhận dấu hộ chiếu.
5. Mở Sổ tay để ôn từ vựng, mẫu câu; M để đổi góc nhìn toàn cảnh.

Trên điện thoại, mở game bằng đường dẫn đã đăng; giữ các nút điều hướng ở góc dưới bên trái. Bộ điều khiển hiển thị trên màn hình hẹp. Nên dùng trình duyệt trực tiếp thay cho cửa sổ xem trước tệp của ứng dụng chat.

## Gửi cho học sinh bằng GitHub Pages

Không cần đưa cả dự án lập trình lên GitHub. Chỉ đưa các tệp trong gói này lên kho lưu trữ.

1. Đăng nhập GitHub, tạo một repository tên ví dụ `bac-kinh-ky`. Với GitHub Free, chọn Public.
2. Chọn **Add file → Upload files**. Tải các tệp đã giải nén lên thư mục gốc, nhất là `index.html`, `.nojekyll` và `THIRD-PARTY-LICENSES.txt`. Không tải nguyên tệp ZIP thay cho nội dung bên trong. Chọn **Commit changes**.
3. Vào **Settings → Pages → Build and deployment**.
4. Chọn **Deploy from a branch**, nhánh **main**, thư mục **/(root)**, rồi **Save**.
5. Khi GitHub báo đã xuất bản, chọn **Visit site**. Sao chép đường dẫn đó gửi qua Zalo, nhóm lớp hoặc LMS. Học sinh chỉ mở link; không cần tài khoản GitHub để chơi.

Mẫu địa chỉ (không phải một link đã được xuất bản): `https://TEN-TAI-KHOAN.github.io/bac-kinh-ky/`.

Theo tài liệu GitHub được kiểm tra ngày 07/10/2026, website Pages tối đa 1 GB, băng thông mềm 100 GB/tháng. Bản game khoảng 1,11 MB trước nén, nhỏ hơn nhiều so với giới hạn. Ví dụ 100 học sinh tải toàn bộ một lần là khoảng 111 MB trước nén; băng thông thực tế còn phụ thuộc nén và bộ nhớ đệm.

Tài liệu chính thức:
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Nội dung học

| Điểm dừng | Cảnh và bài ôn |
|---|---|
| Sân bay | Gặp Vương Nhất Tuyết; 就、给、让、接; 吧 biểu thị phỏng đoán. |
| Chuyến xe vào phố | 次、旅游; 是……的 nhấn mạnh mục đích; phủ định 不是……的. |
| Cuộc gọi trong ngõ | Thiên Trung gọi nhờ giúp; 帮忙、不好意思、已经、那; nhấn mạnh thời gian; câu kiêm ngữ. |
| Quán vịt quay | 北京烤鸭、介绍; lời mời và câu chủ đề của bài. |
| Bưu thiếp khách sạn | 有时、懂、意思; nhắn tin báo đã tới Bắc Kinh và ôn tổng hợp. |

Có 20 câu: chọn đáp án, điền từ, ghép câu Việt–Trung và nhập bản dịch Việt–Trung. Mỗi câu đúng lần đầu được 10 điểm; sau khi thử sai rồi sửa đúng được 7 điểm. Xem gợi ý không trừ điểm. Ôn lại câu đã hoàn thành không cộng điểm trùng. Tối đa 200 điểm và 5 dấu.

Bài điền từ chấp nhận chữ Hán hoặc pinyin có/không dấu; bỏ qua khoảng trắng và dấu câu. Hai bài nhập câu dịch chấp nhận các mẫu câu và biến thể đã định sẵn theo bài học, không phải hệ thống AI chấm mọi cách diễn đạt. Ghép câu không cần bàn phím tiếng Trung. Sổ tay có đủ 14 từ mới, 北京烤鸭 và 3 điểm ngữ pháp.

## Mới: 3 trò Luyện sâu · 32 thẻ

Sau khi vào game, chọn **Luyện sâu** (biểu tượng tay cầm) ở góc trên bên phải. Nút này cũng xuất hiện trong màn hình hoàn thành hành trình.

- **Vali trí nhớ — 15 thẻ:** đọc tình huống tiếng Việt, tự nhớ từ hoặc cụm từ tiếng Trung. Nhập chữ Hán hoặc pinyin có/không dấu. Chưa có danh sách đáp án để đoán.
- **Thám tử ngữ pháp — 8 thẻ:** chọn chính xác cụm cần sửa, rồi nhập cụm thay thế. Các thẻ luyện 吧, phủ định và nhấn mạnh với 是……的, cách dùng 请, 给, 帮个忙, 介绍 và 已经……了.
- **Đạo diễn hội thoại — 9 thẻ:** trả lời nhân vật trong một tình huống mới. Đổi thời gian, mục đích, người yêu cầu hoặc hành động. Có thể tự nhập chữ Hán/pinyin hoặc mở các cụm từ để ghép khi cần trợ giúp.

Mỗi lượt chọn tối đa 6 thẻ chính; ưu tiên thẻ đến hạn và ít mốc ghi nhớ. Sai, chưa nhớ hoặc cần gợi ý thì thẻ được chèn lại sau tối đa 3 thẻ khác, hoặc ở cuối lượt. Mỗi thẻ chỉ lặp lại một lần trong lượt, nên một lượt 6 thẻ có tối đa 12 lần trả lời. Nút **Chưa nhớ** cho phép xem đáp án rồi luyện lại; không buộc học sinh đoán bừa để được đi tiếp.

Cơ chế mốc ghi nhớ:

1. Tự trả lời đúng khi đến hạn, không gợi ý và không phải lượt sửa lại, được ghi nhận một mốc.
2. Lần tự nhớ đầu tiên hẹn sau 1 ngày, lần thứ hai sau 3 ngày, từ lần thứ ba hẹn sau 7 ngày.
3. Trả lời sai đưa mốc về 0 và hẹn sau 10 phút. Cần gợi ý cũng hẹn lại sớm trong 10 phút.
4. Đúng ở lượt sửa lại hoặc luyện trước hạn không tăng mốc. Việc này tránh tính việc vừa xem đáp án là nhớ độc lập.
5. **Ôn chỗ hay quên** trộn các thẻ đang có 0 mốc; có thể luyện ngay nhưng cần đến hạn mới tăng mốc. Lịch ôn chỉ hiện khi mở game, không có thông báo tự động.

Các mốc là quy tắc theo dõi việc luyện trong game, không phải đánh giá chuẩn hóa năng lực ngôn ngữ. Bài tự nhập được đối chiếu với mẫu và các biến thể đã định sẵn; không phải AI hiểu mọi cách diễn đạt đúng. Khi dùng các cụm từ trợ giúp, câu đúng vẫn được ghi nhận là đã luyện, nhưng không tăng mốc tự nhớ.

Tiến trình luyện sâu lưu riêng theo tên/biệt danh trên trình duyệt này, không đổi 200 điểm hộ chiếu và 20 câu của chuyến đi. Chọn cùng tên sẽ thấy lại lịch ôn; đổi tên dùng một lịch khác. Tạo chuyến đi mới không xóa lịch ôn đã lưu của tên đó.

## Lưu tiến trình và giới hạn

- Tên/biệt danh và tiến trình chỉ được lưu bằng bộ nhớ trình duyệt trên thiết bị đang chơi. Không có máy chủ lưu điểm, bảng xếp hạng hay chức năng nộp bài cho giáo viên.
- Khác trình duyệt, khác đường dẫn, chế độ riêng tư hoặc xóa dữ liệu có thể mất tiến trình. Khi mở file trực tiếp, cách lưu phụ thuộc trình duyệt; đường dẫn GitHub Pages ổn định phù hợp hơn cho lớp học.
- Có thể yêu cầu học sinh chụp màn hình kết quả gửi lại khi kết thúc.
- Bản đồ thu nhỏ được sáng tạo theo bối cảnh Bắc Kinh, không phải bản đồ thật. Một số cảnh được chuyển từ xe sang ngõ/quán để tạo hành trình chơi.
- Tệp nguồn chỉ kèm tham chiếu các audio và ảnh, không có các tệp đó. Game dùng mô hình 3D tạo bằng mã và giọng đọc tổng hợp của thiết bị khi khả dụng; không sử dụng audio gốc giáo trình.
- Đã kiểm tra đóng gói, cú pháp/kiểu dữ liệu, 20 câu và đáp án, hiển thị HTML ban đầu, mô hình hình học và đường tự đi đến 5 điểm. Bản cập nhật kiểm tra thêm 32 thẻ, định vị lỗi, đáp án/pinyin/biến thể, hàng đợi ôn lại hữu hạn, lịch 10 phút và 1/3/7 ngày, cùng bảo vệ không tăng mốc khi luyện sớm hoặc dùng gợi ý. Môi trường xem thử trực tiếp không khả dụng, nên chưa xác nhận hình ảnh WebGL và thao tác trên điện thoại/trình duyệt thực. Giáo viên nên thử một lượt trên thiết bị của lớp trước khi giao bài.

## Thay đổi bài học

Mã nguồn chỉnh sửa được giữ cùng bản Site trong cuộc trò chuyện này. Các câu hỏi hành trình tập trung ở `lib/lesson.ts`, thẻ và quy tắc luyện sâu ở `lib/practice.ts`; không chỉnh tay mã đã nén trong `index.html`. Khi cần thay câu hỏi, thêm bài hoặc cải tiến nhân vật, gửi yêu cầu trong cuộc trò chuyện để xuất bản cập nhật.

Các thư viện trong gói có thông báo bản quyền tại `THIRD-PARTY-LICENSES.txt`.
