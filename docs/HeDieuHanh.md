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

  ![Unix](https://3.bp.blogspot.com/-_q2U2W55zGE/Wnw-XxSS7aI/AAAAAAAAG1A/G3IjTspNF5Ik3_5I7EqqW4FeT1te9RadQCLcBGAs/s400/What-is-UNIX.jpg)

- Vào năm 1983, một dự án có tên GNU nhằm mục đích xây dựng và phát triển một hệ điều
  hành giống UNIX (dựa trên phần khung của UNIX) và được phát hành dưới dạng mã
  nguồn mở.

  > Mã nguồn mở: miễn phí, bất kì ai cũng có thể vào đọc và chỉnh sửa
  > mã - code)

  ![GNU](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.webdevelopersnotes.com%2Fwp-content%2Fuploads%2Fgnu-project-announced.png&f=1&nofb=1&ipt=2490ac689979a3174c98144285881114129e83dd46bb782e24538539b60e2a32&ipo=images)

#### 2. Sự hình thành của Linux

![Linux](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flogos-world.net%2Fwp-content%2Fuploads%2F2020%2F09%2FLinux-Logo-1996-present.png&f=1&nofb=1&ipt=032645a7fa42389d5cfba0d00ef99c553fcb2f2e9f4f3b3be113b34685be1b23&ipo=images)

- Dự án GNU không chỉ tạo ra một hệ điều hành mã nguồn mở cho mọi người sử dụng
  mà còn tạo ra nhiều công cụ khác như: Trình biên dịch ngôn ngữ C/C++ (GCC),
  trình soạn thảo văn bản Emacs,... Tuy nhiên, GNU vẫn thiếu một thành phần quan
  trọng, một mảnh ghép cuối cùng để giúp cho nó trở thành một hệ điều hành hoàn
  chỉnh. Đó chính là **Kernel**

  > Kernel (nhân) - hiểu một cách đơn giản Kernel có nhiệm vụ đó là giao tiếp và giao nhiệm
  > vụ cho phần cứng của máy tính (CPU, RAM, ROM, ...)

  ![Linus Torvalds](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.linuxmi.com%2Fwp-content%2Fuploads%2F2020%2F12%2FLinus-Torvalds.jpeg&f=1&nofb=1&ipt=10521f3658803e42ac715062059a2c2b27b54815b9b2d89474c666710e9cdf17&ipo=images)
  ![Linus Torvalds](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fgizmodo.uol.com.br%2Fwp-content%2Fblogs.dir%2F8%2Ffiles%2F2020%2F05%2Flinus-torvalds-ted-conference-flickr-1.jpg&f=1&nofb=1&ipt=47f51d33bdf741ca161779278ec027a3347035f31f982e13da37074aff1118aa&ipo=images)

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

#### 3. Linux không phải là Hệ điều hành!

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

![Linux distributions](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmiro.medium.com%2Fv2%2Fresize%3Afit%3A1140%2F1*_DFfS_3E41lTvodx4OJDCw.jpeg&f=1&nofb=1&ipt=85614a9d30e3f01849666d178fe5863f00903860bd7f176ba283587c2807eda3&ipo=images)

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

## Bản chất của Linux (bản chất của tất cả mọi hệ điều hành)

> [!NOTE]
> Bản chất của Linux hay tất cả mọi phần mềm đó chỉ là những tập tin, gồm hàng
> loạt những dòng mã được các lập trình viên viết nên sau đó được biên dịch bởi
> trình biên dịch để trở thành mã máy nhằm mục đích giao nhiệm vụ và điều hành cho máy tính
> làm việc theo ý muốn của người tạo ra phần mềm.

## Tại sao mọi người tạo sử dụng Linux ?

1. Miễn phí

   > Những hệ điều hành (bản phân phối) được xây dựng từ Linux đa phần đều là mã
   > nguồn mở, cho phép người dùng tải về và trải nghiệm.

2. Tính bảo mật

   > - Khi sử dụng Windows, mặc định Microsoft sẽ cài đặt rất rất nhiều dịch vụ sâu
   >   bên trong hệ điều hành mà có thể bạn không bao giờ biết. So với đó, bạn hoàn
   >   toàn có thể biết được trong thiết bị của bạn đang có những dịch vụ gì, bạn có
   >   thể chủ động tắt hay bật.
   > - Một lý do khác đó chính là việc cài đặt những ứng dụng crack trên Windows quá
   >   là dễ dàng dẫn tới việc chúng có thể có viruss. Trên Linux, việc cài đặt những ứng
   >   dụng chủ yếu thông qua một công cụ có tên Package Manager (trình quản lý gói),
   >   để những phần mềm được phép xuất hiện và cài đặt thì sẽ phải thông qua sự kiểm
   >   duyệt bởi Package Manager, vậy nên tỉ lệ xuất hiện của ứng dụng có mã độc ít khi xảy ra.

> [!NOTE]
> Thật ra một khi hacker đã muốn hack rồi thì nó sẽ tìm được cách thôi :v phần
> mềm sẽ luôn luôn có lỗ hổng, chả hệ điều hành nào hay phần mềm nào là
> hoàn hảo.

3. Có thể cài đặt được trên nhiều thiết bị
   > - Linux tương tích tốt với nhiều phần cứng, máy tính của bạn dù chỉ có 400mb
   >   RAM, 800mb ROM thì vẫn hoàn toàn có thể cài đặt và chạy được những hệ điều
   >   hành của Linux.
   > - Linux hiện diện ở nhiều thiết bị, trong điện thoại của bạn, trong cục
   >   Router wifi nhà bạn cũng hoàn toàn có thể là đang chạy một phiên bản
   >   tối giản của Linux,...

> [!NOTE]
> Fun fact: Đã có lập trình viên cài đặt được Linux lên 1 chiếc que thử thai
> điện tử có màn hình và cài đặt thành công tựu game Doom Classic (đây là một
> tựa game huyền thoại thôi :v). Nói có sách, mách có chứng [link](https://www.youtube.com/watch?v=D5NTJSfUWDE)

4. Tính tùy biến cao
   > Vì là mã nguồn mở nên bạn hoàn toàn có thể thay đổi rất sâu trong hệ thống,
   > như thay đổi xung nhịp, hiệu suất của máy tính, tùy chỉnh giao diện sâu tới mức
   > chiếc máy tính đó của bạn trở thành bản độc nhất trên thế giới mà chỉ có bạn mới
   > biết sử dụng ... như máy tính của tớ :v

## [Phiên bản mới nhất của Linux](https://www.kernel.org/doc/html/latest/) - 6.14

## Link tham khảo

1. [Lịch sử hình thành Linux](https://blog.cloud365.vn/other/lich-su-hinh-thanh-linux/)
2. [Lịch sử về hệ điều hành Linux](https://blogd.net/linux/lich-su-he-dieu-hanh-linux/)
3. [Các bản phân phối Linux](https://en.wikipedia.org/wiki/List_of_Linux_distributions)
4. [Những lý do nên lựa chọn Linux](https://blog.udemy.com/why-use-linux/)

---

Người soạn: aZong
