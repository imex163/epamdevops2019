1. ���������� ���������� Jenkins(������ 2+) � ��������� ��� ���� �� ���������.
 * - ������� ��� ���� �����, �� ��� � �������������� pipeline(Scripted ��� Declarative �� ���� ����������)
 ** - ������� �������� ������ �� GitHub'�(����� ������) � �������������� Jenkins.
 
2. ������� playbook Ansible ��� ��������� � ��������� mysql(������ ������������ MariaDB). ������������ ������ �������������� �� template � �������������� ����������.
 ��������� ��������� playbook'a:

+-- play.yml
L-- roles
    L-- mysql
        +-- tasks
        ��� L-- main.yml
        +-- templates
        ��� L-- my.cnf
        L-- vars
            L-- main.yml

���������� ������ ��������� �� ����� ivan_govorukhin@epam.com. � ������ � Jenkins'�� ������ �������� ��������� ���� ��������� �������(���� pipeline'�).