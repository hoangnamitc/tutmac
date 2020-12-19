# Tổng hợp các thủ thuật và lệnh về Mac

<br/>

> ### 1. Lệnh xóa tất cả cài đặt Finder
- Chạy terminal lệnh sau:\
```sudo find / -name .DS_Store -delete; killall Finder```

<br/>

> ### 2. Xác thực vân tay trên terminal

- Mở terminal và gõ lệnh sau:\
```sudo code /etc/pam.d/sudo```
- Thay đổi dòng có chứa **sufficient** thành:\
```auth sufficient pam_tid.so```

<br/>

> ### 3. Nén file bằng lệnh

1. **ZIP**
- __Nén File:__\
mở terminal:\
cd \<your-path\>\
```zip -r ../zip_file.zip *```
- __Giải nén File__:\
```unzip archive_name.zip```

2. **TAR.GZ**
- __Nén File:__\
mở terminal:\
cd \<your-path\>\
```tar -cvf ./zip_file.tar.gz *```\
kèm theo lệnh để loại trừ ko nén:\
```--exclude="._*"```
- __Giải nén File__:\
```tar -xvf archive_name.tar.gz```

<br/><br/><br/>
### Liên hệ & Hỗ trợ

Nếu bạn có thắc mắc hay hỗ trợ gì vui lòng tạo yêu cầu [tại đây](https://github.com/hoangnamitc/tutmac/issues)
