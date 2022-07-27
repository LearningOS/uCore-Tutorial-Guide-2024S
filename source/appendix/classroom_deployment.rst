=======================
github classroom部署说明
=======================
1.使用github账号登录github classroom，然后给github classroom授权。接下来根据提示创建classroom和organization。
.. image:: classroom_deployment1.png

2.在classroom添加合作者（其他管理员或助教）、学生。

3.创建作业（assignment）。首先可以根据需要设置仓库的可见性和学生对仓库的使用权限，然后选择同一organization下的实验代码基准仓库（必须设置仓库为模板仓库）作为模板，最后由于实验代码基准仓库中配置了自动测试的脚本，因此再创建assignment时不需要添加测试。

4.拷贝classroom邀请链接分享给学生，学生同意邀请后即可加入classroom，并且classroom会为学生自动创建学生个人的实验代码基准仓库，让学生能够在该仓库中进行实验。

参考链接：https://docs.github.com/en/education/manage-coursework-with-github-classroom/get-started-with-github-classroom
