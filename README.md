# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: 30/01/2025 Empresa: XPTO Responsável: Phelipe

# Introdução
> Este relatório apresenta o processo de implementação de ferramentas na empresa XPTO, realizado por Phelipe. O objetivo do projeto foi elencar **3 medidas de segurança em conjunto dos serviços da AWS**, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

### Medida 1:  Gerenciamento Seguro de Credenciais e IAM (Identity and Access Management)
- Princípio do menor privilégio: Conceda apenas as permissões necessárias para cada usuário ou serviço.
- Uso do AWS IAM: Configure políticas detalhadas de acesso e evite o uso de credenciais de root.
- Autenticação Multifator (MFA): Habilite o MFA para todas as contas críticas, especialmente a conta root.

## Medida 2: Criptografia e Proteção de Dados
- Criptografia em repouso e em trânsito: Use AWS KMS (Key Management Service) para proteger dados armazenados no S3, RDS, DynamoDB, entre outros. Utilize TLS/SSL para a comunicação de dados.
- Controle de acesso a dados: Implemente políticas de bucket no S3 e restrinja permissões usando IAM.
- Rotação de chaves: Automatize a rotação periódica de chaves criptográficas para evitar comprometimentos.

## Medida 3: Monitoramento, Auditoria e Resposta a Incidentes
- AWS CloudTrail: Habilite logs de auditoria para rastrear atividades e detectar acessos suspeitos.
- AWS GuardDuty e Security Hub: Utilize ferramentas de monitoramento de ameaças e conformidade de segurança.
- AWS WAF & Shield: Proteja aplicações web contra ataques como DDoS, injeções de SQL e XSS.

# Conclusão
A implementação de ferramentas na empresa XPTO tem como esperado fortalecer a segurança na AWS, reduzindo riscos de ataques e vazamento de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

- https://aws.amazon.com/training/learn-about/security/

Assinatura do Responsável pelo Projeto:
Phelipe
