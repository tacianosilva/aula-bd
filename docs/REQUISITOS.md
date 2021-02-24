# Requisitos do Projeto 

Um sistema para a gestão de consultórios de clínica médica.

Entidades
* Um cadastro de Médico com nome, email, especialidade, CRM, ...
* Um cadastro de Pacientes com nome, email, telefone, dt_nasc, sexo, 
* Um cadastro de Protuária tem um lista de observações dos médicos feitas em consultas, referencia consultas, receitas e exames, ...
* Um cadastro de Funcionários (Secretária, ASG, Enfermeira, ...) nome, email, função, salário,
* Um cadastro de Consulta tem data/hora de agendamento, data/hora de realização, paciente, médico, funcionário, descricao/relato do paciente, situação da consulta (Agendada, Realizada, Cancelada,consulta de retorno, ...
* Um cadastro de Receitas, uma descrição, um médico responsável, paciente, consulta, ...
* Um cadastro de Exames, 

Relacionamentos
* Um médico pode atender várias consultas
* Um paciente pode realizar várias consultas
* Uma consulta é de apenas um paciente
* Uma consulta pode ser realizada por um ou mais médicos
* Uma receita é feita em uma consulta de um paciente, e descreve um ou vários medicamentos.
* Um exame é o resultado de testes passado por um médico,  ...
* Prontuário é de um paciente e os médicos tem acesso

MER - Diagrama Entidade-Relacionamento

Regras de Conversão

MR - Modelo Relacional

O Dicionário de Dados
