# Tensorflow Project2 �����۷���

###### ������������
- ѵ���õ�ģ�͵ı����ʹ��
- ѵ��������ѡ��
    - feedforward������
    - CNN���������

###### ���ݼ�

[�������ݼ�](http://help.sentiment140.com/for-students/)

training.1600000.processed.noemoticon.csv�ļ���**�ֶ�**���£�

- 0 �C the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
- 1 �C the id of the tweet (2087)
- 2 �C the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- 3 �C the query (lyx). If there is no query, then this value is NO_QUERY.
- 4 �C the user that tweeted (robotickilldozr)
- 5 �C the text of the tweet (Lyx is cool)


---
### Ԥ����
ʹ��process.py��������Ԥ����

process.py�еĴ����ԭʼ����תΪtraining.csv����tesing.csv������ֻ����label��tweet��lexcion.pickle�ļ������˴ʻ��

### ѵ�������ַ�ʽ��
- ʹ��train-feedforward.py����ѵ��
- ʹ��train-cnn.py����ѵ��

ѵ��ģ�ͱ���Ϊmodel.ckpt��

### ʹ��ģ��
ʹ��guess.py���в²�