# Hướng dẫn nạp Firmware cho ESP-01, ESP01S, nạp firmware cho esp8266 Node MCU

## Mục lục
- Vì sao phải nạp firmware cho esp 8266 ?
- Vì sao phải tạo file Hex, file Bin và phải biết cách nạp file hex, file Bin cho esp8266, arduino ?
- Hướng dẫn nạp Fimware AT cho esp 01, esp01s
- Hướng dẫn nạp Firmware cho Esp 8266 Nodemcu
- Hướng dẫn xuất file HEX và nạp file HEX trên arduino
- Hướng dẫn tạo file Bin và nạp file Bin cho esp8266

## Vì sao phải nạp firmware cho esp 8266 ?
Esp 8266 được sử dụng rộng rãi trong các ứng dụng IOT, để sử dụng sản phẩm có hai phương án là nạp Firmware AT hoặc lập trình trực tiếp trên esp8266
Một vấn đề hay xảy ra đó là khi mới mua sản phẩm về chúng ta không thể lập trình bằng phương phương pháp tập lệnh AT, bởi vì đa số nhà bán hàng sẽ nạp chương trình của họ để test sản phẩm do đó sẽ làm mất chương trình AT của nhà sản xuất
Trong bài viết này mình sẽ hướng dẫn các bạn các nạp firmware cho các loại esp8266 thông dụng hiện nay đó là: esp 01 – esp 01s , esp 8266 nodemcu

## Vì sao phải tạo file Hex, file Bin và phải biết cách nạp file hex, file Bin cho esp8266, arduino ?
Bình thường khi dùng chương trình arduino khi lưu file sẽ có định dạng .INO , Trong một số do nhu cầu bảo mật nên khi chia sẻ code người ta sẽ không chia sẻ file định dạng đó mà sẽ tạo file hex, file bin gửi cho các bạn, nhiệm vụ của các bạn là phải biết nạp chương trình này vào. Hoặc các chương trình giả lập như Proteus khi nạp chương trình cũng cần định dạng là file hex

## Hướng dẫn nạp Firmware cho Esp 01 esp 01S:
Chuẩn bị phần cứng:
- 1 x mạch esp 01 hoặc 01s
- 1 x usb TTL, ví dụ CH340

Phần mềm cần thiết:
Phần mềm nạp tải firmware lên: https://drive.google.com/file/d/1a3InilCPxDjVxF8JYo-6Ry6EVouRALfv/view?usp=sharing
Firmware AT: https://drive.google.com/file/d/1f-X-Zce6L8cbLA2HdcU7XEKmrof8tdu8/view?usp=sharing
Chương trình giao tiếp với máy tính: https://www.hw-group.com/software/hercules-setup-utility

![Huong-dan-nap-Firmware-cho-Esp-8266-1](https://user-images.githubusercontent.com/11306328/197975107-a0f0cb5a-e156-42db-8590-7ce5131d6f98.jpg)

## Hướng dẫn nạp Fimware AT cho Esp 8266 Nodemcu
Chuẩn bị phần cứng:
- 1 x mạch esp 8266 nodemcu
- 1 x usb TTL, ví dụ CH340
- 1 x dây micro usb

Phần mềm cần thiết:
Phần mềm nạp tải firmware lên: https://drive.google.com/drive/folders/1HM8EQI9CPCu-KPEfrrRvrw3i2-hvSVtt?usp=sharing
Firmware AT: https://drive.google.com/file/d/1f-X-Zce6L8cbLA2HdcU7XEKmrof8tdu8/view?usp=sharing
Chương trình giao tiếp với máy tính: https://www.hw-group.com/software/hercules-setup-utility

![Huong-dan-nap-Firmware-cho-Esp-8266-2-1](https://user-images.githubusercontent.com/11306328/197975685-f93ff176-01bb-4cc4-9464-66b1286f40a6.jpg)
![Huong-dan-nap-Fimware-AT-cho-Esp-8266-nodemcu-2](https://user-images.githubusercontent.com/11306328/197975936-ffa18c66-c689-43e1-ac1e-61955b056783.jpg)
![Huong-dan-nap-Fimware-AT-cho-Esp-8266-nodemcu-2](https://user-images.githubusercontent.com/11306328/197975968-de5e9455-ef61-4ab5-9587-48105f48e845.jpg)




