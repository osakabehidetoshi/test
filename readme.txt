https://github.com/osakabehidetoshi/test
https://github.com/osakabehidetoshi/test.git

#git�̏����ݒ�

$ git config --global user.name "���[�U��"
$ git config --global user.email ���[���A�h���X

#editer�̐ݒ�
$�@git config --global core.editor "vim -f"


#�cor create a new repository on the command line

#git�̏�����
�@#��ƃt�H���_�쐬
    $ mkdir gittest
    $ cd gittest
  #git initialize
    $ git init
    $git add README.md
1�j���[�J�����|�W�g�����쐬����
    $ git init

    $git status  #��Ԋm�F�B�����쐬

2�j���[�J�����|�W�g���Ƀt�@�C���̕ύX�_��ǉ��i�C���f�b�N�X�ɒǉ��j
    $ git add .  # $ git add <filename>

3�j���[�J�����|�W�g���ɃC���f�b�N�X�ɒǉ������t�@�C����o�^
    $git commit -m "first commit"

4)�R�~�b�g���O�̊m�F
    $git log

#GitHub�Ƀv�b�V��
 (1)GitHub�A�J�E���g�쐬
 (2)�ʐM�͈Í������܂��傤�BSSHkey�̐ݒ�
 (3)���|�W�g���̍쐬
 (4)GitHub�ւ�push

4)�C���f�b�N�X�i�t�@�C���̕ύX�_�Ȃǂ̃��X�g�H�j��GitHub�ɍ쐬�D
   $ git remote add origin https://github.com/<username>/first_app.git

5)�R�~�b�g���ꂽ�f�[�^��GitHub�ɑ��M�i�v�b�V���j���܂��D
   $ git push -u origin master
     or 
   $ git push origin master


�Z�v�b�V�������f�[�^��ύX�E�X�V���Ă݂�
0) file��ҏW����B

1�j�ύX���C���f�b�N�X�ɒǉ�
�@�@$ git add test.txt

2�j�t�@�C����o�^�i�R�~�b�g�j
�@�@$ git commit -m "�ύX���Ă݂���"

3�j�f�[�^�̑��M
�@�@$ git push origin master



