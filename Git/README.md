# ��ʼ��git�ֿ�
git init

# ��ӵ�ǰĿ¼�������ļ���git
git add .

# ���Զ��·��
git remote add origin https://{username}:{password}@github.com

# ɾ��Զ��·��
git remote rm origin

# �޸�Զ��·��
git remote set-url origin xxx

# �Ƴ��ļ�track����
git rm -r --cached FILENAME

# �л���Master��֧
git checkout master

# ��develop��֧�ϲ�����ǰ��֧
git merge develop

# �Զ�������иı䲢�ύ�ı�
git commit -am 'comment'

# �½���֧
git branch ��֧��

# ɾ����֧
git branch -d ��֧��

# ɾ��Զ�̷�֧
git push origin -delete ��֧��

# �ύ��Զ�̵�master
git push orgin master

# ��ȡmaster
git pull orgin master

# �鿴master��֧��ʷ
git reflog master

# �ָ�����ʷ
* git reset --hard <COMMIT_ID> ��
* git reset --hard master@{1}

# �ֶ������ͻ
git add ��ͻ�ļ�

# ���ǩ
git tag v1.0.0 -m '��ע'

# �л���ǩ
git checkout [tagname]

# ɾ����ǩ
git tag -d [tagname]

# ��ǩ����
* git push origin [tagname] �ύһ��
* git push origin -tags     �ύ����

# �鿴��ǰ��֮�µı�ǩ
git tag

# ssh for git
* cd ~/.ssh
* ssh-keygen -t rsa -C "your_email@youremail.com"
* clip < ~/.ssh/id_rsa.pub
* ճ����Կ��������
* git remote set-url origin git@github.com:someaccount/someproject.git

# �鿴commit��־
git log