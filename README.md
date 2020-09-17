Last login: Thu Sep 17 09:48:16 on ttys000
semthijssen@MacBook-Pro-van-Sem flex-pythonextra % git init
Reinitialized existing Git repository in /Users/semthijssen/Documents/flex-pythonextra/.git/
semthijssen@MacBook-Pro-van-Sem flex-pythonextra % https://github.com/SemThijssen/flex-pythonextra.git
zsh: no such file or directory: https://github.com/SemThijssen/flex-pythonextra.git
semthijssen@MacBook-Pro-van-Sem flex-pythonextra % git remote add originhttps://github.com/SemThijssen/flex-pythonextra.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from

semthijssen@MacBook-Pro-van-Sem flex-pythonextra % git remote -v
origin	https://github.com/SemThijssen/flex-pythonextra.git (fetch)
origin	https://github.com/SemThijssen/flex-pythonextra.git (push)
semthijssen@MacBook-Pro-van-Sem flex-pythonextra % git pull origin master
From https://github.com/SemThijssen/flex-pythonextra
 * branch            master     -> FETCH_HEAD
Already up to date.
semthijssen@MacBook-Pro-van-Sem flex-pythonextra % 
Sem Thijssen SD1Bb