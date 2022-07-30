
## anconda更新

>conda update conda

## 管理环境
1. 创建环境并安装软件包
>conda create --name *envname* *packagename*
>如果要规定环境需要之后加上例如：python=3.5
2. 激活环境
> conda activate *envname*
3. 查看所有环境列表
> conda info --envs </br>
*活动环境是带有(\*)的*
4. 将当前环境改为默认环境（base）
> conda activate
5. 验证当前环境中python版本
> python version

## 管理软件包
1. 激活环境

> conda activate *envname*
2. 查找是否安装软件包

> conda search *packagename*
3. 安装软件包到当前环境

> conda install *packagename*
4. 检查是否安装在此环节

> conda list




