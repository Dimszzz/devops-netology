**/.terraform/*

������������ ���������� ���������� .terraform (���������� ����� ������������� � ����� ����� � ������ �������)
*.tfstate

������������ ����� �����, c ����������� tfstate � ����� ����� � ������ �������
*.tfstate.*

������������ �����, ���������� ������� ���������� �� tfstate � ����� ������ ������������������ �������� ����� �����

��������:


hello.tfstate.foo
random.tfstate.bar

crash.log

������������ ���� crash.log � ����� � .gitignore
crash.*.log

������������ ����� c crash.����� ������������������ ��������.log
*.tfvars

������������ ��� ����� � ����������� tfvars �� ���� �������
*.tfvars.json

������������ ��� ����� � ����������� tfvars.json �� ���� �������
override.tf � override.tf.json

������������ ��� ����� � ������ ��������� �� ���� �������
*_override.tf *_override.tf.json

������������ ��� �����, ��� ��� ���������� � ������ ������� � ������������� _override.tf ��� _override.tf.json
.terraformrc � terraform.rc

������������ ������ ����� � ����������