# Publish — branch: release/second-year-physics

جاهز للنشر على GitHub. الشبكة شغالة من البيئة، محتاج بس عنوان المستودع + تفويض.

## 1) لو المستودع موجود بالفعل:
```bash
git remote add origin https://github.com/<USERNAME>/<REPO>.git
git push -u origin release/second-year-physics
```

## 2) لو عايز تفتحه من هنا بالتوكن (اكتب التوكن في أمر create أو مرّره لي):
```bash
export GH_TOKEN=<PAT-with-repo-scope>
curl -s -H "Authorization: Bearer $GH_TOKEN" https://api.github.com/user | grep '"login"'   # تحقق من الحساب
# ثم أنشئ المستودع وادفع الفرع
```

## 3) بدون وصول لـ GitHub عندك — استخدم الـ bundle:
```bash
git fetch publish-release-second-year-physics.bundle release/second-year-physics:release/second-year-physics
git push -u origin release/second-year-physics
```
