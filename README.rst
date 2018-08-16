======
Dalton
======

Dalton - Suricata and Snort IDS rule和pcap测试系统
========

Presentation
========
`Efficient Packet Capture Creation and Testing on Suricata - SuriCon2017 <https://github.com/tianyulab/dalton/blob/master/Presentations/SuriCon17-Wharton_Urbanski.pdf>`__

使用指南
========

.. code:: bash

    
1.安装

git clone https://github.com/tianyulab/dalton

cd dalton

docker-compose build

2.启动

docker-compose up -d

docker ps

docker-compose config --service

3.停止

docker-compose down

