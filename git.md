## git env

    
    # 大小写敏感
    git config core.ignorecase false

    # 别名
    git config --global alias.st status
    git config --global alias.ci commit
    git config --global alias.co checkout
    git config --global alias.br branch
    git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cd) %C(bold blue)<%an>%Creset' --date=format:'%Y-%m-%d %H:%M:%S' --abbrev-commit"


    # 根据 git config --list  结果看需要配置哪些

    # 当前项目配置
    git config user.name "xx"
    git config user.email "xx@xx.xx"

    # 全局配置
    git config --global user.name "xx"
    git config --global user.email "xx@xx.xx"
