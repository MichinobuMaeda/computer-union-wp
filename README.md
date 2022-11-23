# computer-union.jp WP テスト環境

## このプロジェクトの初期構築

```bash
gh repo create computer-union-wp --public --clone
cd computer-union-wp
echo "# computer-union.jp WP テスト環境" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git push -u origin main
```
