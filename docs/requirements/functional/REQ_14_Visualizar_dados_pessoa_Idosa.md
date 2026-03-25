### Especificação de Caso de Uso: Visualizar Dados da paciente

**1. Descrição do Caso de Uso**  
**COMO** Responsável/Cuidador  
**QUERO** Visualizar os dados cadastrados no perfil da paciente  
**PARA** Ter acesso rápido e centralizado às informações essenciais do paciente.  

**2. Pré-condições**  
- O usuário deve estar autenticado no sistema.  
- O usuário deve ter permissão para acessar os dados da paciente.  

**3. Fluxo Principal**  
1. O usuário acessa a funcionalidade de visualização de dados do perfil da paciente.  
2. O sistema exibe uma lista com os perfis dos pacientes associadas ao responsável ou cuidador.  
3. O usuário seleciona o perfil da paciente desejada.  
4. O sistema apresenta os dados cadastrados.
5. O usuário analisa as informações exibidas.  

**4. Fluxo Alternativo**  
Não se aplica. 

**5. Pós-condições**  
- O usuário visualiza as informações atualizadas do perfil da paciente.  

**6. Regras de Negócio**  
- **RN01** - Apenas cuidadores ou responsáveis autorizados podem acessar os dados de uma paciente.  

**7. Requisitos Não Funcionais**  
- O sistema deve garantir que os dados sejam exibidos de forma clara e organizada, com layout responsivo para diferentes dispositivos.  
- A visualização deve ser carregada em até 3 segundos, garantindo uma experiência fluida para o usuário.  
