---
title: "Java Streams và Collections: Xử lý dữ liệu hiệu quả"
date: 2025-10-21
draft: false
tags: ["java", "streams", "collections"]
categories: ["Lập trình"]
---

<p style="text-align:center;margin-bottom:1rem;"><img src="https://images.unsplash.com/photo-1532619675605-0f4e1f3d6f8b?q=80&w=1600&auto=format&fit=crop" alt="Java streams" style="width:100%;max-width:1200px;height:auto;border-radius:8px;"/></p>

Trong Java 8 trở lên, Streams API cung cấp cách khai báo, nối chuỗi và xử lý tập hợp dữ liệu một cách dễ đọc và hiệu quả.

### Ví dụ cơ bản

```java
List<String> names = Arrays.asList("An", "Binh", "Cuong");
List<String> filtered = names.stream()
    .filter(s -> s.length() > 3)
    .map(String::toUpperCase)
    .collect(Collectors.toList());
```

### Tips tối ưu
- Tránh dùng stream trong vòng lặp nặng, cân nhắc song song (parallelStream) khi tập dữ liệu lớn.
- Sử dụng Collector để gom nhóm, tính toán tổng hợp.

Streams kết hợp Collections giúp code ngắn gọn, dễ hiểu và dễ maintain.
