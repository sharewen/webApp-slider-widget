# webApp-slider-widget
a webAPP demo


�ƶ�div��ʵ����Ȼ����ʹ��position:absolute,�����ǽ���ʹ��translate3d,��Ϊ���������ֻ���GPU���٣�����ͼƬ����Ⱦ


-webkit-transform: translate3d(0px,0,0);

��ָ������Ļtouchstart
��ָ�����Ļtouchmove
��ָ̧���¼�touchend

translate3d(x,y,z)
x:��ʾ��x�᷽���λ�ơ�
y:��ʾ��y�᷽���λ�ơ�
z:��ʾ��z�᷽���λ��
<mata name="viewpoint" conten="device-width",   //��ȵ����豸�Ŀ��
initial-scale=1.0,//Ĭ�ϷŴ���1.0
maximum-scale=1.0,//���Ŵ���1.0
minimum-scale=1.0,//��С�Ŵ���1.0������ʧ�������
<meta name="apple-mobile-web-app-status-bar-style" content="black" ></mata>//IOS�������������ɫ
user-scalable=no"/>//��ֹ�û�����
<meta name="apple-touch-fullscreen" content="YES" />//����ȫ��Ӧ��

#### Ҫʹ��bodyռ��ȫ�� 
body{
 height:100%;
 position:absolute; // ���ڴ�

}



<ul>
	<li>
		<img width="320" src="1.jpg">
	</li>

</ul>

#### ͼƬ���¾�����ʾ
����(�߼������)��
1��li{display:table-cell;vertical-align:middle;}
2��li{display:-webkit-box;-webkit-box-pack:center;-webkit-box-align:center;}
����(һ��)��
li{line-height:568px;vertical-align:middle;}
li img{vertical-align:middle;}


//���ݴ��ڵı�����ͼƬ�ı�����ȷ��
//ͼƬ�Ǹ��ݿ�����ȱ����Ż��Ǹ��ݸ߶����ȱ�����