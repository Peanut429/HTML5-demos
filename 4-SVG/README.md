### SVG��ͼ
* Scalable Vector Graph�������ŵ�ʸ��ͼ
	            Canvas��ͼ	                    SVG��ͼ
    ����	        2Dλͼ	                        2Dʸ��ͼ
    �Ŵ�      	ʧ��      	                    ����ʧ��
    ��λ�ͼ	    ʹ��JS�����ͼ	                ʹ�ñ�ǩ/Ԫ�ػ�ͼ
    �¼���	   ÿ��ͼ�β���Ԫ�أ��޷�ֱ�Ӱ��¼�	ÿ��ͼ�ζ���Ԫ�أ�����ֱ�Ӱ��¼�����
Web��ĿӦ�ó���	ͳ��ͼ����Ϸ��(����)	            ͳ��ͼ��ͼ�ꡢ��ͼ

* ʹ��SVG���л�ͼ��������
  <rect width="" height="" x="" y="" fill="" fill-opacity="" stroke="" stroke-width="" stroke-opacity=""></rect>
* ʹ��SVG���л�ͼ����Բ��
  <circle r="" cx="" cy="" fill="" fill-opacity="" stroke="" stroke-opacity=""></circle>
* ʹ��SVG���л�ͼ������Բ
  <ellipse rx="" ry="" cx="" cy="" fill="" fill-opacity="" stroke="" stroke-opacity=""></ellipse>
* ʹ��SVG���л�ͼ����ֱ��
  <line x1="" y1="" x2="" y2="" stroke="" stroke-width="" stroke-linecap="butt/square/round"></line>
stroke-linecap��ָ����ͷ����ʽ��="  butt:   Ĭ�ϣ���������ÿ��ĩ�����ƽֱ�ı�Ե
                                  square: ��������ÿ��ĩ�����������ñ�ӣ����butt�����߱䳤
                                  round:  ��������ÿ��ĩ�����Բ�ε�ñ��

��ʾ�������SVGͼ������ȫһ�������ԣ����Գ����������һ�������ĸ�Ԫ���У�С�飩
ʹ��<g></g>������ǩ�飬�����ɼ�������������ʢ����Ԫ�أ���������Ԫ�ع��õĵ����ԣ���Ԫ�ػ�̳�
<g stroke="#000">
   <line></line>
   <line></line>
</g>
* ʹ��SVG���л�ͼ��������
  <polyline points="50,50  100,300 ..." fill="transparent" stroke="#000"></polyline>
* ʹ��SVG���л�ͼ���������
<polygon points="50,50  100,300 ..." fill=""></ polygon>
* ʹ��SVG���л�ͼ�����ı�
  <text font-size="" alignment-baseline="before-edge" fill="" stroke="" x="" y="">�ı����� </text>
* ʹ��SVG���л�ͼ����ͼ��
  ����ʹ��IMG����SVG�����ϣ�ֻ��ʹ�ã�
  <image xlink:href="disc.png" width="200" height="200" x="" y=""></image>


��ҳ�п��õĻ�ͼ������
(1)Canvas��ͼ --H5������ԭ����������һ��2D JSλͼ��ͼ����
(2)SVG��ͼ --H5���ɵ����м�������һ��2D ��ǩ ʸ��ͼ��ͼ����
(3)WebGL��ͼ --��δ����ΪH5��׼����һ��2D/3D JS��ͼ����������ɲο�three.js

