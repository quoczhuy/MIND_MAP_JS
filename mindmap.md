Hệ thống kiến thức MindMap

Tổng hợp Sơ đồ Tư duy Cấu trúc Dữ liệu Mảng Array JavaScript
1. Mục tiêu
Hệ thống hóa toàn diện kiến thức về Cấu trúc dữ liệu Mảng (Array) trong JavaScript: Khái niệm, chỉ số (0..length-1), thuộc tính .length, các nhóm phương thức CRUD cơ bản và cơ chế bộ nhớ tham chiếu.
Xây dựng sơ đồ tư duy (Mindmap) súc tích, phục vụ tra cứu nhanh khi phát triển phần mềm.
Nắm vững các cạm bẫy thường gặp (lỗi lệch chỉ số <= length gây NaN, dùng nhầm pop thay vì shift trong hàng đợi FIFO).
2. Ngữ cảnh & Bài toán
Sau khi học xong mảng, học viên cần tổng hợp kiến thức thành sơ đồ tư duy Markmap/Mermaid, tóm tắt các nguyên lý cốt lõi, cú pháp các phương thức mảng và ứng dụng thực tế (như bài toán quản lý hàng đợi trạm sạc VinFast).

3. Quy tắc nghiệp vụ
Sơ đồ tư duy phải bao quát 5 nhánh kiến thức trọng tâm:

Tổng quan về Mảng: Định nghĩa mảng, chỉ số 0-indexed, thuộc tính .length, mảng chứa đa kiểu dữ liệu.
Nhóm phương thức thêm/xóa ở 2 đầu: Thêm cuối push(), xóa cuối pop(), thêm đầu unshift(), xóa đầu shift().
Nhóm thao tác ở vị trí bất kỳ: splice(start, deleteCount, items...) (sửa mảng gốc), slice(start, end) (sao chép mảng con).
Nhóm tìm kiếm & kiểm tra: indexOf(), lastIndexOf(), includes().
Cơ chế bộ nhớ & Lỗi thường gặp: Pass-by-reference, kỹ thuật sao chép mảng [...arr], lỗi vượt chỉ số i <= length.
4. Yêu cầu kỹ thuật
Định dạng danh sách Markdown tương thích Markmap hoặc biểu đồ Mermaid.
Mỗi nhánh lá ngắn gọn dưới 15 từ, tập trung vào từ khóa chuyên môn kỹ thuật cốt lõi.
Tuyệt đối không biến sơ đồ tư duy thành bài đọc lý thuyết dài dòng.
5. Quy định nộp bài
Đặt tên file: mindmap_session07.md.