# computer-union.jp WP テスト環境

## 参考: このプロジェクトの初期構築

```bash
gh repo create computer-union-wp --public --clone
cd computer-union-wp
echo "# computer-union.jp WP テスト環境" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git push -u origin main
```

<https://github.com/MichinobuMaeda/computer-union-wp/>

- <> Code
    - Codespaces
        - Set up prebuilds
            - branch: main
            - Configuration File: Default Codespaces Configuration
            - Prebuild triggers: On configuration change
            - Region availability: Southeast Asia
