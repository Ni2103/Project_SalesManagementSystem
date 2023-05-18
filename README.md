# Project_SalesManagementSystem
### Đề tài “Xây dựng hệ thống bán hàng tại GS25” hướng đến các mục tiêu cơ bản sau:
-	Bài toán đặt ra với mục đích xây dựng hệ thống quản lý bán hàng có hiệu quả, tăng khả năng xử lý, đáp ứng yêu cầu thông tin đưa ra có tính chính xác, an toàn bảo mật, kịp thời và tiết kiệm được thời gian cho cửa hàng.
-	Hệ thống hóa các kiến thức cơ sở làm nền tảng cho việc thực hiện đề tài.
-	Hiểu rõ được quy trình nghiệp vụ của hệ thống bán hàng.
-	Hiểu rõ các mô hình xử lý, mô hình dữ liệu, áp dụng được các công cụ để thiết kế các mô hình, đánh giá và tạo ra một phần mềm hỗ trợ quản lý bán hàng tối ưu phù hợp với quy trình bán hàng đề tài.
-	Xây dựng mô hình dòng dữ liệu thể hiện rõ từng chức năng của hệ thống quản lý bán hàng.
-	Xây dựng mô hình thực thể quản lý bán hàng.
-	Thiết kế các form giao diện cho hệ thống bán hàng.
-	Hệ thống thống kê được doanh thu và tiến hành báo cáo.
-	Trình bày các nội dung mang tính giải pháp trong thiết kế để hoàn thiện hệ thống quản lý trên cơ sở ứng dụng mạnh mẽ công nghệ thông tin và mạng truyền thông.
-	Đưa ra một số khuyến nghị để hoàn thiện hơn cho đề tài.
# QUY TRÌNH NGHIỆP VỤ
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/f3190a07-7371-4b5f-93f8-3aff185e2782)
####  (1) Khách hàng sẽ đến cửa hàng GS25 ở bất kì chi nhánh nào khi có nhu cầu mua hàng. Khách hàng tìm kiếm sản phẩm cần mua, các sản phẩm được trưng bày theo nhóm sản phẩm, khách hàng có thể dễ dàng lựa chọn theo nhu cầu.
####  (2) Sau khi khách hàng đã tìm kiếm được các sản phẩm cần mua thì nhân viên bán hàng sẽ tiến hành xử lý yêu cầu mua hàng của khách hàng.
####  (3) Nhân viên nhập thông tin, số lượng các sản phẩm để hệ thống cập nhật số tiền thanh toán. Căn cứ vào thông tin, số lượng các sản phẩm cần mua của khách hàng thì tiến hành in hóa đơn.
####  (4) Hóa đơn sẽ được chuyển đến cho khách hàng để tiến hành thanh toán hóa đơn. Khách hàng có 2 sự lựa chọn. Thanh toán trực tiếp bằng tiền mặt và thanh toán trực tuyến qua ví điện tử hoặc thanh toán bằng thẻ ngân hàng.
####  (5) Sau khi in hóa đơn số lượng tồn của sản phẩm sẽ được cập nhật lại và quản lý bởi người quản lý.
####  (6) Sau khi số lượng tồn được cập nhật, nếu các sản phẩm có số lượng tồn dưới mức cho phép thì người quản lý sẽ gửi yêu cầu bổ sung đến kho. 
####  (7) Nhân viên kho sẽ tiến hành kiểm tra đối chứng số lượng tồn kho. Nếu số lượng tồn đáp ứng đủ yêu cầu từ cửa hàng thì sẽ tiến hành xuất sản phẩm đến cửa hàng.
####  (8) Nếu số lượng không đủ yêu cầu để xuất thì nhân viên kho sẽ tiến hành lên kế hoạch tiến hành nhập sản phẩm từ nhà cung cấp.
## Sơ đồ phân cấp chức năng (BFD)
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/2ac6dae9-0f52-4db4-9684-c5a806b111a0)
### Mô hình dòng dữ liệu
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/2cc1eac3-1af4-4e14-8735-819373383840)
### DFD mức 0 hệ thống quản lý bán hàng
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/cb0865a3-2a0f-45bc-9705-75fc6c7101f9)
### DFD mức 1 giao dịch
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/079158c5-6d40-4182-8ebe-3d9fe3b078f2)
### DFD mức 1 điều phối kho 
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/ead8ef23-cb5f-498b-934f-c29306c8e92a)
### DFD mức 1 Thống kê
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/6083c611-41b9-4fb2-9563-2055b7f697bf)

## Mô hình thực thể kết hợp ERD
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/50fbc293-acbe-4307-826b-143c2ad3ab40)
#### Mô hình quan hệ dữ liệu 
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/79841ede-f0ac-4b34-95cf-2ff8ece87475)
##### -	Một nhân viên có thể lập nhiều hóa đơn, một hóa đơn chỉ do một nhân viên lập.
##### -	Một nhân viên có thể lập nhiều phiếu nhập kho, một phiếu nhập kho chỉ do một nhân viên lập
##### -	Một nhân viên có thể lập nhiều phiếu xuất kho, một phiếu xuất kho chỉ do một nhân viên lập.
##### -	Một loại sản phẩm sẽ có nhiều sản phẩm, một sản phẩm chỉ thuộc một loại sản phẩm nhất định.
##### -	Một khách hàng có thể có nhiều hóa đơn, một đơn hàng chỉ thuộc về một khách hàng.
##### -	Một nhà cung cấp có thể cung cấp nhiều sản phẩm, một sản phẩm chỉ được cung cấp bởi một nhà cung cấp nhất định
##### -	Một kho có thể chứa nhiều sản phẩm, một sản phẩm chỉ thuộc một kho nhất định
##### -	Một hóa đơn có thể lưu thông tin nhiều sản phẩm, một sản phẩm có thể được lưu thông tin trong nhiều hóa đơn
##### -	Một phiếu nhập kho có thể lưu thông tin nhiều sản phẩm, một sản phẩm có thể được lưu thông tin trong nhiều phiếu nhập kho
##### -	Một phiếu xuất kho có thể lưu thông tin nhiều sản phẩm, một sản phẩm có thể được lưu thông tin trong nhiều phiếu xuất kho

## Mô hình ERD dạng chuẩn 3
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/4213ff13-50fa-4a4a-a6b2-db15b4e1362c)
## Xây dựng cơ sở dữ liệu
<img width="344" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/af931897-e920-48df-8b85-d921864b5900">
<img width="249" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b5be2668-5024-4d4d-9ada-5cfedbbdb2f5">
<img width="238" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/6db46f18-6e7a-4dd6-965f-3bbe5e5f6cb8">
<img width="245" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/977cfaf8-450e-4318-92bd-e25a51e78feb">
<img width="245" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/308eee0c-f5e9-4606-b7c4-768ab806f78b">
<img width="240" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/ec257b5f-1c19-4fda-8dc0-4cc306418473">
<img width="242" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/39eed5e9-6808-4057-b205-e3eccc2b100f">
<img width="236" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/c1d5b139-9d27-471a-bfe6-0f39bd3da4d1">
<img width="242" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/014bd59d-b02d-4a36-910a-3c6ca8a6dd8f">
<img width="226" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/cf8e78bd-74e1-4397-ab4e-1203e2c70205">
<img width="235" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/34f0e5bb-7e62-4219-98e4-b7e307d7e89a">
<img width="246" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/8ced99f5-3e33-46d9-abb5-7c079df0de48">
<img width="234" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/f1fc6bec-5f1a-40a9-8597-82807fcbe917">
<img width="240" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/d089a384-49fc-436c-83a0-40581d23d556">
<img width="239" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/8446597e-c576-4604-b021-540d13e990b2">
<img width="248" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/816b9165-c407-4d5f-92d4-6bbbe28cdc52">
### Mô tả các ràng buộc 
#####  -	Ràng buộc Check ở giới tính nhân viên để phân biệt giới tính với kiểu dữ liệu BIT thì tương ứng giới tính nam là 0 và nữ là 1.
##### -	Ràng buộc Check ở chức vụ nhân viên để phân biệt chức vụ của mỗi nhân viên cụ thể “QLT” tương ứng với “Quản lý trưởng”, “NV” tương ứng với “Nhân viên bán hàng”, “KT” tương ứng với “Kế toán”, “TK” tương ứng với “Thủ kho”.
##### -	Ràng buộc Default ở địa chỉ của Nhân viên đối với thông tin Nhân viên khi nhập mới chưa biết địa chỉ sẽ tự động mặc định là “Chưa có”.
##### -	Ràng buộc Default ở địa chỉ của Khách hàng đối với thông tin Khách hàng khi nhập mới chưa biết địa chỉ sẽ tự động mặc định là “Chưa có”.
##### -	Ràng buộc Default ở Mức khuyến mãi của Sản phẩm mặc định là 0, khi chương trình khuyến mãi được áp dụng vào 1 ngày cụ thể thì giá trị mức khuyến mãi sẽ được thay đổi bởi các thủ tục đưa vào.
##### -	Ràng buộc Check ở Phương thức thanh toán của Hóa Đơn để kiểm tra hình thức thanh toán của Khách Hàng, cụ thể “TM” tương ứng với “Tiền mặt”, “CK” tương ưng với “Chuyển khoản”
### Mô tả các ràng buộc toàn vẹn
##### 1. Mỗi nhân viên đều có một mã nhân viên để phân biệt
######  Bối cảnh: NHÂN VIÊN  
######  Điều kiện: ∀ n1, n2 thuộc NHANVIEN  
###### Nếu n1#n2 thì n1.[MANV] # n2.[MANV]  
######  Bảng tầm ảnh hưởng 
<img width="239" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b7300dd3-82e0-469d-8daa-bf9fc32e98e9">



