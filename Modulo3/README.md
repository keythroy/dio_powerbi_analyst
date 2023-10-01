# dio_powerbi_analyst

Repositório de estudo do Power Bi

-- desafio módulo 2: Company transformation

- Em Department Mgr_ssn alterado tipo para número inteiro 
- Em Dependent Essn alterado tipo para número inteiro 
- Em Works_on Essn alterado tipo para número inteiro 
- Em Employee Essn e super_ssn alterado tipo para número inteiro 
- Em Employee Salary alterado tipo para número decimal fixo
- Em employee Adress dividida
  - primeiro delimitador '-' a esquerda como Address number
  - ultimo delimitador '-' a direita como Address State
  - ultimo delimitador '-' a direita como Address City
  - o restante como Adress Street
- Mescladas consultas employee (Dno) e Department (Dnumber) em uma nova consulta
	- Acrescertar consultas = somar linhas de diferentes consultas
	- Mesclar Consultas = mesclar colunas de diferentes consultas
- Mescladas colunas Fname e Lname na FullName
- Mescladas consultas Mesclar1 (Super_ssn) e employee (ssn) em uma nova consulta
- Mescladas colunas Fname e Lname na FullName manager
- Criada coluna nova departmentCity utilizando fórmula
	[azure_company departament.Dname] & "-" & [Address.City]