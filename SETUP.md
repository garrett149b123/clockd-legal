# Create the public repo on GitHub (one time)

The local folder is ready at `C:\Users\Garrett\clockd-legal`. Push it after creating the repo:

1. Open **https://github.com/new**
2. Repository name: **`clockd-legal`**
3. Visibility: **Public**
4. Do **not** add README, .gitignore, or license (already in local repo)
5. Click **Create repository**
6. In PowerShell:

```powershell
cd C:\Users\Garrett\clockd-legal
git push -u origin main
```

7. Enable Pages: **https://github.com/garrett149b123/clockd-legal/settings/pages**
   - Source: branch **main**, folder **/ (root)**
8. Test (wait ~1 min): **https://garrett149b123.github.io/clockd-legal/privacy-policy.html**

Use that privacy URL and **https://garrett149b123.github.io/clockd-legal/** as Support URL in App Store Connect.
