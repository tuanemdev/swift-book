# Swift Book - Sách học Swift và SwiftUI

## Mô tả

Cuốn sách này cung cấp các kiến thức nâng cao về:

- **Swift**: Ngôn ngữ lập trình hiện đại, mạnh mẽ và dễ học -
  [swiftlang](https://github.com/swiftlang/swift)
- **SwiftUI**: [Framework](https://developer.apple.com/tutorials/swiftui/) để
  xây dựng giao diện người dùng, đa nền tảng trên hệ sinh thái của Apple

Nội dung được tổ chức theo chủ đề, phù hợp với những người đã có những kiến thức
cơ bản về lập trình và ngôn ngữ lập trình Swift.

## Công cụ sử dụng

Dự án này sử dụng [mdBook](https://github.com/rust-lang/mdBook) để tạo sách điện
tử từ các file Markdown.

## Cài đặt

### Các bước cài đặt

1. Cài đặt [Rust](https://www.rust-lang.org/)

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

2. Cài đặt [cargo-binstall](https://github.com/cargo-bins/cargo-binstall)

```bash
curl -L --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/cargo-bins/cargo-binstall/main/install-from-binstall-release.sh | bash
```

3. Cài đặt mdBook

```bash
cargo binstall mdbook
```

4. Cài đặt mdbook-katex

```bash
cargo binstall mdbook-katex
```

## Sử dụng

### Build dự án

```bash
mdbook build
```

### Xem trước sách

```bash
mdbook serve
```

Sau khi chạy lệnh trên, mở trình duyệt và truy cập `http://localhost:3000/` để
xem sách.

## Đóng góp

Mình rất hoan nghênh mọi đóng góp từ cộng đồng!

### Báo cáo lỗi hoặc đề xuất tính năng

Tạo [Issues](https://github.com/tuanemdev/swift-book/issues)

### Đóng góp nội dung

Tạo [Pull Request](https://github.com/tuanemdev/swift-book/pulls)

### Hướng dẫn viết nội dung

Đọc tài liệu [mdbook](https://rust-lang.github.io/mdBook/) để học cách viết nội
dung

Cài đặt extension `Prettier - Code formatter` hỗ trợ format nội dung file
Markdown

## Liên hệ

admin@tuanem.com
