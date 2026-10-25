# AI English Writing Tool - Manual Testing Project

## Giới thiệu

Đây là dự án **Manual Testing** cho website **AI-Based English Grammar and Writing Improvement Tool** - công cụ hỗ trợ kiểm tra ngữ pháp, viết lại câu bằng AI và tra cứu từ vựng tiếng Anh. Dự án bao gồm phân tích yêu cầu, lập kế hoạch, thiết kế và thực thi test case, ghi nhận lỗi và báo cáo kết quả.

**Thông tin hệ thống được kiểm thử**

| Thành phần | Công nghệ |
|---|---|
| Frontend | React + TypeScript |
| Backend | Flask |
| AI service | FastAPI (mô hình T5), Groq `llama-3.3-70b-versatile` |
| Tra từ điển | Free Dictionary API |

## Mục tiêu dự án

- Phân tích yêu cầu của hệ thống.
- Thiết kế bộ Test Case cho các chức năng chính.
- Thực hiện Manual Testing và ghi nhận lỗi.
- Nâng cao kỹ năng viết test case, phân loại lỗi và báo cáo kết quả.

## Các chức năng được kiểm thử

| Module | Chức năng |
|---|---|
| **Text Input** | Nhập văn bản, Paste, Sample Text, Clear All, Import File, giao diện và bộ đếm từ |
| **Grammar Check** | Phát hiện và sửa lỗi ngữ pháp, hiển thị kết quả, Export, xử lý lỗi API |
| **AI Rewrite** | Viết lại câu bằng AI, hiển thị Improved Version, Improvements, Summary, Listen, xử lý lỗi API |
| **Vocab Lookup** | Tra cứu nghĩa, phiên âm IPA, từ loại, popup tra cứu, gợi ý cách dùng bằng AI, xử lý lỗi API |

## Công việc thực hiện

- Phân tích yêu cầu và xác định phạm vi kiểm thử.
- Lập Test Plan.
- Thiết kế Test Design theo từng module và nhóm chức năng.
- Viết Test Case.
- Thực thi test case, ghi nhận kết quả và ngày thực hiện.
- Báo cáo lỗi (Bug Report) kèm mức độ nghiêm trọng và độ ưu tiên.
- Lập Test Checklist trước khi phát hành và Test Summary Report.

## Tài liệu kiểm thử

| Tài liệu | Nội dung |
|---|---|
| `TEST_PLAN` | Phạm vi, chiến lược, môi trường, tiêu chí kết thúc, rủi ro, kết quả kiểm thử |
| `TEST_CASE.xlsx` | Gồm các sheet: Test Case List, Test Design, 4 sheet module (Text Input, Grammar Check, AI Rewrite, Vocab Lookup) và Test Report |
| `TEST_CHECKLIST.xlsx` | Danh sách kiểm tra theo chức năng và các điều kiện trước khi phát hành |
| `BUG_REPORT.xlsx` | Danh sách lỗi: mô tả, bước tái hiện, mức độ nghiêm trọng, độ ưu tiên |
| `TEST_SUMMARY_REPORT.xlsx` | Tổng hợp kết quả theo module, theo mức ưu tiên và đánh giá theo tiêu chí kết thúc |

## Kết quả

- Thiết kế và thực hiện **109 Test Case** cho **4 module** chức năng.
- Hoàn thành đầy đủ bộ tài liệu kiểm thử (Test Plan, Test Design, Test Case, Test Checklist, Bug Report, Test Summary Report).
- Ghi nhận **3 Defect** trong quá trình kiểm thử (2 Major, 1 Minor), tiêu biểu:
  - Ô nhập văn bản nhận nội dung vượt quá giới hạn 2000 ký tự.
  - Khi từ có nhiều từ loại, popup tra cứu chỉ hiển thị từ loại đầu tiên.
- Đạt **97.25% Pass Rate** (106/109 Test Case đạt, 3 Failed, 0 Untested).

| Module | Tổng | Passed | Failed |
|---|---|---|---|
| Text Input | 37 | 36 | 1 |
| Grammar Check | 23 | 23 | 0 |
| AI Rewrite | 23 | 23 | 0 |
| Vocab Lookup | 26 | 24 | 2 |
| **Tổng** | **109** | **106** | **3** |


## Tác giả

**Nguyễn Thanh Thủy** - Tester
