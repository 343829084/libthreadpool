libthreadpool
=============

һ���Ƚ�������ͨ�ü򵥵��̳߳�
�ÿ����boost::thread��ʹ���˲���c++11���ԣ���Ϊvs2010��c++11֧�ֲ�������
ʹ�÷������test.cpp


int main(int,char**)
{
    threadpool::pool p;

    p.post(...);//����һ������
    p.waitall();//�ȴ������������
    p.post(...);//����һ������
    p.stop();   //ֹͣ
    p.start();  //���¿�ʼ����stop�ɶԣ�
    p.waitall();//�ȴ������������

    return 0;
}