# algebra-for-cute-girls
喵！

欢迎来到《给萌妹子看的代数书：Galois男神我爱你》的小仓库~

你可能发现了这里只有一个Github Pages页面的源代码，那是因为书的源代码在[writing分支](https://github.com/zhangyutong926/algebra-for-cute-girls/tree/writing)里面。所以你要用
```bash
git clone -b writing https://github.com/zhangyutong926/algebra-for-cute-girls.git
```
来clone这里面的代码，而push的时候要
```bash
git push origin writing:writing
```

你需要MikTeX或MacTeX或TeX Live来编译这个文档，如果找不到`gb7714.sty`的话可能还需要手动安装一下，不会的话来问我呀（联系方式在下面↓）。编译的指令是`xelatex -> bibtex -> xelatex * 2`。当然如果你是collaborator的话你直接提交用我的[Jenkins CI](http://vps.sayako.blog:8080/)来编译然后看artifacts也可以啦。

然后是Telegram群：https://t.me/sayako_book_writing
以及Sayako的telegram：https://t.me/zhangyutong926
