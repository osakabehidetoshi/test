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

 1)$ git init   #���[�J�����|�W�g�����쐬����
 2)$git add .  #  #���[�J�����|�W�g���Ƀt�@�C���̕ύX�_��ǉ��i�C���f�b�N�X�ɒǉ��j
 2)$ git add <filename>

 3) $git status  #��Ԋm�F�B�����쐬

 4)$git commit -m "first commit" #���[�J�����|�W�g���ɃC���f�b�N�X�ɒǉ������t�@�C����o�^
 5)$git log #�R�~�b�g���O�̊m�F

#GitHub�Ƀv�b�V��
 (1)GitHub�A�J�E���g�쐬
 (2)�ʐM�͈Í������܂��傤�BSSHkey�̐ݒ�
 (3)���|�W�g���̍쐬
 (4)GitHub�ւ�push

4)�C���f�b�N�X�i�t�@�C���̕ύX�_�Ȃǂ̃��X�g�H�j��GitHub�ɍ쐬�D
   $ git remote add origin https://github.com/<username>/first_app.git

5) $ git push -u origin master #�R�~�b�g���ꂽ�f�[�^��GitHub�ɑ��M�i�v�b�V���j
     or 
   $ git push origin master    #�R�~�b�g���ꂽ�f�[�^��GitHub�ɑ��M�i�v�b�V���j


�Z�v�b�V�������f�[�^��ύX�E�X�V���Ă݂�
  0) file��ҏW����B
  1�j$ git add test.txt  #�ύX���C���f�b�N�X�ɒǉ�
  2�j$ git commit -m "�ύX���Ă݂���" #�t�@�C����o�^�i�R�~�b�g�j
  3�j$ git push origin master #�f�[�^�̑��M


�Z���̑��Q�l�R�}���h
�@$git status    #�R�~�b�g�҂��t�@�C���̕\��
  $git checkout  #check out
  $git push      #�����[�g���|�W�g���R�~�b�g