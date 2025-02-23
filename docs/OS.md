# Nội dung cho bài thuyết trình

> [!WARNING]
> Linux là nhân (kernel) của hệ điều hành. Không phải là hệ điều hành (OS).

> [!NOTE]
> Tại sao Linux lại được gọi là nhân của hệ điều hành chứ không phải hệ điều hành?
> bài viết sau đây sẽ tổng quát về Linux để mọi người có thể hiểu được vì sao Linux lại không phải hệ điều hành.

## Lịch sử về Linux (Đọc là li-ních không phải li-núch :v)

**Trước hết ta cần biết lý do vì sao Linux lại được tạo ra và một trong những lý
do mà Linux được tạo ra đó chính là sự phát triển của hệ điều thành UNIX và dự
án có tên GNU**

#### 1. Hệ điều hành UNIX và dự án GNU

- UNIX là một hệ điều hành được tạo ra vào những năm 1970. (Là một hệ điều hành
  mã nguồn đóng, có trả phí cho đến năm 1975 mới được phát hành mã nguồn mở do luật
  chống độc quyền của Mẽo :v)
- Vào năm 1983, một dự án có tên GNU nhằm mục đích xây dựng và phát triển một hệ điều
  hành giống UNIX (dựa trên phần khung của UNIX) và được phát hành dưới dạng mã
  nguồn mở.
  > Mã nguồn mở: miễn phí, bất kì ai cũng có thể vào đọc và chỉnh sửa
  > mã - code)

#### 2. Sự hình thành của Linux

- Dự án GNU không chỉ tạo ra một hệ điều hành mã nguồn mở cho mọi người sử dụng
  mà còn tạo ra nhiều công cụ khác như: Trình biên dịch ngôn ngữ C/C++ (GCC),
  trình soạn thảo văn bản Emacs,... Tuy nhiên, GNU vẫn thiếu một thành phần quan
  trọng, một mảnh ghép cuối cùng để giúp cho nó trở thành một hệ điều hành hoàn
  chỉnh. Đó chính là **Kernel**
  > Kernel (nhân) - hiểu một cách đơn giản Kernel có nhiệm vụ đó là giao tiếp và giao nhiệm
  > vụ cho phần cứng của máy tính (CPU, RAM, ROM, ...)
- Vào đầu năm 1991, một anh sinh viên đẹp zai 21 tuổi có tên Linus Torvalds (Lai-nợt To-vồ) của trường
  Đại học Helsiki ở Phần Lan đã biết đến dự án GNU và anh đã được sử dụng một
  phiên bản của chính hệ điều hành từ dự án GNU và rồi sau đó chính là lịch sử :)
- Tháng 4 năm đó, vào một ngày đầy sao, đêm không nắng, anh Linus của chúng ta
  đã đặt tay vào bàn phím và bắt đầu những dòng code đầu tiên để tạo nên Linux.
- Sau 4 tháng miệt mài ăn, ngủ, nghỉ với cái máy tính, anh ấy đã đã thông báo về sự ra
  đời của Linux và chỉ 1 tháng sau đó phiên bản Linux 0.01 được tạo ra bằng ngôn ngữ C (không phải C++) đã chính thức được phát hành.
- Đến năm 1992, anh Lai Nợt quyết định phát hành Linux dưới dạng mã nguồn mở có giấy phép (trước đó cũng là mã nguồn mở những chưa có giấy phép).
- Nhờ có Linux, đã có hàng trăm Hệ điều hành được sinh ra. Cho đến thời điểm
  hiện tại, Linux vẫn tiếp tục được phát triển và hoàn toàn mã nguồn mở. [Link dẫn tới trang lưu trữ mã nguồn của Linux](https://github.com/torvalds/linux)

#### 3. Úm ba la, Nô bi ta đưa xi zu ka sang Malaixia

- Như vậy, chúng ta đã thấy rằng Linux không phải một hệ điều hành mà là phần
  nhân bên trong của hệ điều hành có nhiệm vụ giao tiếp với phần cứng của máy
  tính. Nhưng tại sao vẫn có nhiều người hiểu nhầm?

1. Vì người ta không biết
2. Vì người ta không tìm hiểu :v
3. Vì trên trời cao có muôn ngàn vì sao tinh tú

> [!WARNING]
> Đùa thôi

**Chúng ta gọi Hệ điều hành Linux là chỉ đến những Hệ điều hành được xây dựng
từ Linux, tức nghĩa Linux không phải là một hệ điều hành riêng biệt mà có rất
nhiều hệ điều hành được xây dựng dựa trên nó**

> [!NOTE]
> Nếu nói tới phiên bản của Linux, thì chúng ta chỉ đang nói đến phiên của
> Kernel chứ không phải nói đến phiên bản của hệ điều hành mà đang chạy Linux

#### 4. Những hệ điều hành được tạo ra từ Linux

**Từ năm 1992 cho đến thời điểm hiện tại, tức là từ thời điểm hệ điều hành đầu tiên dựa
trên Linux được tạo ra, thì ở năm 2025 đang có hơn 600 hệ điều hành được tạo ra
(bên Linux gọi là distributions - các bản phân phối).**

`Nhiều như những vì sao tinh tú trên trời cao :v`

##### Tuy nhiên, có thể chia làm các nhánh lớn sau đây:

> [!NOTE]
> Gọi là nhánh tức nghĩa là những chúng có phiên bản độc lập, nhưng cộng
> đồng vẫn tạo ra nhưng phiên bản khác dựa trên những phiên bản đó. (vd: Iphone X thì Xs, Xs Max, Xr)

1. Nhánh Debian (Đê bi ần)
2. Nhánh Ubuntu (được xây dựng từ nhánh Debian)
3. Nhánh Knoppix (no-píc)
4. Nhánh Pacman
5. Nhánh Redhat
6. Nhánh SUSE (xu)
7. Nhánh Gentoo
8. Nhánh Slackware (hệ điều hành đầu tiên được tạo ra dựa trên Linux)
9. Nhánh Android

## [Phiên bản mới nhất của Linux](https://www.kernel.org/doc/html/latest/) - 6.14

## Link tham khảo

1. [Lịch sử hình thành Linux](https://blog.cloud365.vn/other/lich-su-hinh-thanh-linux/)
2. [Lịch sử về hệ điều hành Linux](https://blogd.net/linux/lich-su-he-dieu-hanh-linux/)
3. [Các bản phân phối Linux](https://en.wikipedia.org/wiki/List_of_Linux_distributions)

---

> Người soạn: aZong
