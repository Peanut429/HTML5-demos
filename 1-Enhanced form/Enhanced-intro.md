# HTML5 demos
HTML5�б���������
  (1)�µ�input type  	<input type="?">
	H4�е�input type��text��password��radio��checkbox��file��hidden��submit��reset��image
	H5�е�input type��email��url��number��tel��search��range��color��date��month��week
  (2)�µı�Ԫ��
	H4�еı�Ԫ�أ�input��textarea��select/option��label��button(Ĭ��type��submit)
	H5�������ı�Ԫ�أ�datalist��progress��meter��output
  (3)��Ԫ�ص�������
    1��placeholder ռλ�ַ���
    <input value="tom" placeholder="�������û���">����value��ͬ�����������ύ
      placeholder="��ʾ������"
    2��autofocus �Զ���ȡ���뽹�㡢
    <input autofocus>
      autofocusҳ����ֻҪһ���������������ʱ��Ĭ�ϵ�һ���Զ���ȡ����
      ��js��������ֵĬ��Ϊfalse
    3��multiple ����������г��ֶ�����루�ö��ŷָ�����һ����Ҫ��������������ʹ�ã�������������url�ȡ�
    <input type="email" multiple>
    4��form ���ڰ���������õ�FORM�ⲿ��
    <form id="f5"></form>
    	  <input form="f5">
          ��js��������ֵĬ��Ϊ���������ַ���
     ��input����form����ָ�������ı���id���ĸ�inputҪ�ύ��˭���form����
  	5��required ��������ݲ���Ϊ�ա�
  	<input required>
  	6)maxlength��ָ���ַ�������󳤶�
    <input maxlength="9">������9�Ͳ�������
    7)minlength��ָ���ַ�������С����
    <input minlength="6"> �������������minlength����Ч��������ô���requiredһ��ʹ��
    8)max��ָ�����ֵ����ֵ
   	<input max="60">
    9)min��ָ�����ֵ���Сֵ
    <input min="18">
    10)pattern��ָ�����������ϵ�������ʽ
    <input pattern="^1[35789]\d{9}$">   ^$����ʡ�Բ�д
      ֻ�������������²���Ч��������require����ʹ��
    <input type="tel"/>�����������������֤
         ����6����������Ŀ�л�������ô�ã���ʽ̫�󣬲����Զ���
    ������֤���Ի�Ӱ���Ԫ�ض�Ӧ��JS�����validity���ԡ�
  (4)H5��������֤��ص�JS��������
    input.validity {			��������֤��Ч��
  	badInput:	false			��Ч�����룬��number������ĸ
  	customError:false		�����Զ������
  	patternMismatch:false	��ƥ��ָ����������ʽ
  	rangeOverflow:false	ֵ�����
  	rangeUnderflow:false	ֵ�����
  	stepMismatch:false		������ƥ��
  	tooLong:false			����̫��
  	tooShort:false			����̫��
  	typeMismatch:false		���Ͳ�ƥ��
  	valueMissing:false		ֵȱʧ
  	valid:true				��ǰ����ֵ��Ч
  }