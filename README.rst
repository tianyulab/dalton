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

2.启动

cd dalton

docker-compose build && docker-compose up -d # If you change a service’s Dockerfile or the contents of its build directory, run docker-compose build to rebuild it

docker ps

docker-compose config --service

3.停止

docker-compose down

视频教程
========
`Dalton:Suricata和Snort IDS规则测试系统 <http://v.youku.com/v_show/id_XMzc4MzU1NDk1Ng==.html>`__
