---


---

<h3 id="bước-1.-viết-prompt-theo-công-thức-3-phần">Bước 1. Viết Prompt theo công thức 3 phần</h3>
<p>Ông mở một cuộc trò chuyện AI mới và gửi prompt này:</p>
<h2 id="tôi-là-ai--bối-cảnh">Tôi là ai / Bối cảnh</h2>
<p>Tôi là sinh viên năm nhất ngành Công nghệ thông tin tại PTIT, đang học Markdown và kiến thức lập trình cơ bản. Tôi chưa hiểu rõ thuật ngữ API.</p>
<h2 id="chủ-đề--nội-dung-cần-xử-lý">Chủ đề / Nội dung cần xử lý</h2>
<p>Hãy giải thích thuật ngữ API (Application Programming Interface) theo cách dễ hiểu cho người mới học CNTT.</p>
<h2 id="yêu-cầu">Yêu cầu</h2>
<ul>
<li>
<p>Giải thích API là gì bằng ngôn ngữ đơn giản.</p>
</li>
<li>
<p>Đưa ra một ví dụ thực tế liên quan đến ứng dụng SmartCampus tra cứu lịch học.</p>
</li>
<li>
<p>Trình bày cách API giúp ứng dụng trao đổi dữ liệu với máy chủ.</p>
</li>
<li>
<p>Chia nội dung thành các tiêu đề ngắn và gạch đầu dòng.</p>
</li>
<li>
<p>Có một ví dụ ngắn để minh họa quá trình gửi yêu cầu và nhận dữ liệu.</p>
</li>
</ul>
<h2 id="không-cần">Không cần</h2>
<ul>
<li>
<p>Không giải thích quá sâu về lập trình hoặc giao thức mạng.</p>
</li>
<li>
<p>Không đưa thông tin ngoài chủ đề API cơ bản.</p>
</li>
</ul>
<h3 id="bước-2.-câu-trả-lời-mẫu-của-ai">Bước 2. Câu trả lời mẫu của AI</h3>
<p>Đây là nội dung tham khảo để ông lưu thành tài liệu tra cứu riêng.</p>
<h1 id="api-là-gì">API là gì?</h1>
<h2 id="khái-niệm">1. Khái niệm</h2>
<p><strong>API</strong> (Application Programming Interface) là giao diện cho phép các phần mềm giao tiếp và trao đổi dữ liệu với nhau.</p>
<p>Có thể hiểu API giống như người phục vụ trong nhà hàng: ứng dụng gửi yêu cầu, API chuyển yêu cầu đến hệ thống phù hợp và trả kết quả về ứng dụng.</p>
<h2 id="ví-dụ-với-smartcampus">2. Ví dụ với SmartCampus</h2>
<p>Khi sinh viên muốn xem lịch học trên SmartCampus:</p>
<ol>
<li>
<p>Sinh viên nhập mã sinh viên.</p>
</li>
<li>
<p>Ứng dụng gửi yêu cầu đến máy chủ thông qua API.</p>
</li>
<li>
<p>Máy chủ xử lý yêu cầu và trả dữ liệu lịch học.</p>
</li>
<li>
<p>Ứng dụng hiển thị lịch học cho sinh viên.</p>
</li>
</ol>
<h2 id="api-hoạt-động-như-thế-nào">3. API hoạt động như thế nào?</h2>
<ul>
<li>
<p><strong>Request:</strong> Ứng dụng gửi yêu cầu lấy dữ liệu.</p>
</li>
<li>
<p><strong>Server:</strong> Máy chủ xử lý yêu cầu.</p>
</li>
<li>
<p><strong>Response:</strong> Máy chủ trả kết quả cho ứng dụng.</p>
</li>
</ul>
<p>Ví dụ minh họa:</p>
<pre><code>GET /api/schedules/student123
</code></pre>
<p>Đây là ví dụ giả lập về yêu cầu lấy lịch học của một sinh viên. Địa chỉ API thực tế phụ thuộc vào cách hệ thống được xây dựng.</p>
<h2 id="vai-trò-của-api">4. Vai trò của API</h2>
<ul>
<li>
<p>Giúp ứng dụng lấy dữ liệu từ máy chủ.</p>
</li>
<li>
<p>Cho phép các hệ thống trao đổi thông tin.</p>
</li>
<li>
<p>Giúp ứng dụng tách biệt giao diện với phần xử lý dữ liệu.</p>
</li>
</ul>
<h3 id="bước-3.-tóm-tắt-bằng-lời-của-mình">Bước 3. Tóm tắt bằng lời của mình</h3>
<p>Áp dụng cách đọc 3 bước: xem tiêu đề, đọc phần chữ đậm, rồi xem các gạch đầu dòng.</p>
<p>API là giao diện giúp các phần mềm trao đổi dữ liệu với nhau. Trong SmartCampus, API giúp ứng dụng gửi yêu cầu lấy lịch học đến máy chủ và nhận dữ liệu trả về. API giúp việc kết nối giữa ứng dụng và hệ thống dữ liệu thuận tiện hơn.</p>
<h3 id="bước-4.-lưu-thành-api_giai_thich.md">Bước 4. Lưu thành <code>api_giai_thich.md</code></h3>
<ol>
<li>
<p>Mở StackEdit và tạo tài liệu mới.</p>
</li>
<li>
<p>Dán câu trả lời AI ở Bước 2 vào tài liệu.</p>
</li>
<li>
<p>Kiểm tra phần Preview để đảm bảo tiêu đề, danh sách và khung code hiển thị đúng.</p>
</li>
<li>
<p>Lưu hoặc xuất tài liệu với tên <code>api_giai_thich.md</code>.</p>
</li>
</ol>
<p>Quan trọng: Đề yêu cầu copy toàn bộ câu trả lời AI thực tế. Vì vậy, nếu ông gửi prompt ở Bước 1 cho AI và nhận được câu trả lời khác, hãy dùng câu trả lời thực tế đó thay cho nội dung mẫu phía trên.</p>
<h2 id="phần-4-hai-lỗi-cú-pháp-cần-nhớ">Phần 4: Hai lỗi cú pháp cần nhớ</h2>
<p>| Lỗi | Cách sửa | |—|---| | Bảng thiếu dòng phân cách sau hàng tiêu đề | Thêm dòng <code>|---|---|</code> | | Task List thiếu dấu cách sau <code>-</code> | Sửa <code>-[x]</code> thành <code>- [x]</code> |</p>
<p>Để nộp bài, ông lưu ba tài liệu thành <code>README.md</code>, <code>api_giai_thich.md</code> và <code>on_tap.md</code> (nếu muốn tách phần ôn tập riêng). Nếu đưa lên GitHub, nên đặt các file trong cùng repository của bài tập.</p>

