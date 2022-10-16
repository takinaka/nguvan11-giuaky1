# Bài tập Ngữ văn 11, giữa kỳ I.
Đây là bài tập giữa kỳ I, môn Ngữ văn 11. Nghiêm cấm hành vi tải xuống, chỉnh sửa hoặc sử dụng mà không có sự đồng ý của các bên liên quan.

# Cấu trúc thư mục

Cấu trúc thư mục gốc bao gồm 2 thư mục "doc" chứa tệp tài liệu về dự án lần trước, "Video project" chứa các tài liệu liên quan đến việc làm video.

![image](https://user-images.githubusercontent.com/115929530/196038126-bbfa6ee9-949a-432a-94e0-405aa44efdb6.png)


# Cấu trúc thư mục "Video Project" (QUAN TRỌNG)

1. Cấu trúc thư mục tổng quát: Thư mục "Video Project" bao gồm thư mục:
  + "project" chứa các tệp mã nguồn video cho phần mềm Adobe Premiere Pro 2020. Có thể mở bằng cách mở tệp "source.prproj". Ngoài ra, trong thư mục còn có tệp "Instance.prproj" là tệp định dạng chỉnh sửa nhanh các phần video nhằm tránh việc chỉnh sửa quá nhiều trong tệp chính có thể gây ra lỗi tràn bộ nhớ (-1).
  + "source" chứa các thành phần cấu tạo nên video, bao gồm tư liệu, phông chữ, nhạc nền, phông hiệu và kịch bản nói cho người lồng tiếng. Mỗi một loại đều được chia thành các thư mục tương ứng

![image](https://user-images.githubusercontent.com/115929530/196038293-5bd1839b-840c-498d-a254-3d4702c346c3.png)


2. Quy tắc đặt tên trong thư mục "source":
  + Đối với thư mục "#script": "text-lysic-en.docx" là phiên bản tiếng Anh do học máy hỗ trợ, trong khi "text-lysic-vi.docx" là phiên bản tiếng Việt được hỗ trợ.
  + Đối với các tệp làm ảnh nền: <file type>-bg-<part>
  + Đối với các tệp khác: <file type>-<paragraph number>-<scene num>-<part>
Với:
<file type> là loại tệp tin. Với video là "vid", tệp âm thanh là "mus", tệp hình ảnh là "pic", tệp powerpoint là "ppt". Đối với tệp phông chữ trong thư mục "font" và tệp psd trong thư mục "picture\samples", do là tệp mở rộng không phụ thuộc, nên không cần theo quy tắc
<paragraph number> là vị trí của tệp đó trên đoạn văn của 

# Các phần mềm liên quan
Chỉnh sửa ảnh: GIMP 2

Chỉnh sửa video: Microsoft PowerPoint 2021, Adobe Premiere Pro 2020

Chỉnh sửa source: Microsoft Word 2021

Chỉnh sửa âm thanh: FL Studio 20

Chỉnh sửa mã nguồn git này: github for desktop, git CLI.
