# Deploy len Vercel

Du an nay la static app (HTML/CSS/JS) nen deploy tren Vercel rat nhanh.

## 1) Cai Vercel CLI

```powershell
npm install -g vercel
```

## 2) Di chuyen vao thu muc du an

```powershell
cd "c:\Users\ADMIN\Downloads\SQA APP"
```

## 3) Dang nhap Vercel

```powershell
vercel login
```

## 4) Deploy production

```powershell
vercel --prod
```

## Luu y

- File `vercel.json` da duoc tao de route `/` -> `/app.html`.
- Sau khi chay `vercel --prod`, CLI se tra ve URL production.
