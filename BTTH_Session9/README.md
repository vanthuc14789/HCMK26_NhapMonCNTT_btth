---


---

<h1 id="smartcampus-🎓">SmartCampus 🎓</h1>
<p>SmartCampus là <strong>ứng dụng di động</strong> giúp sinh viên PTIT <em>tra cứu thông tin học tập</em>, xem phòng trống và nhận thông báo từ nhà trường.</p>
<h2 id="tính-năng-chính">Tính năng chính</h2>
<ul>
<li>Tra cứu lịch học theo mã sinh viên.
<ul>
<li>Giúp sinh viên xem lịch học của mình.</li>
</ul>
</li>
<li>Xem danh sách phòng trống theo tòa nhà.</li>
</ul>
<h2 id="liên-kết-dự-án">Liên kết dự án</h2>
<p>Trang chủ CLB: <a href="https://clblaptrinh.ptit.edu.vn">CLB Lập trình PTIT</a></p>
<blockquote>
<p>Lưu ý: Dự án đang trong giai đoạn phát triển, chưa sử dụng cho mục đích chính thức.</p>
</blockquote>
<hr>
<h2 id="cài-đặt-dự-án"> Cài đặt dự án</h2>
<p>Để tải và chạy dự án, mở Terminal và nhập lần lượt các lệnh sau:</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> clone https://github.com/clb-lap-trinh/smartcampus.git
<span class="token function">npm</span> <span class="token function">install</span>
<span class="token function">npm</span> start
</code></pre>
<h2 id="danh-sách-công-việc">Danh sách công việc</h2>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" checked="true" disabled=""> Tra cứu lịch học theo mã sinh viên.</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" checked="true" disabled=""> Xem danh sách phòng trống theo tòa nhà.</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Phát triển thông báo đẩy (push notification).</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Phát triển đăng nhập bằng tài khoản trường.</li>
</ul>
<h2 id="thư-viện-sử-dụng">Thư viện sử dụng</h2>

<table>
<thead>
<tr>
<th align="left">Thư viện</th>
<th align="center">Phiên bản</th>
<th align="left">Mục đích</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">React Native</td>
<td align="center">0.74</td>
<td align="left">Xây giao diện đa nền tảng iOS/Android</td>
</tr>
<tr>
<td align="left">Axios</td>
<td align="center">1.6</td>
<td align="left">Gọi API lấy dữ liệu lịch học</td>
</tr>
</tbody>
</table><h2 id="ghi-chú-ôn-tập">Ghi chú ôn tập</h2>
<p>Markdown dùng các ký tự đặc biệt để định dạng văn bản. Muốn hiển thị nguyên dấu <code>*</code> thì viết <code>\*</code>, còn muốn hiển thị nguyên dấu <code>#</code> thì viết <code>\#</code>.</p>
<h3 id="kiểm-tra-lỗi-cú-pháp-markdown">Kiểm tra lỗi cú pháp Markdown</h3>
<p>Đoạn ban đầu có 2 lỗi:</p>
<ol>
<li><strong>Bảng thiếu dòng phân cách:</strong> Cần thêm dòng <code>| --- | --- |</code> ngay dưới dòng tiêu đề.</li>
<li><strong>Task List thiếu khoảng trắng:</strong> Cần viết <code>- [x]</code> và <code>- [ ]</code>, không viết <code>-[x]</code> hoặc <code>-[ ]</code>.</li>
</ol>

