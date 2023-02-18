# sohoroom.github.io
sohoroom's github pages
branch: main or master 兩者差異在哪？

"""最近在使用 GitHub 的時候應該會發現現在 default branch 變成的 main，原因可以參考 iThome [GitHub 10月起將以Main取代Master作為新Git儲存庫預設名稱]，可是這樣跟我們原本習慣的變得不一樣，可能有很多套件也會因此有點問題，那我們要怎麼把它改回來呢？"""2020年10月起master主分支變成以main取代

很抱歉直到現在才回复您。你在說命令Git: Initialise Repository嗎？git init單擊該按鈕實際上將在打開的文件夾中執行。目前，執行時的默認分支名稱git init是master，但這在未來可能會改變，並且可以使用init.defaultBranch(ex git config --global init.defaultBranch main:) 進行控制。更改預設分支，注意git版本需高於2.28以上才升效

git branch --set-upstream-to=origin/main main
更改上傳的分支名?
