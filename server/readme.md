#�׼�ֱ��qpluslive����������

##���
����Ŀ���׼�ֱ���ͻ���[QPlusLive For IOS]()��ֱ��ҵ���������

����Ŀ��ʹ��Golang��д��ֱ��ҵ�������������ֱ�����У�Ϊ�˷����Ҳ���ʹ�ã�����ʹ���ѱ���汾��[�������]
()

����Ŀ������װȫ��ֱ��APP����ƣ�Ŀǰ��1.0�汾�����ڻ᲻�ϸ��£������ڴ���

## ʹ�÷�ʽ
����Ŀ��Ҫʹ��Mysql,��������ϵͳ�ð�װMysql��

�������ݿ�ͱ���SQL�ű�Ϊgotye_open_live.sql, ���ؽ�ѹ���.tar.gz��������С�

ѹ�������ṩ�˱���õ�֧��`Linux`�Ŀ�ִ���ļ���

ѹ�����е�`config.ini`�Ƿ������������ļ������е������밲��ʽ�޸�, ����˵������:
```
[apiserver]
#�����������˿�
http_port = 8080

[mysql]
#���ݿ��ַ
address = 192.168.1.10
#���ݿ���
dbname  = gotye_open_live
#���ݿ��˺�
account = app
#���ݿ�����
password = 123456
```
ѹ�����е�`run`�Ƿ����������ű���ʹ��˵������:
run -s or start : ��������������
run -k or stop  : �رշ���������
run -i or info  : �鿴��������Ϣ
run -h or help  : ��ýű�ʹ��˵��

##API˵��
��鿴[API](api_doc.md)

