# Project_SalesManagementSystem
#### Source code: https://drive.google.com/file/d/1IOc-ULDkBS14j-MHXZwSpXGFeuXfc6cG/view?usp=sharing
### Đề tài “Xây dựng hệ thống quản lý bán hàng tại GS25” hướng đến các mục tiêu cơ bản sau:
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

##  Mô tả các ràng buộc 
#### -	Ràng buộc Check ở giới tính nhân viên để phân biệt giới tính với kiểu dữ liệu BIT thì tương ứng giới tính nam là 0 và nữ là 1.
#### -	Ràng buộc Check ở chức vụ nhân viên để phân biệt chức vụ của mỗi nhân viên cụ thể “QLT” tương ứng với “Quản lý trưởng”, “NV” tương ứng với “Nhân viên bán hàng”, “KT” tương ứng với “Kế toán”, “TK” tương ứng với “Thủ kho”.
#### -	Ràng buộc Default ở địa chỉ của Nhân viên đối với thông tin Nhân viên khi nhập mới chưa biết địa chỉ sẽ tự động mặc định là “Chưa có”.
#### -	Ràng buộc Default ở địa chỉ của Khách hàng đối với thông tin Khách hàng khi nhập mới chưa biết địa chỉ sẽ tự động mặc định là “Chưa có”.
#### -	Ràng buộc Default ở Mức khuyến mãi của Sản phẩm mặc định là 0, khi chương trình khuyến mãi được áp dụng vào 1 ngày cụ thể thì giá trị mức khuyến mãi sẽ được thay đổi bởi các thủ tục đưa vào.
#### -	Ràng buộc Check ở Phương thức thanh toán của Hóa Đơn để kiểm tra hình thức thanh toán của Khách Hàng, cụ thể “TM” tương ứng với “Tiền mặt”, “CK” tương ưng với “Chuyển khoản”
### Mô tả các ràng buộc toàn vẹn
#### 1. Mỗi nhân viên đều có một mã nhân viên để phân biệt
#####  Bối cảnh: NHÂN VIÊN  
#####  Điều kiện: ∀ n1, n2 thuộc NHANVIEN  
#####  Nếu n1#n2 thì n1.[MANV] # n2.[MANV]  
#####  Bảng tầm ảnh hưởng 
<img width="239" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b7300dd3-82e0-469d-8daa-bf9fc32e98e9">

####  2. Mỗi hóa đơn đều có một mã hóa đơn để phân biệt 
##### Bối cảnh: HOADON
##### Điều kiện: ∀ h1, h2 thuộc HOADON
##### Nếu h1#h2 thì h1.[MAHD] # h2.[MAHD]  
##### Bảng tầm ảnh hưởng 
<img width="233" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/053afc38-9888-4401-bcb4-b56c846fc84d">

#### 3. Mỗi khách hàng đều có một mã khách hàng để phân biệt
##### Bối cảnh: KHACHHANG
##### Điều kiện: ∀ x1, x2 thuộc KHACHHANG
##### Nếu x1#x2 thì x1.[MAKH] # x2.[MAKH]  
##### Bảng tầm ảnh hưởng 
<img width="227" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/c42e4edf-452c-4432-8f55-a271810613e3">

####  4. Mỗi sản phẩm đều có một mã sản phẩm để phân biệt
##### Bối cảnh: SANPHAM
##### Điều kiện: ∀ s1, s2 thuộc SANPHAM
##### Nếu s1#s2 thì s1.[MASP] # s2.[MASP]  
##### Bảng tầm ảnh hưởng 
<img width="228" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/14bd051e-1dd1-41fb-aa2e-1f286bf0ae0b">

####  5. Mỗi kho đều có một mã kho để phân biệt
##### Bối cảnh: KHO
##### Điều kiện: ∀ k1, k2 thuộc KHO
##### Nếu k1#k2 thì k1.[MASP] # k2.[MAKHO]  
##### Bảng tầm ảnh hưởng 
<img width="229" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b9b50345-b96b-41f9-b68f-b9fe3bec6158">

####  6. Mỗi loại sản phẩm đều có một mã loại để phân biệt
##### Bối cảnh: LOAISANPHAM
##### Điều kiện: ∀ p1, p2 thuộc LOAISANPHAM
##### Nếu p1#p2 thì p1.[MASP] # p2.[MASP]  
##### Bảng tầm ảnh hưởng 
<img width="226" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/afd5e79d-81b3-4543-bc43-0d7f6bea90b9">

####  7. Mỗi nhà cung cấp đều có một mã nhà cung cấp để phân biệt
##### Bối cảnh: NHACUNGCAP
##### Điều kiện: ∀ c1, c2 thuộc NHACUNGCAP
##### Nếu c1#c2 thì c1.[MANCC] # c2.[MANCC]  
##### Bảng tầm ảnh hưởng 
<img width="226" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b42624e1-5882-443d-827c-9ed20de96e5d">

#### 8. Mỗi phiếu xuất kho đều có một mã để phân biệt
##### Bối cảnh: PHIEUXUATKHO
##### Điều kiện: ∀ x1, x2 thuộc PHIEUXUATKHO
##### Nếu x1#x2 thì x1.[MAXK] # x2.[MAXK]  
##### Bảng tầm ảnh hưởng 
<img width="215" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/09d4a1a8-e019-42e3-8504-778c2399c8e5">

####  9. Mỗi phiếu nhập kho đều có một mã để phân biệt.
##### Bỗi cảnh: PHIEUNHAPKHO
##### Điều kiện: ∀ n1, n2 thuộc PHIEUNHAPKHO 
##### Nếu n1#n2 thì n1.[MANK] # n2.[MANK]  
##### Bảng tầm ảnh hưởng 
<img width="219" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/7b810d1b-0b68-44dc-a39e-6d7b9b2fb16a">

####  10. Giới tính của nhân viên chỉ có thể là ‘0’ hoặc ‘1’
##### Bối cảnh: NHANVIEN
##### Điều kiện: ∀ n thuộc NHANVIEN: n.GIOITINH IN (0,1)
##### Bảng tầm ảnh hưởng:
<img width="226" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/1cadf058-2377-4f85-93b0-7d27419ff6f1">

####  11. Số điện thoại khách hàng phải đủ 10 số: 
##### Bối cảnh: KHACHHANG 
##### Điều kiện: ∀ H1,H2 thuộc KHACHHANG 
##### Nếu H1 # H2 thì H1.[SDT] # H2.[ SDT] 
##### Bảng tầm ảnh hưởng: 
<img width="234" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/eb0babaa-8504-4310-b4e1-7d4b779dc6a4">

#### 12. Đơn giá bán phải lớn hơn 0: 
##### Bối cảnh: CTHOADON
##### Điều kiện: ∀ dongiaban thuộc CTHOADON Thì 
##### CTHOADON.[DONGIABAN >0]
##### Bảng tầm ảnh hưởng: 
<img width="222" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/d0c586e3-d1c1-4151-8149-a74d4ba3dc19">

####  13. Đơn giá nhập kho phải lớn hơn 0
##### Bối cảnh: CTPHIEUNHAPKHO
##### Điều kiện: ∀ dongiank thuộc CTPHIEUNHAPKHO Thì CTPHIEUNHAPKHO.[DONGIANK >0] 
##### Bảng tầm ảnh hưởng: 
<img width="223" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/71f29a0e-4ba4-486b-a71f-503b6b75f9e8">

####  14. Đơn giá xuất kho phải lớn hơn 0
##### Bối cảnh: CTPHIEUXUATKHO
##### Điều kiện: ∀ dongiaxk thuộc CTPHIEUXUATKHO Thì CTPHIEUXUATKHO.[DONGIAXK >0] 
##### Bảng tầm ảnh hưởng: 
<img width="224" alt="image" src="https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/9d24351e-05af-4ae9-8a35-91e22d2c9d30">

# Sơ đồ Diagram
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b64c0335-1007-4d11-973b-67d1afa3eda5)

# GIAO DIỆN CHƯƠNG TRÌNH
## Form đăng nhập hệ thống
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/c5137aa1-02d9-4e6f-8b7d-91dc446c5295)

#####  -	Đây là giao diện khởi động của hệ thống. Muốn vào trong hệ thống chúng ta cần thông qua chức năng đăng nhập của giao diện này.
#####  -	Cần sử dụng tài khoản và mật khẩu đã có sẵn để đăng nhập vào hệ thống.

## Form màn hình chính
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/770dc63a-e8e7-4c45-97fe-21c9d6fe8b34)

-	Sau khi đăng nhập với tài khoản là quản lý thành công giao diện chính của hệ thống sẽ xuất hiện.
-	Form chính của hệ thống bao gồm các chức năng như quản lý sản phẩm, quản lý nhân viên, quản lý hóa đơn, quản lý kho, quản lý nhà cung cấp, quản lý tài khoản, quản lý doanh thu, quản lý thống kê, quản lý khách hàng, đăng xuất và thoát.

## Màn hình quản lý nhân viên
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/b2d7d348-959a-4836-ab9d-39b5f86c8fe2)

##### 	Form có chức năng quản lý thông tin của nhân viên.
##### 	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
##### 	Các thành phần trên form quản lý nhân viên bao gồm: 
        	Thông tin nhân viên: mã nhân viên, họ và tên, ngày sinh, giới tính, số điện thoại, địa chỉ, tài khoản, email, chức vụ.
              +	JTable (tableNV) để load dữ liệu từ CSDL lên form.
              +	Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, in danh sách 
###### 	Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin nhân viên mới.
###### 	Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về thông tin nhân viên gồm: mã nhân viên, họ và tên, ngày sinh, giới tính, số điện thoại, địa chỉ, tài khoản, email, chức vụ thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm nhân viên mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableNV.
###### 	Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu nhân viên đã tồn tại (ví dụ: sửa thông tin họ tên nhân viên, giới tính, …).
###### 	Chức năng xóa: Khi cần xóa thông tin về một nhân viên, người dùng sẽ chọn nhân viên cần xóa và click vào button “Xóa”.
###### 	Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của nhân viên thông qua: mã nhân viên, họ và tên, ngày sinh, giới tính, số điện thoại, địa chỉ, tài khoản, email, chức vụ. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
###### 	Chức năng in danh sách: Khi nhấn vào button “In Danh Sach” thì chương trình sẽ in ra danh sách toàn bộ nhân viên của cửa hàng. Tại đây có thể xuất ra file PDF để lưu về máy tính.

## Màn hình quản lý sản phẩm
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/3db21ce3-e4bf-444b-9827-97d22529df7e)

##### 		Form có chức năng quản lý thông tin của sản phẩm.
#####   	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####   	Các thành phần trên form quản lý sản phẩm bao gồm: 
	                Thông tin sản phẩm: mã sản phẩm, tên sản phẩm, mức khuyến mãi, đơn giá, số lượng tồn, đơn vị tính, mã loại sản phẩm, mã nhà cung cấp, mã kho.
	                JTable (tableSP) để load dữ liệu từ CSDL lên form.
	                Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm.
######  	Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin sản phẩm mới.
######  	Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về thông tin sản phẩm cần thêm gồm: mã sản phẩm, tên sản phẩm, mức khuyến mãi, đơn giá, số lượng tồn, đơn vị tính, mã loại sản phẩm, mã nhà cung cấp, mã kho thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm SP mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableSP.
######  	Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu sản phẩm đã tồn tại (ví dụ: sửa thông tin tên sản phẩm, mức khuyến mãi, …).
######  	Chức năng xóa: Khi cần xóa thông tin về một sản phẩm, người dùng sẽ chọn sản phẩm cần xóa và click vào button “Xóa”.
######  	Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của sản phẩm thông qua: mã sản phẩm, tên sản phẩm, mức khuyến mãi, đơn giá, số lượng tồn, đơn vị tính, mã loại sản phẩm, mã nhà cung cấp, mã kho. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.

## Màn hình quản lý loại sản phẩm
##### 	Form có chức năng quản lý thông tin của các loại sản phẩm.
##### 	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
##### 	Các thành phần trên form quản lý các loại sản phẩm bao gồm: 
		Thông tin loại sản phẩm: mã loại sản phẩm, tên loại sản phẩm.
		JTable (tableDSLoaiSP) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin loại sản phẩm mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về thông tin loại sản phẩm gồm: mã loại sản phẩm, tên loại sản phẩm thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm LSP thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableDSLoaiSP.

######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu loại sản phẩm đã tồn tại (ví dụ: sửa thông tin tên loại sản phẩm, …).
######		Chức năng xóa: Khi cần xóa thông tin về một loại sản phẩm, người dùng sẽ chọn loại sản phẩm cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của loại sản phẩm thông qua: mã loại sản phẩm, tên loại sản phẩm. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.

## Màn hình quản lý nhà cung cấp
#####	Form có chức năng quản lý thông tin của các nhà cung cấp.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý nhà cung cấp bao gồm: 
		Thông tin nhà cung cấp: mã nhà cung cấp, tên nhà cung cấp, địa chỉ, email.
		JTable (tableDSNCC) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin nhà cung cấp mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về thông tin nhà cung cấp gồm: mã nhà cung cấp, tên nhà cung cấp, địa chỉ, email thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm NCC mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableDSNCC.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu nhà cung cấp đã tồn tại (ví dụ: sửa thông tin tên nhà cung cấp, …).
######		Chức năng xóa: Khi cần xóa thông tin về một nhà cung cấp, người dùng sẽ chọn nhà cung cấp cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của nhà cung cấp thông qua: mã nhà cung cấp, tên nhà cung cấp, địa chỉ, email. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.
## Màn hình quản lý khách hàng
#####	Form có chức năng quản lý thông tin của khách hàng.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý khách hàng bao gồm: 
		Thông tin khách hàng: mã khách hàng, tên khách hàng, họ khách hàng, địa chỉ, điện thoại.
		JTable (tableqlKH) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin khách hàng mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về thông tin khách hàng gồm: mã khách hàng, tên khách hàng, họ khách hàng, địa chỉ, điện thoại thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm KH mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableqlKH.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu khách hàng đã tồn tại (ví dụ: sửa thông tin họ khách hàng, …).
######		Chức năng xóa: Khi cần xóa thông tin về một khách hàng, người dùng sẽ chọn khách hàng cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của khách hàng thông qua: mã khách hàng, tên khách hàng, họ khách hàng, địa chỉ, điện thoại. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.

## Màn hình quản lý tài khoản

#####	Form có chức năng quản lý thông tin của các tài khoản dùng để đăng nhập vào hệ thống.
#####	Các thành phần trên form quản lý tài khoản bao gồm: 
		Thông tin tài khoản: mã ID, usename, password.
		JTable (tableDSTaiKhoan) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin đăng kí tài khoản mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về tài khoản gồm: mã ID, usename, password thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm TK mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableDSTaiKhoan.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu tài khoản đã tồn tại (ví dụ: sửa usename, …).
######		Chức năng xóa: Khi cần xóa thông tin về một tài khoản, người dùng sẽ chọn tài khoản cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của tài khoản thông qua: mã ID, usename, password. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.

## Màn hình quản lý kho
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/3eaec28c-9db7-4016-8f3f-5da0e2151171)

#####	Form có chức năng quản lý thông tin kho của cửa hàng.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý kho bao gồm: 
		Thông tin kho: mã kho, tên kho, địa chỉ.
		JTable (tableDSKho) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới, in ra danh sách kho.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin kho mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về kho gồm: mã kho, tên kho, địa chỉ thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm kho mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableDSKho.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu tài khoản đã tồn tại (ví dụ: sửa địa chỉ, …).
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu tài khoản đã tồn tại (ví dụ: sửa địa chỉ, …).
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của kho thông qua: mã kho, tên kho, địa chỉ. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.
######		Chức năng in danh sách kho: Khi nhấn vào button “Print” thì chương trình sẽ in ra thông tin của kho được chọn. Tại đây có thể xuất ra file PDF để lưu về máy tính.

## Màn hình quản lý phiếu nhập kho

#####	Form có chức năng quản lý thông tin phiếu nhập kho của cửa hàng.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý phiếu nhập bao gồm: 
		Thông tin phiếu nhập: mã nhập kho, ngày nhập, mã nhân viên.
		JTable (tablePNK) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập phiếu nhập kho.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về phiếu nhập kho gồm: mã nhập kho, ngày nhập, mã nhân viên thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm PNK mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tablePNK.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu phiếu nhập kho đã tồn tại (ví dụ: sửa ngày nhập kho, …).
######		Chức năng xóa: Khi cần xóa thông tin phiếu nhập kho, người dùng sẽ chọn phiếu nhập kho cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của phiếu nhập kho thông qua: mã nhập kho, ngày nhập, mã nhân viên. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.

## Màn hình quản lý chi tiết phiếu nhập kho
#####	Form có chức năng quản lý thông tin chi tiết của phiếu nhập kho.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý chi tiết phiếu nhập kho bao gồm: 
		Thông tin chi tiết phiếu nhập: mã nhập kho, mã sản phẩm, số lượng nhập, đơn giá nhập.
		JTable (tableCTPNK) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin chi tiết phiếu nhập mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về chi tiết phiếu nhập kho gồm: mã nhập kho, mã sản phẩm, số lượng nhập, đơn giá nhập thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm CTPNK mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableCTPNK.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu chi tiết phiếu nhập kho đã tồn tại (ví dụ: số lượng nhập kho, …).
######		Chức năng xóa: Khi cần xóa thông tin chi tiết phiếu nhập kho, người dùng sẽ chọn chi tiết phiếu nhập kho cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của chi tiết phiếu nhập kho thông qua: mã nhập kho, mã sản phẩm, số lượng nhập, đơn giá nhập. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.
## Màn hình quản lý phiếu xuất kho
#####	Form có chức năng quản lý thông tin phiếu xuất kho.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý phiếu xuất kho bao gồm: 
		Thông tin phiếu xuất kho: mã xuất kho, ngày xuất, mã nhân viên.
		JTable (tablePXK) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin phiếu xuất kho mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về phiếu xuất kho gồm: mã xuất kho, ngày xuất, mã nhân viên thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Thêm thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tablePXK.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu phiếu xuất kho đã tồn tại (ví dụ: sửa ngày xuất kho, …).
######		Chức năng xóa: Khi cần xóa thông tin phiếu xuất kho, người dùng sẽ chọn phiếu xuất kho cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của phiếu xuất kho thông qua: mã xuất kho, ngày xuất, mã nhân viên. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.

## Màn hình quản lý chi tiết phiếu xuất kho 
#####	Form có chức năng quản lý thông tin chi tiết của phiếu xuất kho.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý chi tiết phiếu xuất kho bao gồm: 
		Thông tin chi tiết phiếu xuất: mã xuất kho, mã sản phẩm, số lượng xuất, đơn giá xuất.
		JTable (tableCTPXK) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin chi tiết phiếu xuất kho.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về chi tiết phiếu xuất kho gồm: mã xuất kho, mã sản phẩm, số lượng xuất, đơn giá xuất thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm CTPXK mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableCTPXK.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu chi tiết phiếu xuất kho đã tồn tại (ví dụ: số lượng xuất kho, …).
######		Chức năng xóa: Khi cần xóa thông tin chi tiết phiếu xuất kho, người dùng sẽ chọn chi tiết phiếu xuất kho cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của chi tiết phiếu xuất kho thông qua: mã xuất kho, mã sản phẩm, số lượng xuất, đơn giá xuất. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
######		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.

## Màn hình quản lý hoá đơn
#####	Form có chức năng quản lý thông tin của hóa đơn.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý hóa đơn bao gồm: 
		Thông tin hóa đơn: mã hóa đơn, ngày lập hóa đơn, phương thức thanh toán, mã nhân viên, mã khách hàng.
		JTable (tableHD) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm.
######		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin hóa đơn mới.
######		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về hóa đơn gồm mã hóa đơn, ngày lập hóa đơn, phương thức thanh toán, mã nhân viên, mã khách hàng thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm hóa đơn mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableHD.
######		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu hóa đơn đã tồn tại (ví dụ: phương thức thanh toán, …).
######		Chức năng xóa: Khi cần xóa thông tin hóa đơn, người dùng sẽ chọn hóa đơn cần xóa và click vào button “Xóa”.
######		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của hóa đơn thông qua: mã hóa đơn, ngày lập hóa đơn, phương thức thanh toán, mã nhân viên, mã khách hàng. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.

## Màn hình quản lý chi tiết hoá đơn

#####	Form có chức năng quản lý thông tin chi tiết của hóa đơn.
#####	Khi thực hiện các chức năng hiện có trên form đều có các thông báo xác nhận để các thao tác trên form được chính xác nhất.
#####	Các thành phần trên form quản lý chi tiết hóa đơn bao gồm: 
		Thông tin chi tiết hóa đơn: mã hóa đơn, mã sản phẩm, số lượng bán, đơn giá bán.
		JTable (tableCTHD) để load dữ liệu từ CSDL lên form.
		Các chức năng: thêm, lưu, sửa, xóa, tìm kiếm, làm mới, in danh sách.
#####		Chức năng thêm: Cho phép xóa trắng hết dữ liệu để nhập thông tin chi tiết hóa đơn mới.
#####		Chức năng lưu: Khi người dùng đã nhập hết các dữ liệu về chi tiết hóa đơn gồm: mã hóa đơn, mã sản phẩm, số lượng bán, đơn giá bán thì click vào button “Lưu” nếu thành công thì sẽ xuất hiện hộp thoại thông báo “Đã thêm CTHD mới thành công” và thông tin sau khi thêm sẽ được hệ thống cập nhật hiển thị lên tableCTHD.
#####		Chức năng sửa: Thao tác này cho phép người dùng sửa lại dữ liệu chi tiết hóa đơn đã tồn tại (ví dụ: số lượng bán, …).
#####		Chức năng xóa: Khi cần xóa thông tin chi tiết hóa đơn, người dùng sẽ chọn chi tiết hóa đơn cần xóa và click vào button “Xóa”.
#####		Chức năng tìm kiếm: Chức năng cho phép người dùng hệ thống truy xuất thông tin của chi tiết hóa đơn thông qua: mã hóa đơn, mã sản phẩm, số lượng bán, đơn giá bán. Dữ liệu trả về có thể là 1 hoặc nhiều trường dữ liệu tùy thuộc vào phương thức tìm kiếm.
#####		Chức năng làm mới: Sau khi thực hiện thay đổi trên form nhấn button “Làm mới” để refresh lại dữ liệu trên bảng.
#####		Chức năng in hóa đơn: Khi nhấn vào button “In Hoa Don” thì chương trình sẽ in ra thông tin hóa đơn được chọn. Tại đây có thể xuất ra file PDF để lưu về máy tính.
## Màn hình thống kê
#####		Form có chức năng thống kê doanh thu của cửa hàng.
![image](https://github.com/Ni2103/Project_SalesManagementSystem/assets/89075130/5a7fea4f-405e-4ceb-b851-0549fd1a3013)

###### ====== Hạn chế của Project =======
1. Các tính năng còn cơ bản, vấn đề phân quyền chưa được hoàn thiện
2. Một số sử lý ràng buộc chưa chặt chẽ
3. Chưa tiếp xúc với môi trường thực tế ( chỉ nghiên cứu tìm hiểu qua internet nên còn nhiều thiếu sót trong khâu phân tích )

