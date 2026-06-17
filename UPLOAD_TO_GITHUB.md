# GitHub 업로드 방법

이 폴더의 파일들을 새 GitHub Repository 루트에 올리면 됩니다.

## 브라우저로 업로드

1. GitHub에서 새 Repository를 만듭니다.
2. `Add file` → `Upload files`를 누릅니다.
3. 이 폴더 안의 파일 전체를 업로드합니다.
   - `index.html`
   - `app.js`
   - `styles.css`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `icon.svg`
   - `standalone.html`
   - `README.md`
   - `.nojekyll`
4. `Commit changes`를 누릅니다.
5. GitHub Pages로 배포하려면 `Settings` → `Pages`에서 `Deploy from a branch`를 선택하고 `main` / `/root`를 지정합니다.

## 터미널로 업로드

```bash
unzip fta-kkoong-ai-helper-v0.9.3-github-ready.zip
cd fta-kkoong-ai-helper-github-ready

git init
git add .
git commit -m "Add kkoong finance investment analyst AI helper v0.9.3"
git branch -M main
git remote add origin https://github.com/YOUR_ID/YOUR_REPO.git
git push -u origin main
```

GitHub Pages 배포는 Repository의 `Settings` → `Pages`에서 `main` / `/root`를 선택하면 됩니다.
