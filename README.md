Git steps

git clone https://github.com/BhushanLande/CI_CD_ProjectNew

git checkout practice -b
change code
git add .
git config --global user.name "BhushanLande"
git commit -m "Branch code"
git push --set-upstream origin practice

https://github.com/settings/tokens
Click "Generate new token (classic)"
Select the following scopes:
✅ repo (for private repositories)
✅ workflow (for GitHub Actions, optional)
Click "Generate token" and copy the token.
and username BhushanLande or b.lande525@gmail.com
pass user key

git config --global credential.helper store


