Phát triển Phần mềm quản lý - Nhóm 01

1. Môi trường lập trình
    - C#, .Net, MVC
    - Visual Studio Code/Visual Studio (C# Dev Kit, C#, IntelliCode for C# Dev Kit...)
    - Git + Github (git add, git commit, git push, git pull, git branch...)
2. Nội dung học
   - Phát triển ứng dụng quản lý trên .net MVC
   - Tìm hiểu mô hình MVC, Cách thức hoạt động của Model, View, Controller
   - Nắm được cách gửi nhận dữ liệu giữa Model, View, Controller
   - Kế thừa... => Đủ điều kiện đạt
   - Làm việc với Excel, phân trang dữ liệu
   - Authentication và Authorization
   - HTML, CSS (W3.css/Bootstrap)
   - C# Code First, Entity Framework
3. Đánh giá kết quả học phần
   - Thi điểm A: Vấn đáp
   - Điểm B: Dựa vào điểm thi + Bài thực hành + Bài kiểm tra
   - Điểm C: Điểm danh + Làm bài thực hành
4. Bai thực hành số 1:
   - Cài đặt môi trường lập trình
   - Tạo project DemoMVC: dotnet new mvc -o DemoMVC
   - Tại repository trên github và đẩy code lên github
   - Chèn link repository vào link thông tin môn học
5. Bài học ngày 01/07/2025
   - Tạo project net mvc: dotnet new mvc -o PROJECT_NAME
   - Chạy và build project: dotnet watch run (chạy ứng dụng) và dotnet build (build ứng dụng xem có lỗi hay không)
   - Khi chạy project mà gặp lỗi "Could not find a MSBuild project file in" => sai gốc thư mục chứa project => cd tới thư mục gốc chứa project
   - Gửi dữ liệu từ view lên controller => thực hiện submit form
   - Controller nhận được dữ liệu từ view gửi lên: [HttpPost] và parameter (trùng tên với thẻ input trên view)
   - Gửi dữ liệu từ controller về view: ViewBag/ViewData/ViewTemplate
6. 