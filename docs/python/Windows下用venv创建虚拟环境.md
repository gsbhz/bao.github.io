## 1.����һ�����⻷��
``` bash
D:\>mkdir my_venv
D:\>cd my_venv
D:\my_venv>python -m venv venv1
```

����python -m venv venv1,����һ��venv1�����⻷��������Ŀ¼��ʽ���£�

```
venv1
  ��  pyvenv.cfg
  ��  
  ����Include
  ����Lib
  ����Scripts
```

## 2.�������⻷��
``` bash
D:\my_venv>venv1\Scripts\activate.bat
(venv1) D:\my_venv
```

## 3.pip�����⻷����װģ��
���Ȳ鿴Ŀǰ���⻷�����е�ģ�飺
``` bash
(venv1) D:\my_venv>pip list
pip (8.1.1)
setuptools (20.10.1)
You are using pip version 8.1.1, however version 8.1.2 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.
```

��ʾpip���°汾������ʾpython -m pip install --upgrade pip ������¾ͺã�ǧ�����pip install --upgrade pip���������ƻ�pip

## 4.�˳����⻷��

``` bash
(venv1) D:\my_venv>test\Scripts\deactivate.bat
D:\my_venv>
```