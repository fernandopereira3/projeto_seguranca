RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: imediata 
Empresa: Abstergo Industries 
Responsável: fernando augusto pereira

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries , realizado por Fernando Augusto Pereira. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
    - Criacao de Usuarios, grupos, politicas e roles
    - Nesta etapa criaremos usuarios para todos que necessitao da conexao com a conta AWS. As contas teram a principio acesso minimo e mais privilegios serao dados os que necessitarem.
    - Junto com a criacao de usuarios seram criados tambem grupos de acesso sendo eles: Devenvolvedor, Testes e Admins. Mais grupos tambem poderam ser criados no futuro.
    - Ha todos os usuarios sera ogrigatorio a criacao de uma senha com protecao MFA (Autentificacao em dois fatores).

Medida 2: 
    -  Utilizacao dos serviços AWS Shield e WAF
    -  AWS WAF é um serviço que gerencia o trafigo da aplicacao, ja é nativo dos serviços AWS suas regras serao customizadas quando a aplicaçao estiver em modo de testes.
    -  AWS Shield Standart. Utilizaremos a versão Standart (Gratis) desta ferramenta AWS por motivos do custo, caso necessario faremos um upgrade para a versao Advance do servico. 
    Este servico protege o trafico da aplicação assim previnindo ataques DDOS e analizando o trafego em tempo real. Deste modo poderemos identificar o trafego, e assim como o serviço WAF o servico Shield poderao ser atualizados para o serviço pago caso haja a necessidade.

Medida 3: 
    - Utilização dos serviços Inspector e GuardDuty
    - Serviços de serguranca para o gerenciamento e a criaçao de logs.
    - O serviço Inspector sera utlizado para o momitoramentos das instancias encontrando erros e ajudando em futuras atualizações.
    - O Serviço GuardDuty sera responsavel por monitorar a infra estrutura gerando logs e registrando eventos.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado o aumento na segurança da organização e monitoramento do trafigo na aplicação, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Assinatura do Responsável pelo Projeto:

                                            Fernando Augusto Pereira