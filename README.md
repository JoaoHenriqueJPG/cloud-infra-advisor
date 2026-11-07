# 🚀 Cloud & Infra Advisor — Consultoria em Transformação Digital

🔗 **Acesse o Aplicativo Online (GitHub Pages):** [Clique aqui para abrir o App](https://JoaoHenriqueJPG.github.io/cloud-infa-advisor/)

## 👥 Especialistas Responsáveis (Autores)
- **João Hednrique MArchetto Vieira**
- **Unidade Curricular:** Exploração Digital e Fundamentos Tecnológicos (Objetos de Conhecimento 05 e 06)

---

## 🎯 1. O Problema Empresarial e Objetivo do Aplicativo
Muitas empresas ainda dependem de servidores locais antigos, sem garantia, com backups manuais ou inexistentes e links de internet instáveis. Isso gera alto risco de perda de dados (inclusive por ransomware), paradas inesperadas, custos de TI imprevisíveis e dificuldade em decidir **se, quando e como** migrar para a nuvem. O **Cloud & Infra Advisor** resolve essa dor com um diagnóstico rápido de 8 perguntas que calcula um **Score de Prontidão em Nuvem**, classifica a maturidade da empresa e gera um **Laudo Técnico de Prontidão e Migração para a Nuvem** com plano de ação priorizado, modelo de nuvem ideal (IaaS, PaaS ou SaaS) e estratégia de custos — tudo processado localmente no navegador, em conformidade com a LGPD.

## 🏛 2. Os 4 Pilares de Boas Práticas Aplicados no Diagnóstico
- **🖥 Infraestrutura Atual & Servidores:** Avalia a idade dos equipamentos e a dependência de infraestrutura física local. Recomenda inventário (CMDB), migração *lift-and-shift* para IaaS, troca de file servers por SaaS e, nos níveis mais altos, modernização com PaaS, containers e Infraestrutura como Código.
- **💾 Riscos, Backup & Recuperação:** Verifica a política de backup e o plano de recuperação de desastres (DR). Orienta a adoção da **regra 3-2-1**, backup imutável contra ransomware, definição de RTO/RPO e testes periódicos de restauração.
- **🌐 Conectividade, Desempenho & Custos:** Analisa a redundância de links e a previsibilidade do TCO. Sugere segundo link com failover, SD-WAN, migração de CAPEX para OPEX e práticas de **FinOps** (right-sizing, instâncias reservadas e alertas de custo).
- **🔐 Prontidão para Nuvem & Segurança:** Mede a maturidade da equipe e os controles de segurança. Recomenda MFA, gestão de identidades (SSO/IAM), EDR, criptografia, adequação à LGPD e evolução para arquitetura **Zero Trust**.

## 📊 3. Como Funciona
1. Preencha os dados da empresa (nome, setor, porte e colaboradores).
2. Responda às 8 perguntas (2 por pilar) — ou clique em **Carregar Caso Exemplo (Demo)**.
3. Clique em **Gerar Diagnóstico** para ver o score geral, o gráfico radar e o plano de ação.
4. Use **Imprimir / Exportar Laudo em PDF** para salvar o laudo.

**Níveis de maturidade:** Altamente On-Premise / Risco (0–39%) · Em Transição (40–64%) · Nuvem Híbrida Otimizada (65–84%) · Cloud Native / Líder (85–100%).

## 🛠 4. Tecnologias Utilizadas
- HTML5 + JavaScript puro (arquivo único `index.html`)
- Tailwind CSS (via CDN)
- Chart.js (gráfico radar)
- Lucide Icons
- Hospedagem: GitHub Pages

## 🛡 5. Privacidade (LGPD)
**Privacy by Design:** todos os cálculos e dados são processados localmente no navegador. Nenhuma informação é enviada a servidores.
