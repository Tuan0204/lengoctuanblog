# Async/Await trong JavaScript: Quản lý bất đồng bộ dễ dàng


<p style="text-align:center;margin-bottom:1rem;"><img src="https://images.unsplash.com/photo-1505238680356-667803448bb6?q=80&w=1600&auto=format&fit=crop" alt="Async JavaScript" style="width:100%;max-width:1200px;height:auto;border-radius:8px;"/></p>

Async/Await là một cú pháp để viết mã bất đồng bộ trông giống như đồng bộ, dựa trên Promise.

### Ví dụ

```javascript
async function fetchData() {
  try {
    const res = await fetch('https://api.example.com/data');
    const json = await res.json();
    return json;
  } catch (err) {
    console.error(err);
  }
}
```

Sử dụng async/await giúp xử lý lỗi dễ dàng hơn so với chuỗi .then/.catch.

