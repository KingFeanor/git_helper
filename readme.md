# ����������� �� ������ � git  
----  
## �������� ������� � �����������  
� ��������� ������ �� ������ ���������� � �����-�� ����� � ������ ����� �� �����.  
�.� - ������� ����������  
�..� - ���������� ����������  
�~� - �������� ����������  
  
**pwd** (print working directory) ������� ���� � ������� ���������� (�����).  
  
**cd** (change directory) � ������� �����. ���� � �������� ����� ���� �������, ����� ������ ����� �������. ����� ��������� � ������������ ����������, ����� �������� ��� �����. � ������� ����� ����� ����� ���������� � ������� �����.  
  
**ls** (list contents) � ���������� ���������� �����. ���� �������� ���� -a, �� ��������� � ������� �����, ������������ � �.�  
  
**touch** � ������ ����. ������ �touch test.txt�  
  
**mkdir** (make directory) � ������ ����������. � ������� ����� -p ����� ������� ����� ��������� �����: mkdir -p dir/dir-inside. ������ � ��������� ������: mkdir ~/my-git-projects  
  
**cp** (copy) � ����������� ������. ��������� ��� ���������: ��� ��������, � ����.  
  
**mv** (move) � �� ���������� �� ��, ��� � cp  
  
**cat** (concatenate and print) � ������� ���������� (������) ���������� �����. ����� cat ���� ������ �������� �����.
   
**rm** (remove) � ������� ����. ���� ������ �������� ����� ����� remove.  
  
**rmdir** (rempve directory) � ������� ������ �����. ���� ����� �� ������, �� ��� �� ����� �������, � �� ���� ����������. ����� rmdir ������� �������� �����.  
  
**rm -r** ������ �� ���������� ����� � ���� �����. ���� �������� ���� -f �� ���������� �������� ��� �������� �� �� ����� ������?�. ��������� ����� ����� ��� -rf  
  
**!!�������������!!** rm � rmdir ����������, �.�. �������� ����� � ����� �������� ��������, ������ ��� �� �������� � �������.  
  
**clip** < ����/�/�����/ - �������� ���������� ����� � ����� ������.  
  
����� ��������� ������ ����� ��������� ������, �������� �� &&  
� ������� ��������� ����� ����� ������������ �� ��������� ��������.  
� ������ tab ����� �������������� ������.  

## ��������� git  
  
**git config --global** � ��������� ����� (user.name) � ����� (user.email). ������: git config --global user.name �Feanor Noldor�. � ������ --list ������ ��� � �����.  
  
**ssh-keygen** � ���������� ssh ���� (���� ������������� ��������).  
  
## ������ � git  
  
**git init** � ������ �����, � ������� ���������� ������������ ���. �� ����� ��������� ���� ����������� ������ �������.  
����� ��������� �����, ���������� ������������, ����� ������� ����� .git ������ � ��� �������� ������� ���������.  
  
**git status** � ���������� ������� ��������� �����������.  
  
**git add smth.smth** � �������������� � ���������� ���� � �����������. ���� --all ��������� ��� ������� �� ���� ������ � �����������. ����������� ����� � ��� ������� �����, ����������� � ��� ����� �.�. ������� git add ���� ���������� ������� ���������, �� �� ��������� ���.  
  
���������� ������� ������ �������� ��������.  
**git commit** � �������� �����������. ���� �������� ���� -m �� ����� ������� ����� �������� � �������� ����������� � ����� �������.  
  
**git log** � ���������� ������� ��������.  
  
**git remote add** <���> <URL> - �������� ��������� ����������� � ����������. ������� ����������� �� ������� �����������. origin � ����������� ���������, � ������� �������� ����� ���������� � �������� ��������� �����������. ������������ ��� ��������� <���>. � ������� ����� -v ����� ���������, ��� ����������� �������.  
   
**git push** � ���������� ��������� �� �������� �����������. � ������ ��� ��� ������� ���� �������� � ������ -u � ������������ ����� ��������� ����������� (origin) � �������� ������� ����� (master, ���� �������).  
  
**readme.md** � ���� ��������, ��������� � �������. �������� ������� ��������� ������, �� �������� ������������� � ������� ����� markdown. �������� ����� [���](https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c)