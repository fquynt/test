Danh sách các quy định pháp lý bắt buộc phải thực hiện khi thiết kế/tạo website ở Đức (áp dụng EU/DSGVO). Tôi liệt kê theo thứ tự ưu tiên, dựa trên TMG, DSGVO, TDDDG và eAA. [ihk-muenchen](https://www.ihk-muenchen.de/ratgeber/recht/internetrecht/rechtssicherheit/)

## Danh sách Quy định Bắt buộc

- **Impressum (Thông tin nhà cung cấp)**: Trang riêng dễ tìm (tối đa 2 click từ mọi trang), chứa tên đầy đủ, địa chỉ Đức, email, số ĐT, USt-ID (nếu có), Handelsregister (nếu áp dụng). Bắt buộc cho mọi site kinh doanh/blog. [rechtecheck](https://rechtecheck.de/impressumspflicht-was-muss-rein/)
- **Datenschutzerklärung (Tuyên bố bảo vệ dữ liệu)**: Chi tiết dữ liệu thu thập (IP, cookies), mục đích, cơ sở pháp lý, quyền người dùng (xóa, rút consent). Liên kết từ footer/banner. [ihk](https://www.ihk.de/regensburg/fachthemen/recht/online-recht-und-datenschutz/eu-datenschutzgrundverordnung/anforderungen-an-websites-nach-der-ds-gvo-4158848)
- **Cookie Consent Banner**: Pop-up xin phép trước khi set non-essential cookies (tracking, analytics). Có nút "Akzeptieren" và "Ablehnen" rõ ràng, dễ từ chối ngang nhau; link chi tiết cookies. [ccm19](https://www.ccm19.de/cookie-banner-plicht.html)
- **HTTPS/SSL Encryption**: Toàn bộ site phải mã hóa (https://), không http. [barth-datenschutz](https://barth-datenschutz.de/dsgvo-website-checkliste/)
- **Barrierefreiheit (eAA từ 28/6/2025)**: Tuân thủ WCAG 2.1/2.2 AA - alt text ảnh, contrast cao, keyboard nav, screen reader. Thêm trang Erklärung Barrierefreiheit + form feedback. [getresponse](https://www.getresponse.com/de/hilfe/was-ist-der-european-accessibility-act-eaa-2025.html)
- **Kontaktformular (Form liên hệ)**: Chỉ lưu dữ liệu cần, xin consent, không forward email tự động nếu vi phạm DSGVO. [ihk](https://www.ihk.de/regensburg/fachthemen/recht/online-recht-und-datenschutz/eu-datenschutzgrundverordnung/anforderungen-an-websites-nach-der-ds-gvo-4158848)
- **Tracking/Analytics (Google Analytics, etc.)**: Chỉ sau consent; dùng server-side nếu có thể, anonymize IP. [ihk](https://www.ihk.de/regensburg/fachthemen/recht/online-recht-und-datenschutz/eu-datenschutzgrundverordnung/anforderungen-an-websites-nach-der-ds-gvo-4158848)
- **Social Plugins/Embeds (Facebook, YouTube)**: Lazy load sau consent; tránh inline scripts. [ihk](https://www.ihk.de/regensburg/fachthemen/recht/online-recht-und-datenschutz/eu-datenschutzgrundverordnung/anforderungen-an-websites-nach-der-ds-gvo-4158848)
- **Google Fonts/External Fonts**: Self-host hoặc consent; tránh leak IP. [ihk](https://www.ihk.de/regensburg/fachthemen/recht/online-recht-und-datenschutz/eu-datenschutzgrundverordnung/anforderungen-an-websites-nach-der-ds-gvo-4158848)
- **Hosting & Logs**: Chọn host EU-compliant, xóa logfiles định kỳ, không lưu IP lâu. [ihk](https://www.ihk.de/regensburg/fachthemen/recht/online-recht-und-datenschutz/eu-datenschutzgrundverordnung/anforderungen-an-websites-nach-der-ds-gvo-4158848)

Thực hiện checklist này để tránh Abmahnung (cảnh cáo pháp lý) và phạt. Với domain .de của bạn, dùng công cụ như eRecht24 để generate tự động. [xovi](https://www.xovi.de/dsgvo-checkliste-die-10-wichtigsten-to-dos-fuer-ihre-webseite/)

Yêu cầu bắt buộc:
- Mọi website public có mục đích kinh doanh phải chuẩn bị sẵn Impressum.
- Phải có Datenschutzerklärung nếu website có form liên hệ, analytics, tracking, map, font ngoài, reCAPTCHA, pixel, hoặc bất kỳ xử lý dữ liệu cá nhân nào.
- Nếu dùng cookie/tracker không cần thiết, phải có cookie consent trước khi kích hoạt tracking.
- Không được tự bịa thông tin pháp lý; nếu thiếu dữ liệu công ty thì phải chèn placeholder rõ ràng hoặc cảnh báo cần bổ sung.

Yêu cầu SEO/kỹ thuật:
- Dùng HTML semantic, heading hierarchy đúng, title/meta description rõ ràng, alt text đầy đủ, URL sạch, internal link hợp lý.
- Tối ưu mobile-first, responsive tốt, touch target đủ lớn, accessible cơ bản, contrast tốt, keyboard-friendly.
- Tối ưu Core Web Vitals, ảnh nhẹ, lazy-load, font/load script hợp lý, code sạch và dễ maintain.
- Chỉ dùng nội dung ngắn gọn, rõ dịch vụ, khu vực phục vụ, CTA mạnh và dễ chuyển đổi.

Quy tắc output:
- Khi build landing page/company website, luôn reserve sẵn link hoặc section cho Impressum và Datenschutz trong footer.
- Nếu thiếu thông tin pháp lý bắt buộc, phải nêu rõ mục nào còn thiếu trước khi finalize.
- Không hy sinh pháp lý và tốc độ chỉ để làm website đẹp hơn.
