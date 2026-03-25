### Especificação de Caso de Uso: Gerenciar paciente

**1. Descrição do Caso de Uso**  
**COMO** Responsável  
**QUERO** Gerenciar o perfil de pacientes
**PARA** Incluir ou remover paciente sobre sua responsabilidade, além de manter as informações de saúde e bem-estar atualizadas.

**2. Pré-condições**  
- O responsável deve estar cadastrado e autenticado no sistema.  

**3. Fluxo Principal**  
1. O responsável acessa o perfil da paciente no sistema.  
2. O sistema exibe os dados da paciente, incluindo informações de saúde e bem-estar.  
3. O responsável seleciona a opção para incluir um cuidador ao perfil da paciente.  
4. O sistema solicita a busca do perfil do cuidador a ser incluído (pode ser feito por nome, e-mail ou outro identificador).  
5. O responsável seleciona o cuidador desejado na lista de resultados e confirma a inclusão.  
6. O sistema registra a associação entre o perfil do responsável, a paciente e o cuidador.  
7. O sistema exibe uma mensagem de sucesso confirmando a inclusão do cuidador no perfil da paciente.  
8. O responsável pode visualizar a lista de cuidadores associados à paciente.

**4. Fluxo Alternativo**  
4a. Caso o perfil do cuidador não seja encontrado:  
   1. O sistema exibe uma mensagem informando que o perfil não foi encontrado e sugere adicionar o cuidador manualmente (se aplicável).  

4b. Caso o responsável opte por remover um cuidador:  
   1. O sistema solicita a confirmação da remoção do cuidador do perfil da paciente.  
   2. O responsável confirma a remoção e o cuidador é desvinculado do perfil da paciente.  
   3. O sistema exibe uma mensagem de sucesso após a remoção do cuidador.

**5. Pós-condições**  
- O perfil do cuidador é vinculado ao perfil da paciente.  
- O responsável pode visualizar os cuidadores associados à paciente e gerenciar essa associação.

**6. Regras de Negócio**  
- **RN01** - O responsável pode associar vários cuidadores ao perfil de uma paciente.  
- **RN02** - O sistema deve garantir que o perfil do cuidador esteja devidamente registrado antes de ser vinculado à paciente.  
- **RN03** - Apenas o responsável tem permissão para adicionar ou remover cuidadores aos perfis de pessoas idosas.

**7. Requisitos Não Funcionais**  
- O sistema deve garantir que o processo de associação de cuidadores seja concluído em no máximo 5 segundos.  
- O sistema deve garantir a segurança das informações pessoais e de saúde da paciente, conforme políticas de privacidade e proteção de dados.

**8. Diagramas**  
- [BPMN](https://github.com/EnneLu/TINA-Requisitos/blob/main/docs/requirements/diagrams/BPMN/img/BPMN_02_GerenciarPaciente.png)