# cybersecurity-bruteforce-lab
Projeto de laboratório desenvolvido durante a formação de Cibersegurança da DIO.
####################################################################################################################

**_Simulação de Ataque de Força Bruta com Medusa e Kali Linux_**

Este repositório contém a documentação técnica do laboratório de simulação de ataques de força bruta, realizado como parte da formação em Cibersegurança na DIO.

Objetivo do Projeto
O foco deste estudo foi compreender como ferramentas de auditoria, como o **Medusa**, são utilizadas para identificar vulnerabilidades em serviços de rede (como FTP, SSH e SMB) e, a partir disso, implementar medidas de proteção.

 Ferramentas Utilizadas (Ambiente Teórico)
- **Kali Linux:** Distribuição focada em testes de invasão e segurança.
- **Medusa:** Ferramenta de força bruta rápida, modular e paralela que testa múltiplas combinações de usuários e senhas.
- **Metasploitable 2 / DVWA:** Ambientes deliberadamente vulneráveis usados para prática segura.

O que foi aprendido
1. **Ataques de Força Bruta:** Tentativas sistemáticas de adivinhação de senhas até encontrar a correta.
2. **Wordlists:** A importância de listas de senhas bem estruturadas para o sucesso do teste.
3. **Serviços Alvos:** Como o Medusa interage com diferentes protocolos (ex: FTP e formulários web).

Medidas de Mitigação (Como se proteger)
Para evitar ataques como os simulados neste lab, as principais recomendações são:
- **Políticas de Senhas Fortes:** Uso de caracteres especiais, números e letras maiúsculas.
- **Bloqueio de IP (Fail2Ban):** Bloquear automaticamente o IP que errar a senha várias vezes seguidas.
- **MFA (Autenticação de Dois Fatores):** Adicionar uma camada extra de segurança que a força bruta não consegue quebrar sozinha.

Nota sobre Limitação Técnica
Devido a limitações de hardware para a execução de máquinas virtuais (VMs) localmente, este projeto priorizou a **documentação técnica detalhada**, análise do fluxo de ataque e estudo das ferramentas apresentadas em aula, conforme permitido pelas diretrizes flexíveis do desafio.

-----------------------------------------------------------------------------------
**Estudo realizado por Yasmin Silva**
