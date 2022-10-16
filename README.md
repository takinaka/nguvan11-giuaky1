# Bài tập Ngữ văn 11, giữa kỳ I.
Đây là bài tập giữa kỳ I, môn Ngữ văn 11. Nghiêm cấm hành vi tải xuống, chỉnh sửa hoặc sử dụng mà không có sự đồng ý của các bên liên quan.

# Cấu trúc thư mục

Cấu trúc thư mục gốc bao gồm 2 thư mục "doc" chứa tệp tài liệu về dự án lần trước (có thể xem ở [đây](https://drive.google.com/drive/folders/1nhZt4XnF6knhiakI_BPvZwZYS6g6yr2W?usp=sharing)), "Video project" chứa các tài liệu liên quan đến việc làm video.

![image](https://user-images.githubusercontent.com/115929530/196038126-bbfa6ee9-949a-432a-94e0-405aa44efdb6.png)


# Cấu trúc thư mục "Video Project" (QUAN TRỌNG)

## 1. Cấu trúc thư mục tổng quát: Thư mục "Video Project" bao gồm thư mục:
  + "project" chứa các tệp mã nguồn video cho phần mềm Adobe Premiere Pro 2020. Có thể mở bằng cách mở tệp "source.prproj". Ngoài ra, trong thư mục còn có tệp "Instance.prproj" là tệp định dạng chỉnh sửa nhanh các phần video nhằm tránh việc chỉnh sửa quá nhiều trong tệp chính có thể gây ra lỗi tràn bộ nhớ (-1).
  + "source" chứa các thành phần cấu tạo nên video, bao gồm tư liệu, phông chữ, nhạc nền, phông hiệu và kịch bản nói cho người lồng tiếng. Mỗi một loại đều được chia thành các thư mục tương ứng

![image](https://user-images.githubusercontent.com/115929530/196038293-5bd1839b-840c-498d-a254-3d4702c346c3.png)


## 2. Quy tắc đặt tên trong thư mục "source":
  + Đối với thư mục "#script": "text-lysic-en.docx" là phiên bản tiếng Anh do học máy hỗ trợ, trong khi "text-lysic-vi.docx" là phiên bản tiếng Việt được hỗ trợ.
  + Đối với các tệp làm ảnh nền: <file type>-bg-<part>
  + Đối với các tệp khác: <file type>-<paragraph number>-<scene num>-<part>
### 	Với:
**file type** là loại tệp tin. Với video là "vid", tệp âm thanh là "mus", tệp hình ảnh là "pic", tệp powerpoint là "ppt". Đối với tệp phông chữ trong thư mục "font" và tệp psd trong thư mục "picture\samples", do là tệp mở rộng không phụ thuộc, nên không cần theo quy tắc.
  
**paragraph number** là vị trí của tệp đó trên đoạn văn tương ứng trong thư mục "#script". 

**part** là phần của tệp đó. Điều này khiến cho các tệp có thể sắp xếp theo trình tự video, với số nhỏ hơn được hiển thị trước số lớn hơn.

# Nguồn và tài trợ

Nguồn của hầu hết các tệp:
	+ Video tư liệu thật: VOA, BBC, Film Images (do cộng đồng hỗ trợ), Kênh Quốc hội Cộng hòa Xã hội Chủ nghĩa Việt Nam.

	+ Hình ảnh tư liệu đến từ: Film Images (do cộng đồng hỗ trợ), Vector, Bảo Khương (ĐH Kiến trúc), Jean Chesneaux (Nhà sử học người Pháp), Kenh14, Báo Đời sống & Pháp luật, Báo Thanh Niên, Báo Quân đội nhân dân Việt Nam, VOA, BBC, Kênh Quốc hội Cộng hòa Xã hội Chủ nghĩa Việt Nam.

	+ 2D/3D Animation: TheFlightSims (trước đây có tên là TheFlightSimulations Global), NVIDIA A.I., Topaz Labs
	
	+ Cấu trúc thư mục: TheFlightSims (trước đây có tên là TheFlightSimulations Global)
	
	+ Phông chữ: Microsoft, iCiel, Dexsar Harry Anugrah, STYLEno.1 Fonts
	
	+ Âm nhạc nền: Cộng đồng Pixabay

# Các phần mềm liên quan
	
### Lưu ý: khi cài đặt phần mềm, vui lòng kết nối mạng tốc độ cao nhằm kích hoạt tự động đến máy chủ được chỉ định (trừ GIMP và github).
	
Chỉnh sửa ảnh: [GIMP 2](https://download.gimp.org/gimp/v2.10/windows/gimp-2.10.32-setup-1.exe)

Chỉnh sửa video: [Microsoft PowerPoint 2021](https://drive.google.com/drive/folders/1EFyBoifVgVv8Owg2EYZCqYfBJWC3zzI5?usp=sharing), [Adobe Premiere Pro 2020](https://drive.google.com/file/d/1I2NO9CuQqrqF7pe5lcPEY58HMjS4gTer/view?usp=sharing)

Chỉnh sửa tệp kịch bản: [Microsoft Word 2021](https://drive.google.com/drive/folders/1EFyBoifVgVv8Owg2EYZCqYfBJWC3zzI5?usp=sharing)

Chỉnh sửa âm thanh: [FL Studio 20](https://drive.google.com/file/d/1WdbQydkr6raFDuygwHyxBm9fU3VzlWt_/view?usp=sharing)

Chỉnh sửa mã nguồn git này: [GitHub for Desktop](https://central.github.com/deployments/desktop/desktop/latest/win32?format=msi)
