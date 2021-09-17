# JupyterLab安装流程
在windows或者linux系统下只要安装python以及python里面的pip即可以通过命令行直接安装JupyterLab，代码如下：  
pip install jupyterlab  
然后可以在命令行里通过以下代码来启动JupyterLab：  
jupyter lab  
JupyterLab是自带python解释器的，所以在python上面运行的程序不需要再继续安装python解释器，但相关的包需要通过pip再进行安装。  
JupyterLab需要安装R语言的依赖，具体来说就是在R语言的命令行当中使用以下命令安装一个包：
devtools::install_github('IRkernel/IRkernel')//直接使用install.packages安装也行  
然后重新启动JupyterLab即可。