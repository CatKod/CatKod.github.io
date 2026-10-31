<div align="center">

# Hoàng Kim Vĩnh — Portfolio

**Embedded Firmware Engineer** · Industrial IoT · Edge AI

[![Live site](https://img.shields.io/badge/live-catkod.github.io-47D3A5?style=flat-square)](https://catkod.github.io/)
[![CV](https://img.shields.io/badge/CV-PDF-E5484D?style=flat-square)](https://catkod.github.io/pdf/CV_Hoang-Kim-Vinh_2026.pdf)

</div>

---

## Site

Trang portfolio tĩnh, dựng bằng Next.js App Router (static export).

| Route | Nội dung |
| --- | --- |
| `/` | Trang chủ — hero, tổng quan |
| `/about` | Về tôi, hành trình, GitHub activity |
| `/work` | Kho dự án |
| `/skills` | Bộ kỹ năng theo nhóm |
| `/credentials` | Chứng chỉ, giải thưởng, học vấn |
| `/guestbook` | Sổ ghi chú |
| `/contact` | Liên hệ |

**Link trực tiếp:** https://catkod.github.io/

## Cấu trúc thư mục

```
index.html            # Trang chủ
about/ work/ ...      # Mỗi route là thư mục chứa index.html
_next/                # Asset của Next.js (bắt đầu bằng _ nên cần .nojekyll)
images/ pdf/          # Hình ảnh dự án, CV PDF
.nojekyll             # Tắt Jekyll để _next/ được phục vụ nguyên vẹn
```

`.nojekyll` là bắt buộc: nếu không có, Jekyll sẽ bỏ qua thư mục `_next/` và site sẽ mất toàn bộ CSS/JS.

## Nguồn

Mã nguồn Next.js và bộ công cụ dựng/kiểm thử nằm ở repo
[`CatKod/My_Portfolio_CatKod`](https://github.com/CatKod/My_Portfolio_CatKod).

Profile README đầy đủ (kỹ năng, dự án, chứng chỉ): [`CatKod/CatKod`](https://github.com/CatKod/CatKod).

---

Hoàng Kim Vĩnh (CatKod) · HUST · Embedded / IoT Engineer
