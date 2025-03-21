# LUCAS-TG-UML
Lucas Bittencourt de Oliveira, TIA: 42219851 || RA: 10409476

<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Inovação na Gestão Médica: Rumo a uma Saúde mais Eficiente e Segura&gt;*
</center></font>


**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Definição de demanda de desenvolvimento](#definição-de-demanda-de-desenvolvimento)
- [](#)
- [](#)

# Autores

* Lucas Bittencourt de Oliveira - TIA 42219851/RA 10409476

# Descrição do projeto

*O sistema será um software de cadastro de funcionários, permitindo centralização das informações, validação automática de dados, controle de acesso por níveis, busca eficiente e gestão simplificada para facilitar a administração de recursos humanos. *

## Demanda
![Demanda](docs/demanda.png)

# Diagrama de casos de uso

## Paciente
![Diagrama de casos de uso Paciente](docs/caso_de_uso_paciente.png)

## Medico
![Diagrama de casos de uso Medico](docs/caso_de_uso_medico.png)

# Descrição dos casos de uso

## Paciente

**Login do Paciente:**

- *Ator Principal:* Paciente
- *Descrição:* O paciente realiza login no sistema utilizando suas credenciais. Em caso de sucesso, tem acesso às funcionalidades do sistema; caso contrário, uma mensagem de erro é exibida.

**Registro de Informações Pessoais:**

- *Ator Principal:* Paciente
- *Descrição:* O paciente pode inserir e atualizar suas informações pessoais, como nome, data de nascimento, sexo, endereço, número de telefone, RG e informações de contato de emergência.

**Ver Receitas:**

- *Ator Principal:* Paciente
- *Descrição:* O paciente visualiza prescrições médicas anteriores, incluindo data, médico responsável e medicamentos prescritos.

**Enviar Resultados de Exames:**

- *Ator Principal:* Paciente
- *Descrição:* O paciente faz upload de resultados de exames para compartilhar com seu médico, facilitando a comunicação entre eles.

**Agendar Consultas:**

- *Ator Principal:* Paciente
- *Descrição:* O paciente agenda consultas com médicos disponíveis, escolhendo motivo, data e horário desejados.

**Ver Consultas Realizadas:**

- *Ator Principal:* Paciente
- *Descrição:* O paciente visualiza suas consultas prévias com os médicos.

## Medico

**Caso de Uso: Login do Médico**

- *Ator Principal:* Médico
- *Descrição:* O médico faz login no sistema utilizando seu código de acesso. Em caso de sucesso, tem acesso às funcionalidades do sistema; caso contrário, uma mensagem de erro é exibida.

**Caso de Uso: Registro de Informações Pessoais do Médico**

- *Ator Principal:* Médico
- *Descrição:* O médico insere e atualiza suas informações pessoais, como nome, idade, área de atuação, e outras informações relevantes.

**Caso de Uso: Gerenciamento de Pacientes**

- *Ator Principal:* Médico
- *Ator Secundário:* Paciente
- *Descrição:* O médico acessa e atualiza as informações pessoais e médicas de seus pacientes, incluindo nome, idade, sexo, RG, doenças pré-existentes, alergias e histórico familiar.

**Caso de Uso: Prescrição de Receitas**

- *Ator Principal:* Médico
- *Ator Secundário:* Paciente
- *Descrição:* O médico prescreve medicamentos e faz o upload da receita para o paciente, incluindo informações sobre a medicação e a dosagem.

**Caso de Uso: Gerenciamento de Medicamentos**

- *Ator Principal:* Médico
- *Descrição:* O médico busca e filtra medicamentos por tipo e nome, auxiliando na prescrição de medicamentos.

**Caso de Uso: Agenda de Consultas**

- *Ator Principal:* Médico
- *Ator Secundário:* Paciente
- *Descrição:* O médico visualiza sua agenda de consultas, incluindo os horários marcados com os pacientes, facilitando o gerenciamento de consultas e atendimentos.


- ## Diagrama de classe de domínio
- ![Diagrama de classe de domínio](docs/diagrama_de_classe.png)

- ## Diagrama de Sequencia Inicial
- ![medico_ver_pacientes](docs/medico_ver_pacientes.png)
- ![medico_enviar_receita](docs/medico_enviar_receita.png)
- ![paciente_marcar_consulta](docs/paciente_marcar_consulta.png)
- ![paciente_enviar_exames](docs/paciente_enviar_exames.png)
- ![medico_ver_consulta](docs/medico_ver_consulta.png)
- ![paciente_lista_receita](docs/paciente_listar_receita.png)
- ![medico_exame_historico](docs/medico_exame_historico.png)

-  ## Diagrama de Sequencia Detalhado
-  ![sequencia1](docs/sequencia1.jpg)
-  ![sequencia2](docs/sequencia2.jpg)

- ## Diagrama de Classe de Projeto
- ![diagrama_de_classe de projeto](docs/classe_de_projeto.jpg)
