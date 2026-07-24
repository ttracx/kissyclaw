# THOX GitHub Agent Team (trang cầu nối)

Xem [tài liệu nguồn tiếng Anh](../../thox-agent-team.md) để đọc đặc tả đầy đủ.

## Review coverage

Quy trình bao phủ issue, bình luận issue, pull request, kiểm tra thủ công và xác thực chính sách hằng ngày.

## Safe merge gates

Chỉ merge khi mọi kiểm tra bắt buộc thành công, bảo vệ nhánh cho phép, PR không còn là bản nháp, head SHA khớp và thay đổi nhạy cảm đã được con người xem xét.

## Branch pruning

Chỉ xóa nhánh tính năng đã merge trong cùng kho, không phải nhánh mặc định hoặc được bảo vệ, và không còn được PR mở khác tham chiếu.
