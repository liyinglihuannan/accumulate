/**
   * ��ȡ��ǰURL����ֵ
   * @param name	��������
   * @return	����ֵ
   */
  getUrlParam(name) {
    var reg = new RegExp('[?&]'+name+'=([^&#]+)');
    var r = window.location.hash.substr(1).match(reg);
    if (r != null) return unescape(r[1]);
    return "";
  }

//���磺http://localhost:8080/#/wqq/res/resList/detail?resGroupId=151#1

�ο����ϣ�
https://blog.csdn.net/wqq1018893786/article/details/73895250
