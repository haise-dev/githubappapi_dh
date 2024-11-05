Tôi đã làm gì: 
- Những thứ tôi đã sửa: local.properties và gradle.properties để thay API Token của riêng mình ( bạn cũng nên dùng của bạn đề phòng cái cảu tôi hết hạ)
cách lấy Personal token access trong file readme mới nhất của hải tô

- tôi sửa build.gradle.kts (Module :app) thêm khá nhiều dêpndencies để fetch dc các thông tin khác từ acc github
- tôi cũng sử strings.xml để thêm các string lấy từ thông tin trên github cho nó hiện trên app mình

- tôi cũng sửa AndroidManifest.xml cho các thứ tự các Activity để cái LoginActivity xuất hiện dầu tiên để đăng nhập
- trong cái package api tôi có thêm 3 cái class trong package model là chức năng
 
LƯU Ý: tôi đã chuyển cái ApiClient ở bên ngoài vào package api đấy cho nó ở cùng với GitHubService không thì dell chạy dc 
LƯU Ý 2: cái lib.verions.toml cũng sửa cái agp ở line 2 thành phiên bản phù hợp ( cảu hải tô phiên bản 8.7.2 dell chạy dc )
 

cái package ui.login để chứa LoginActivity thôi, Còn cái ProfileActivity để ngoài 
lưu ý là cái ProfileActivity chưa nối vào đâu cả nên muốn test thì chạy riêng mới thấy
-layout của 2 cái activity tôi làm thì nhìn laf biết 
- à t cũng có sửa cái nav_header_main.xml theo í hải luôn để hiện thông tin và ảnh mình ngoài homepage 

