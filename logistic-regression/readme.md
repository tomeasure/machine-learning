Ubuntu 16.04</br>
包含两个文件夹data/、lib/和一个shell脚本bash_this.sh</br>
文件夹分别用于存放数据和模块</br>
bash_this.sh用于执行模块，并将结果存储在log文件中，具体步骤：</br>
* 先执行lib/下的generate_data.py</br>
* 再执行lib/下的regression.py</br>
