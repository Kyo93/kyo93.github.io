---
layout: post
title: Github và GitLab là gì
subtitle: Kiến thức cần thiết cho dev
gh-badge: [star, fork, follow]
tags: [Blog for Dev]
comments: true
---

## Github, Gitlab là gì

Bài này mình viết dành cho các bạn sinh viên đang học các ngành công nghệ, thông tin, data, anh em thấy thiếu gì thì bổ sung giúp mình nhé. Về cơ bản, GitHub và GitLab, hay Git nói chung, là một hệ thống để lưu trữ và theo dõi thay đổi với mã nguồn của bạn. Mã nguồn đó có thể thuộc bất kì ngôn ngữ lập trình nào cũng được. Ngoài Git còn có một số hệ thống tương tự nhưng mình sẽ tập trung Git và GitHub / GitLab vì đây là những thứ phổ biến nhất.

Trước tiên, chúng ta hãy tìm hiểu về Git trước. Với các loại file thông thường, khi bạn mở nó ra và chỉnh sửa, nội dung cũ của file chắc chắn sẽ mất đi và để khôi phục lại nó cực kì vất vả (không phải không làm được, nhưng tốn nhiều thời gian, công sức). Rồi giả sử bạn muốn tìm lại xem file đó như thế nào vào ngày 1/1/2019 thì sao, tức tận 1 năm về trước?  

Trước tiên, chúng ta hãy tìm hiểu về Git trước. Với các loại file thông thường, khi bạn mở nó ra và chỉnh sửa, nội dung cũ của file chắc chắn sẽ mất đi và để khôi phục lại nó cực kì vất vả (không phải không làm được, nhưng tốn nhiều thời gian, công sức). Rồi giả sử bạn muốn tìm lại xem file đó như thế nào vào ngày 1/1/2019 thì sao, tức tận 1 năm về trước?

Chưa hết, bạn còn muốn biết rằng file này do ai chỉnh sửa, sửa dòng nào, sửa từ cái gì thành cái gì... Những thứ này thì tính năng sao lưu mặc định của macOS và Windows không làm được, vì đơn giản chúng không phải được xây dựng nên để dành cho mục đích phát triển phần mềm. Máy tính cá nhân của bạn thì chỉ 1 mình bạn dùng, nhưng 1 dự án phần mềm có nhiều người, thậm chí cả trăm người, cùng tham gia phát triển là chuyện bình thường. Chưa kể có nhiều thứ mà người này phải vào chỉnh sửa code của người kia nữa, mọi thứ sẽ rối rắm hơn khi có nhiều bên cùng tham gia.

![Github vs Gitlab](https://kyo93.github.io\assets\img\4890110_github_pull.jpg){: .mx-auto.d-block :}

Để giải quyết vấn đề này, người ta dùng Git. Git sẽ thay dõi thay đổi của file trong dự án của bạn, bạn có thể biết được ai sửa dòng nào vào lúc nào, dòng code mới thêm vào là phục vụ cho chức năng gì. Git còn hỗ trợ tách nhánh (branch) để khi người ta phát triển các chức năng khác nhau thì không bị xung đột với nhau. Mấy cái chi tiết kĩ thuật này anh em tìm hiểu thêm ở các blog về Git nhé, ở Tinh tế mình chỉ giới thiệu chung chức năng thôi.

Ở tất cả các công ty mình từng dùng qua, người ta đều xài Git. Bạn có thể tự duy trì dịch vụ Git của riêng mình, khi đó bạn phải có server, ổ lưu trữ, phải tự làm nhiều thứ. Còn không thì bạn có thể dùng GitHub hoặc GitLab, hai dịch vụ Git online. Bạn có thể lưu trữ code của mình lên GitHub hoặc GitLab và không còn lo về chuyện mất code nữa (giống như việc bạn up file lên Google Drive hay iCloud thì lỡ máy tính có hỏng cũng không lo mất file). Server, ổ đĩa lưu trữ, vận hành, sao lưu... đều có GitHub và GitLab lo.

Hai dịch vụ này cũng cung cấp một giao diện web để bạn xem code hiện tại của mình, xem lại những chỉnh sửa với file, xem lại các lần chỉnh sửa để ra mắt phần mềm... Với các dự án mã nguồn mở, một người nào đấy ở bất kì nơi nào trên thế giới có thể đóng góp tính năng, giúp sửa lỗi vào dự án của bạn. Họ có thể upload code mới lên, bạn sẽ nhận được thông báo, bạn có thể kiểm tra xem code này chạy đúng hay không, rồi chấp nhận đưa code đó vào dự án chính... Những thứ này nếu xài chỉ dùng Git truyền thống thì cực hơn, nếu không có GitHub thì bạn phải tự download mã nguồn về, chỉnh sửa, gửi email qua lại cho chủ nhân của dự án, rồi sau đó lại trộn code với nhau. Cơ bản là cực lắm.

![App pull](https://kyo93.github.io\assets\img\4890121_git_hub_app.jpg){: .mx-auto.d-block :}