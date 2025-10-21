---
title: "Java cơ bản: Bắt đầu nhanh và cấu trúc dự án"
date: 2025-10-21
draft: false
tags: ["java", "cơ bản"]
categories: ["Lập trình"]
---

<p style="text-align:center;margin-bottom:1rem;"><img src="https://images.unsplash.com/photo-1526378728711-3b3f5d9f1f9b?q=80&w=1600&auto=format&fit=crop" alt="Java programming" style="width:100%;max-width:1200px;height:auto;border-radius:8px;"/></p>

Java là một trong những ngôn ngữ lập trình phổ biến, mạnh mẽ và được sử dụng rộng rãi trong doanh nghiệp. Bài viết này hướng dẫn bạn từ việc cài đặt, cấu trúc dự án đến các khái niệm OOP cơ bản.

### 1. Cài đặt
- Tải JDK (OpenJDK hoặc Oracle JDK) và thiết lập biến môi trường JAVA_HOME.
- Dùng Maven hoặc Gradle để quản lý phụ thuộc.

### 2. Cấu trúc dự án tham khảo (Maven)

```
my-app/
├─ src/main/java/com/example/app
│  └─ App.java
├─ src/test/java
└─ pom.xml
```

### 3. Nguyên tắc OOP cơ bản
- Lớp và đối tượng, kế thừa, đóng gói, đa hình, trừu tượng.
- Ví dụ lớp đơn giản:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

### 4. Mẹo thực hành
- Viết unit test sớm (JUnit / Mockito).
- Sử dụng linter/formatter và tuân theo chuẩn đặt tên.

### 5. Tài nguyên tham khảo
- Oracle Java docs, Baeldung, StackOverflow.

Kết luận: nắm vững cấu trúc và OOP sẽ giúp bạn tiến nhanh khi học các framework Java hiện đại.
