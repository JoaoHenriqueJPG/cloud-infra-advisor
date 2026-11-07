🚀 Cloud & Infra Advisor — Consultoria em Transformação Digital
🔗 Acesse o Aplicativo Online (GitHub Pages): Clique aqui para abrir o App(https://joaohenriquejpg.github.io/cloud-infra-advisor/)

👥 Especialistas Responsáveis (Autores)
João Henrique Marchetto Vieira
Unidade Curricular: Exploração Digital e Fundamentos Tecnológicos (Objetos de Conhecimento 05 e 06)

🎯 1. O Problema Empresarial e Objetivo do Aplicativo
Muitas empresas ainda dependem de servidores locais antigos e sem garantia, fazem backups manuais (ou nenhum) e usam links de internet instáveis. Isso gera alto risco de perda de dados, inclusive por ransomware, além de paradas inesperadas, custos de TI imprevisíveis e dificuldade para decidir se, quando e como migrar para a nuvem. O Cloud & Infra Advisor resolve essa dor com um diagnóstico de 8 perguntas que calcula um Score de Prontidão em Nuvem, classifica a maturidade da empresa (de "Altamente On-Premise / Risco" a "Cloud Native / Líder") e gera um Laudo Técnico de Prontidão e Migração para a Nuvem. O laudo traz um plano de ação priorizado, o modelo de nuvem ideal (IaaS, PaaS ou SaaS) e uma estratégia de custos, tudo processado localmente no navegador, em conformidade com a LGPD.

🏛 2. Os 4 Pilares de Boas Práticas Aplicados no Diagnóstico
O aplicativo é especializado em infraestrutura e nuvem, e por isso organiza o diagnóstico nestes 4 pilares:

☁ Infraestrutura Atual e Migração para a Nuvem: avalia a idade dos servidores e a dependência de estrutura física local. Recomenda inventário de sistemas, migração lift-and-shift para IaaS, troca de servidores de arquivos por SaaS e, nos níveis mais altos, modernização com PaaS, containers e Infraestrutura como Código.
💾 Riscos, Backup e Alta Disponibilidade: verifica a política de backup e o plano de recuperação de desastres. Orienta a adoção da regra 3-2-1, backup imutável contra ransomware, definição de RTO/RPO, testes periódicos de restauração e DR multirregião.
🌐 Conectividade, Desempenho e Custos: analisa a redundância dos links e a previsibilidade do custo total de TI (TCO). Sugere segundo link com failover, SD-WAN, troca de CAPEX por OPEX e práticas de FinOps (right-sizing, instâncias reservadas e alertas de custo).
🛡 Governança, Segurança Digital e LGPD: mede a maturidade da equipe e os controles de segurança. Recomenda MFA, gestão de identidades e controle de acesso (SSO/IAM), EDR, criptografia, adequação à LGPD e evolução para Zero Trust. O próprio app segue o Privacy by Design: nenhum dado sai do navegador.
🛠 3. IAs Generativas e Ferramentas Utilizadas
Ferramenta / IA	Como foi utilizada no projeto
Lovable (agente de IA)	Estruturação das regras de negócio, perguntas e pesos do diagnóstico, níveis de maturidade, plano de ação e geração do código HTML/JS em arquivo único.
TailwindCSS & Chart.js (CDN)	Estilização executiva responsiva e gráfico radar dinâmico de maturidade por pilar.
Lucide Icons (CDN)	Ícones da interface e dos pilares.
VS Code & Git	Edição local do projeto e controle de versão.
GitHub & GitHub Pages	Versionamento de código e publicação em nuvem estática (PaaS/CDN).
🧠 4. Diário de Construção: Como Construímos e Refinamos o App
Concepção e Engenharia de Prompt: o prompt inicial definiu o papel da IA como consultora de infraestrutura e nuvem e pediu um aplicativo em um único arquivo HTML, pronto para o GitHub Pages. Ele trazia uma lista numerada de requisitos: formulário com dados da empresa, 4 pilares com 2 perguntas cada e pontuação de 0 a 100, score geral com selo de maturidade, gráfico radar, plano de boas práticas com modelo de nuvem ideal (IaaS/PaaS/SaaS), botão de demonstração, exportação do laudo em PDF e selo de privacidade LGPD no rodapé.
Ajustes e Refinamentos Técnicos: (descrevam aqui o que vocês pediram para corrigir ou melhorar após o primeiro teste. Exemplo: o prompt foi cortado no último item e a IA precisou completar o texto do selo LGPD; ajustes de layout de impressão do laudo em PDF; mudanças nas perguntas ou nos pesos.)
Principal Aprendizado: (escrevam com suas palavras. Sugestão de pontos: migrar para a nuvem não começa pela tecnologia, e sim pelo diagnóstico, pelo backup testado e pelo controle de custos; a escolha entre IaaS, PaaS e SaaS depende da maturidade de cada empresa; a IA acelera muito o desenvolvimento, mas o resultado depende de um prompt claro e de revisão humana.)
