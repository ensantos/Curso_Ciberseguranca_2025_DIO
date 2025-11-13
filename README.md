# Desafio - Cibersegurança Santander 2025: 
* **Simulação de Ataque de Força Bruta com Medusa**

Este exercício prático reproduziu cenários comuns em que a segurança é comprometida por configurações negligenciadas e erros humanos. As imagens e arquivos anexados no repositório registram a execução dos módulos concluídos e evidenciam a metodologia aplicada.



### 1. Atividades Realizadas



O projeto foi conduzido em ambientes de laboratório (Metasploitable 2 e DVWA), com foco em exploração controlada de vulnerabilidades e nas técnicas a seguir:



* **Acesso a Ambientes Deliberadamente Vulneráveis:** Utilização do Metasploitable 2 como alvo de testes de intrusão, servindo de base para experimentação segura.

* **Ataques de Força Bruta:**


    
    * Criação e uso de **Wordlists** e listas de usuários.

    * Simulação de tentativas de login em aplicações web sujeitas a validação fraca.

    * Uso do Medusa para realizar password spraying em serviços de rede, explorando combinações de credenciais fracas ou padrão.

* **Ataque e Enumeration:**

    * Enumeração do protocolo SMB (Server Message Block) como parte de um fluxo de ataque em cadeia..

    * Verificação de compartilhamentos e coleta de informações via smbclient, reproduzindo um contexto corporativo com parâmetros inadequadamente configurados.



### 2. Reflexões e Opiniões



O principal aprendizado está no impacto de falhas básicas de configuração. O êxito nas simulações reforça conclusões estratégicas que costumam se repetir em ambientes reais.



#### Fragilidades Mais Evidentes:

* **Servidores Expostos e Mal Configurados:** Acesso facilitado a serviços de rede (ex.: FTP e SMB) e a aplicações web vulneráveis revela carência de endurecimento (hardening) e de ajustes mínimos de segurança..

* **Senhas Fracas e Reutilização de Credenciais:** O sucesso de ataques por dicionário e password spraying evidencia o risco de senhas previsíveis, padrões reutilizados e ausência de controles complementares.

* **Padrões Previsíveis e Falta de Auditoria:** Sem revisões periódicas, padrões fáceis de inferir permanecem exploráveis por atacantes com pouco esforço.



#### Recomendações de Mitigação:

Para reduzir a superfície de ataque e responder de forma proativa às vulnerabilidades identificadas, destacam-se as seguintes medidas:

* **Política de Senhas e Autenticação Robusta:** Exigir senhas complexas, com rotação periódica quando apropriado, e adotar Autenticação Multifator (MFA) em serviços críticos.

* **Monitoramento e Resposta a Incidentes:** Implementar detecção de anomalias, alertas em tempo real e bloqueio automático por IP após tentativas consecutivas de falha.

* **Auditorias Contínuas e Testes de Segurança:** Tratar segurança como processo permanente: realizar avaliações regulares, pentests agendados e exercícios de simulação para identificar e corrigir falhas antes que sejam exploradas.


* **Considerações Finais**

Em síntese, o desafio ressalta que muitas violações decorrem de descuidos operacionais e lacunas de governança. Uma postura de segurança sólida começa pelo cumprimento rigoroso do básico: boas práticas de configuração, políticas de credenciais efetivas e verificação contínua do ambiente.

<img width="1821" height="1012" alt="kali" src="https://github.com/user-attachments/assets/42ce691e-b8d3-4081-9ea9-ed71f2051480" />
<img width="1913" height="1015" alt="Metasploitable" src="https://github.com/user-attachments/assets/569c1afa-aba1-4060-8cf9-d8de34824aa9" />
<img width="1100" height="460" alt="descobrir rede" src="https://github.com/user-attachments/assets/07cbb310-24c2-4b14-a570-8f88fd295108" />
<img width="692" height="537" alt="maquina enumerada" src="https://github.com/user-attachments/assets/e51f5e59-064b-46ad-a6f7-bcf633a903e6" />
<img width="291" height="96" alt="ftp pedindo senha" src="https://github.com/user-attachments/assets/36aad1a9-3fb9-439b-b500-a795d5559989" />
<img width="533" height="142" alt="arquivos txt criados" src="https://github.com/user-attachments/assets/f9bf459c-e9eb-4a25-9aed-2ffafa79aa57" />
<img width="1266" height="362" alt="ftp medusa" src="https://github.com/user-attachments/assets/b9a0d2c4-9b95-4318-affb-374e97cfb4b4" />
<img width="315" height="195" alt="acesso ao ftp" src="https://github.com/user-attachments/assets/1a258307-31eb-43ee-bf48-a77a33cb43f6" />
<img width="572" height="297" alt="listado pastas no ftp" src="https://github.com/user-attachments/assets/4d2cfcd4-4b4f-4a18-9532-ce8877944d8f" />


<img width="1622" height="729" alt="parametros" src="https://github.com/user-attachments/assets/b0871813-2793-42f9-b170-70ffe20328e3" />
<img width="1286" height="782" alt="senha encontrada" src="https://github.com/user-attachments/assets/e2ca3d7b-8ccf-4b07-b960-31fa251bdbba" />
<img width="1392" height="865" alt="acesso ao formulario" src="https://github.com/user-attachments/assets/c12dd8ac-8d28-47b3-a76a-77165ab119e1" />












 



