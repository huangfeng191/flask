1.安装virtualenv

pip install virtualenv
2.查看python解释器路径

where python
3.创建一个python3虚拟环境

win+R输入cmd按回车，然后：
D:
cd D:\VScodeProjects\PythonProjects\opms
virtualenv venv -p "C:\Users\test\AppData\Local\Programs\Python\Python37-32\python.exe" 
4.激活虚拟环境以及取消激活状态

cd D:\VScodeProjects\PythonProjects\opms\venv\Scripts
activate
deactivate.bat