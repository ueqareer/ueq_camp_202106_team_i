# Gitの使い方

以下のURLを参考にする

<https://qiita.com/sekiyaeiji/items/d0312c90bff4c37bc5dc>

とりあえず，git cloneだけ載せておく

これをクローンさせたいディレクトリで打つ

```bash
git clone https://github.com/ueqareer/ueq_camp_202106_team_i.git
```

# 注意点
上のURLでは，デフォルトのリポジトリがmasterになっているが，現在ではmainになっているので注意

# 以下はデフォルトのREADMEファイルに書かれていた内容

# …or create a new repository on the command line

```bash
echo "# ueq_camp_202106_team_i" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ueqareer/ueq_camp_202106_team_i.git
git push -u origin main
```

# …or push an existing repository from the command line
```bash
git remote add origin https://github.com/ueqareer/ueq_camp_202106_team_i.git
git branch -M main
git push -u origin main
```

# …or import code from another repository 
```bash
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
```