

## �͂��߂�
����md�t�@�C����API�̃\�[�X�����p�ł��B

***
### 1. �\�[�X�̊T�v
�{�\�[�X(SCM1_API�\�����[�V����)��UI������̃��N�G�X�g���󂯁A  
DB�փA�N�Z�X���A�f�[�^��CRUD���鏈�����s���܂��B��1  
������͕K���������ʁ�2��API���Ă�UI���ɕԋp���܂��B��3  

    ��1 ����UI����js�ŏ���������Ȃ����G�ȏ��������������ꍇ��  
        API���ŏ������s����������܂���  
    ��2 [���������FOK]�A[�������s�FNG]�A[�ُ�I���FER]  
    ��3 �f�[�^�擾�����̏ꍇ�͎擾�����f�[�^���ԋp���܂�

�܂��A�{�\�[�X��Azure���WebApps�ɓW�J����Ă���A  
�A�g���Ă���DB��Azure���SQL Database�ł��B  

�ȉ��A�A�v���P�[�V�����\���}�ł��B
![�A�v���P�[�V�����\���}](./mdFileResource/ApplicationConstitution.jpg?raw=true)

***
### 2. �A�v���̍\��
���̃A�v����VisualStudio2017�ŊJ�����Ă��܂��B.NET Framework��4.6.2�ł��B  
�\�����[�V�����̃t�@�C���\���͈ȉ��̂悤�ɂȂ��Ă��܂��B��2017/11/10����  
![�\�����[�V�����G�N�X�v���[���[](./mdFileResource/SolutionCompositionOverView.jpg?raw=true)


##### �ȉ��A�e�t�H���_���̐����ł�
+ APIController  
  UI����@�����API�̎󂯌��ƂȂ�\�[�X���i�[����Ă��܂��B  
  (MVC��Controller�Ɠ��������ł�)  
  APIController��HTTP���N�G�X�g�̎��(GET,POST�Ȃ�)�Ɋ�Â����A  
  ���\�b�h�Ő��藧���Ă��܂��B


# �����܂ŏ��������I

