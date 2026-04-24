
# Upload File via GitHub Workflow
```
این ریپوزیتوری شامل یک کد ورک‌فلو است که فایل‌هایی با لینک مستقیم را در مخزن آپلود می‌کند.
```
## نحوه استفاده

1. مخزن را کلون کنید:
   ```bash
   git clone <https://github.com/kingowow/Download-file.git>
   ```

2. به پوشه `.github/workflows` بروید و فایل `download-file.yml` را باز و ویرایش کنید.

3. در فایل `download-file.yml`، مقادیر زیر را با اطلاعات فایل مورد نظر خود جایگزین کنید:
   ```yaml
   FILE_URL: https://github.com/kingowow/kingo.team/releases/download/vx.x/name.apk
   FILE_NAME: name.apk
   ```

4. تغییرات را ذخیره کنید و ورک‌فلو را اجرا کنید تا فایل مورد نظر در مخزن آپلود شود.

---

t.me/kingo_team