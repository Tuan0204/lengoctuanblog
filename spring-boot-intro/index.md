# Spring Boot cơ bản: Xây dựng REST API nhanh chóng


<p style="text-align:center;margin-bottom:1rem;"><img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?q=80&w=1600&auto=format&fit=crop" alt="Spring Boot" style="width:100%;max-width:1200px;height:auto;border-radius:8px;"/></p>

Spring Boot giúp khởi tạo ứng dụng Java với cấu hình tối thiểu. Đây là hướng dẫn tạo REST API đầu tiên.

### 1. Khởi tạo project
- Dùng Spring Initializr hoặc start.spring.io, chọn Web, Lombok (tùy), JPA nếu cần DB.

### 2. Controller mẫu

```java
@RestController
public class HelloController {
    @GetMapping("/api/hello")
    public String hello() {
        return "Hello from Spring Boot";
    }
}
```

### 3. Kết nối database
- Sử dụng Spring Data JPA và cấu hình datasource trong application.properties.

Spring Boot phù hợp cho microservices và ứng dụng doanh nghiệp nhỏ.

