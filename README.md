# Catmull-Clarkϸ������C++ʵ��
---------------------------------------
### ʵ�ֹ���
�ó���ʵ����Catmull-Clark�㷨ϸ�������塣����Catmull-Clark�㷨��һ��ͨ������ϸ�ֵõ��⻬����ķ������ڼ����ͼ��ѧ�������Ź㷺Ӧ�á�����ͼ�Ϳ��Դ�������㷨�����philosophy��ͼƬ����[wiki](https://en.wikipedia.org/wiki/Catmull%E2%80%93Clark_subdivision_surface)����

![wiki_illustration](/readme_images/wiki_illustration.png)

ͨ������������Ŀ��ƶ��㣬Catmull-Clark�㷨����ͨ��������㣨face point�����ߵ㣨edge point�����ǵ㣨vertex point�����о���B����������㣬����⻬���档

### �㷨
Catmull-Clark�㷨���㷽�����£�
�����Ҫϸ�ֵ���Ⱥ͢�һ���������������񣬸����������еĵ���Ϊ**ԭʼ�㣨original points��**��
* ���������е�ÿ���棬�������**����㣨face point��**
	- ������Ǹ�������ԭʼ���ƽ��ֵ
* ���������е�ÿ���ߣ�����ñߵ�**�±ߵ㣨edge point��**
	- �±ߵ��Ǹñ�����������е㣬�͸ñ��ڽӵ�������������ƽ��ֵ
* �������е�ÿ��ԭʼ�㣬����**�½ǵ㣨vertex point��**���½ǵ�ļ��㷽����![formula](/readme_images/formula.png)

���У�
<ul>
<ul>
<li>F�Ǹõ��������������������ƽ��ֵ</li>
<li>R�Ǹõ����������бߵ��е��ƽ��ֵ</li>
<li>P�Ǹ�ԭʼ��</li>
</ul>

<li>
���������͸����ϼ�����±ߵ㣬ͬʱ�����½ǵ�͸õ������ıߵ��±ߵ㡣������Щ�����ɵıߣ��õ��ķ����������µ��档������������֪���ﵽ�����ϸ�ֵ���ȡ�
</li>
</ul>
��ͼ����Catmull-Clark�㷨��һ�����ӡ�

![algorithm_pipeline](/readme_images/algorithm_pipeline.png)

### ʵ�黷��
win7��64bit

C++�� Visual Studio 2015

��Ҫ�����Ҵ����С��鲻�õ��ģ�ֻҪ��ʹ��VS2015+��Ϊ64λϵͳ���Ϳ���ֱ����VS��ѡ��x64�������ɿ�ִ���ļ������ѽ�OpenGL��header��lib��dll�ⶼ��á�����ǿ�Ұ���ʹ��[�÷����������](http://www.cs.uregina.ca/Links/class-info/315/WWW/Lab1/GLUT/windows.html)���Լ��ĵ����价���������Ͳ����Ժ�ÿдһ���������һ�λ�����~
### ʹ�÷���
���̿��Ʒ�����
* ����f��������y����������������ϵ����ʱ����ת��
* ����s��������y����������������ϵ��˳ʱ����ת��
* ����e��������x����������������ϵ����ʱ����ת��
* ����d��������x����������������ϵ��˳ʱ����ת��

### ʵ����
�߿��ʾ��

![result_grid](/readme_images/result_grid.png)

��Ƭ��ʾ��

![result_face](/readme_images/result_face.png)