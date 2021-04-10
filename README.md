# 实验室每日打卡计划

这个计划主要是为了帮助大家熟悉多人使用`git`合并代码的过程

## 主要步骤

1. `Fork`这个仓库到自己的仓库
2. 然后在自己的仓库里提交代码
3. 接着提交PR（Pull requests），请求将自己仓库的分支合并到实验室主仓库分支
4. 到 https://github.com/zustcs/sign-in-git/pulls 手动合并代码

## 上传格式

每日新建一个`md`文件

例如现在是`2021.4.10`

那么创建文件`10.md`，并且放在`2021`/`4`/这个目录下面

文件内容的填写如下

打卡人部分填写自己的`git`账号名

代码部分填写今天写的代码地址（每天写的代码都要更新到自己的仓库，实在没有就写无好了）

```markdown
| 打卡人  |               代码地址                |
| :-----: | :-----------------------------------: |
| Junzzzz | https://github.com/zustcs/sign-in-git |
```

展示效果如下：

| 打卡人  |               代码地址                |
| :-----: | :-----------------------------------: |
| Junzzzz | https://github.com/zustcs/sign-in-git |

## 合并流程

进入`Pull requests`选项卡

点击绿色的`New pull request`

一般会自动分析要合并的内容，然后填写合并的说明，就会来到下面这个页面

![PR](https://i.loli.net/2021/04/10/sCT87eyQR1FAmcp.png)

如上图所示

`2021.4.10`是写合并的说明，比如你跟仓库管理者说：我修复了XXXBUG，用来解释你提交PR的原因

再下一行`样例提交`那块区域是你的`commit`记录，你可以好几次commit后一次性提交PR

`This branch has no conflicts with the base branch`指的是没有冲突的代码，可以自动合并，有冲突部分需要手动合并

然后点击绿色的`Merge pull request`

![Merge](https://i.loli.net/2021/04/10/nU2tQ9NIZsu6rkx.png)

第一个框内填写的是`commit`信息，相当于用的`git commit -m "Merge pull request..."`

第二个框内填写的是说明

然后点`Confirm merge`就合并成功啦！

## 注意

如果忘记了`Git`的操作可以看看以前发的教程（虽然感觉写的一般）

接下来可能要布置多人完成的项目，先让大家熟悉一下~