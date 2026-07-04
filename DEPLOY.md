# Deploy `nmattt` len GitHub Pages

Repo nay da co san `index.html`, vi vay co the publish nhu mot static site.

## 1. Day code len GitHub

Chay trong thu muc repo:

```powershell
git add index.html .github/workflows/deploy-pages.yml .nojekyll README.md DEPLOY.md
git commit -m "Setup quiz website for GitHub Pages"
git push origin main
```

Neu muon luu ca file nguon goc:

```powershell
git add nmattt_ocr_quiz_phan_loai_nguon_bo_sung.html
git commit -m "Add original quiz source HTML"
git push origin main
```

## 2. Bat GitHub Pages

Vao:

`Settings` -> `Pages`

Tai muc `Build and deployment`, chon:

- `Source`: `GitHub Actions`

## 3. URL public

Sau khi workflow chay xong, site thuong se co URL:

`https://jozznothing.github.io/nmattt/`

## 4. Test nhanh

- Mo URL tren trinh duyet an danh.
- Thu lam bai va reload lai trang.
- Neu tieng Viet bi loi dau, can mo `index.html` va save lai dung encoding `UTF-8`.
