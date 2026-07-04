# nmattt

Web trắc nghiệm tĩnh từ file `nmattt_ocr_quiz_phan_loai_nguon_bo_sung.html`.

## Chạy local

Mở trực tiếp `index.html` trong trình duyệt, hoặc chạy server tĩnh:

```powershell
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000`.

## Deploy GitHub Pages

Repo đã kèm workflow tại `.github/workflows/deploy-pages.yml`.

Sau khi đẩy repo này lên GitHub:

1. Vào `Settings > Pages`.
2. Chọn `Build and deployment` là `GitHub Actions` nếu GitHub chưa tự nhận.
3. Push lên nhánh `main` để GitHub build và publish.

URL thường có dạng:

`https://<github-username>.github.io/nmattt/`
"# nmattt" 
