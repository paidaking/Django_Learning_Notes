# Django_Learning_Notes

书名：《python编程：从入门到实践》（python3实现，django版本1.11，win10系统）

18章 django入门

1. 建立项目
  新建一个项目目录，将其命名为learning_log
  从次文件夹启动命令行
  创建虚拟环境：python -m venv 11_env # 运行模块venv，创建一个名为ll_env的虚拟环境（venv文python自带模块，若此方法行不通可用virtualenv，使用方法：   virtualenv ll_env）
  激活虚拟环境：11_env\Scripts\activate
  (停止虚拟环境方法：deactivate)
  安装django：pip install django==1.11
  在django中创建项目：django-admin startproject learning_log . ( . 别忘了加 learning_log为项目名)
  创建数据库：python manage.py migrate
  查看项目：python manage.py runserver
  终端窗口结束runserver方法：ctrl+c
  
2. 创建应用程序
  激活虚拟环境：11_env\Scripts\activate
  执行命令python manage.py startapp learning_logs
  定义模型：打开 learning_logs\models.py文件
           编辑：class Topic(models.Model):
                    """用户学习的主题"""
                    text = models.CharField(max_length=200)
                    date_added = models.DateTimeField(auto_now_add=True)
                    def __str__(self):
                        """返回模型的字符串表示"""
                        return self.text
