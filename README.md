#### ThucHanhKiemThuUngDungWeb_API
### HỆ THỐNG TÌM KIẾM VIỆC LÀM

##### 🔗 Link Web: 
[TÌM KIẾM VIỆC LÀM](http://ec2-13-228-39-1.ap-southeast-1.compute.amazonaws.com/)
##### 📁 Tài liệu đặc tả kỹ thuật SRS:
[SRS_Chức năng - nghiệp vụ của hệ thống tìm kiếm việc làm.docx](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/files/12393919/SRS_Ch.c.nang.-.nghi.p.v.c.a.h.th.ng.tim.ki.m.vi.c.lam.docx)

##### 🌻 Giải thích về hệ thống:
Ý nghĩa, mục đích: 
- Hệ thống “Tìm kiếm việc làm” là một hệ thống giúp kết nói những nhà tuyển dụng và ứng viên, những người mong muốn tìm cho mình một công việc phù hợp.

##### 🔯 Các chức năng chính của hệ thống: 
  -	Quản lí thông tin ứng viên.
  -	Quản lí thông tin công ty (nhà tuyển dụng).
  -	Quản lí các bài viết tìm việc.
  -	Cập nhật tin tức cho khách hàng.
##### ✴️ Đối tượng tham gia vào hệ thống: 

![timvieclam drawio](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/1da329a2-5d05-4b39-9d29-fceb38193d43)

##### ⏯️ Các bước thực hiện:
![step](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/68509b03-e195-4fc1-80c4-cbc191c43ad2)
***
![FLOW_kiemthuWEB drawio](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/bb4b761a-59db-436b-bc5b-8a88265dcc7d)

![FLOW_kiemthuWEB_2 drawio](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/572f46cb-421b-4638-b069-b60a2352fbc1)

![DANG BAI TIM UV drawio](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/7e736fc3-2500-4184-9deb-624446392eee)   ![DANG BAI UNG TUYEN](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/9385b24f-b4b0-43a3-911c-49d5697aa347)
***
##### ✍️ Testcase Website & Defect Log

![testcase_web](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/51f36e35-fa71-4ca4-8b47-089db2647884)

![defect_log_website](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/8a05078f-f7c1-439e-8bdc-fe44e26624f8)

![chart_web](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/5e9000b9-cc56-4d36-be95-dadb50c932c6)
***
##### ✍️ Testcase API & Defect Log

![testcaseAPI](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/5fec7ffe-6e5b-43fa-8569-b20ffa7d778e)

![defect_API](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/3cd537b2-b867-4fbf-a478-5e27a5d93027)

 📜 _Ví dụ 1 Script test:_
``` javascript
pm.test("name trống, Status 400 Bad Request", function () {
    pm.response.to.have.status(400)
});

const response = pm.response.json();
const expectMsg = "Không được để trống họ tên"

pm.test('message: ' + expectMsg, () => {
    pm.expect(response).to.haveOwnProperty('message');
    pm.expect(response.message).to.eql(expectMsg)
});
```
![evidence](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/9765c724-d85f-489a-b090-de2373a5314b)

![chart_API](https://github.com/khang77/ThucHanhKiemThuUngDungWeb_API/assets/92577611/c051b2dd-f98d-4dd5-ab9f-d60c2af1c7bf)


