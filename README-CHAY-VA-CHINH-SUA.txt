HUONG DAN CHAY BRI MED (Windows)

1. Giai nen file ZIP nay.
2. Mo VS Code > File > Open Folder... > chon thu muc BriMed-Brimed-BA da giai nen.
3. Neu npm chua nhan lenh: dong hoan toan VS Code, mo lai. Neu van loi, mo Command Prompt/PowerShell moi va go: node -v roi npm -v. Neu van bao khong nhan dien, can cai Node.js LTS va tick Add to PATH.
4. Trong VS Code, mo Terminal > New Terminal. Dam bao duong dan Terminal ket thuc bang \BriMed-Brimed-BA.
5. Chay tung lenh, moi lenh bam Enter va doi chay xong:
   npm run setup
6. Khi setup hoan tat, chay:
   npm run dev
7. Mo trinh duyet vao http://localhost:5173

CHINH FONT VA MAU LOGO
- Font Be Vietnam Pro da duoc dat cho giao dien chung va cac tieu de landing page.
- Chu Med tren logo chu da doi sang mau xanh giong Bri.
- File CSS chinh: web/src/index.css va web/src/components/landing/landing.css
- Neu muon doi mau xanh: tim --blue: #0d71e2 trong landing.css; mau chung nam o web/tailwind.config.js (primary).

LUU Y
- Day la du an React/Vite, khong the chay dung bang cach bam mo index.html truc tiep. Can chay npm run dev.
- Lenh npm run setup chi can chay lan dau (hoac khi can cai lai thu vien).
