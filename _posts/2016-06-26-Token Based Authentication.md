#### ����Token����֤�ͻ��������ı�ʶ

> http://codelife.me/blog/2014/03/26/token-based-authentication-and-claims-based-identity/

#### JWT
JWT������һ���ڿͻ��˺ͷ�����֮�����Ͷ����ģ�compact and self-contained��������Ϣ�ķ��������ݵ���Ϣ��������ǩ����HMAC����RSA�����Ǳ���֤�Ϳ��ŵġ�s

- **compact**: smaller size, can be sent through an URL, POST parameter, or inside an HTTP header.

- **self-contained**: The payload contains all the required information about the user, avoiding the need to query the database more than once.

##### JWT Scenarios
- Authentication
alse sso
- Information Exchange

##### How do JWT work?
![](index_files/jwtwork.png)

#### ���㼺��
https://www.v2ex.com/t/148426

#### ϸ��ʵ��

##### token�Ĵ洢�ʹ���
���access token �� refreh token��Ӧ�ô洢���ģ��û����ģ�����ҵ��Ӧ�ã�
�洢��ҵ��Ӧ�õĻ���������̫ǿ��

token��ÿ������������δ��ݵģ�������http header�������Ļ�ʹ��requestwrap��responsewrap

##### token��һ��ʹ�ý���
http://www.haomou.net/2014/08/13/2014_web_token/

##### token benifits
http://stackoverflow.com/questions/1592534/what-is-token-based-authentication


