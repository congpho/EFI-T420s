# EFI-T420s
Đây là bản dành cho Thinkpad T420s Hackintosh: macOS High Sierra 10.13.6
Trước tiên bạn tải file dmg macOS High Sierra 10.13.6 và Run nó, sau khi xong bạn vào Finder -> Applications sẽ thấy "Install macOS High Sierra". tiếp theo format usb đặt tên là "clover" và chạy file "Clover 10.13.command" nó sẽ yêu cầu nhập pass thì bạn gõ pass vào. và đợi nó coppy xong thì mới làm tiếp bước sau.
Sau khi coppy xong bạn chạy clover v2.4k hoặc bản mới hơn. nhớ chọn cài đặt clover vào usb nhé, nếu bạn ko hiểu có thể tìm trên mạng cách hướng dẫn clover. Mục đích là để nó tạo ra 1 phần vùng EFI trên usb sau đó ta chép thư mục EFI mà tôi đã share chép đè vào là xong.

Chú ý trong quá trình cài khi boot phải dùng usb để boot nhé. sau khi xong thì ta lại chép EFI chép đè vào phần vùng của ổ cứng thì lần sau booot ko phải mồi.

Khi cài xong có 1 số máy sẽ ko nhận drive wifi, thì phải xem lại phần cứng nhé, ko thì ra ngoài quán mua card wifi khác xong tìm kext cho model đó là dc.

Cách cài Kext thì bạn có thể dùng Kext Utility để cài.
