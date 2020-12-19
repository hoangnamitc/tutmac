# Tổng hợp các thủ thuật và lệnh về Mac

> ### 1. Lệnh xóa tất cả cài đặt Finder

```sudo find / -name .DS_Store -delete; killall Finder```

<br/>

> ### 2. Xác thực vân tay trên terminal
- Mở terminal và gõ lệnh sau:\
```sudo code /etc/pam.d/sudo```
- Thay đổi dòng có chứa **sufficient** thành:\
```auth sufficient pam_tid.so``` 

<br/><br/><br/>
### Liên hệ & Hỗ trợ

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
