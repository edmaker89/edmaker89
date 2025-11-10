# 👋 Olá, Eu sou o Douglas!

💰 Um paulista morando no Interior "do" Goiás!
🎓 Pós-graduado em **Engenharia de Software** pela Faculdade Metropolitana e **Arquitetura de Sistemas da Informação** pela CENES <br>
💻 **Desenvolvedor Full Stack** — foco em **Python**, **React** e **React Native**  
🏢 Atualmente: **Analista de Sistemas e Aplicações** em [SSA Alimentos S/A](https://www.linkedin.com/company/saosalvadoralimentos/posts/?feedView=all)  
🚀 Entusiasta de containers, infraestrutura e orquestração (Docker Swarm → Kubernetes)  
🌎 [edmaker.dev.br](https://edmaker.dev.br)  
📍 Itaberaí, GO, Brasil

---
## 🌐 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/douglasedmaker/)  [![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/edmaker89)  [![E-mail](https://img.shields.io/badge/Email-FF6C37?style=for-the-badge&logo=gmail&logoColor=white)](mailto:edmaker@gmail.com)

---
## 🧠 Tecnologias — resumo

Sou um desenvolvedor Full Stack com ênfase em back-end Python e aplicações front-end com React. Trabalho com desenvolvimento mobile multiplataforma (React Native) e tenho forte prática em colocar aplicações em produção usando containers e VPS. Abaixo um resumo prático das minhas stacks preferidas e onde atuo com mais frequência.

### Linguagens & frameworks (habilidade prática)
- **Python** — desenvolvimento de APIs e serviços (Flask, FastAPI, Django). Uso Python para API REST, ETL leve, automações, aplicações fullstacks, utilitarios e scripts de infra.  
- **JavaScript / TypeScript** — aplicações web com **React**, **Next.js** (front-end moderno, SSR/SSG) e **React Native** para mobile.  
- **Flutter** — conhecimento para projetos móveis quando aplicável.  
- **HTML / CSS** — construção de interfaces responsivas; uso **TailwindCSS** e **BulmaCSS** para acelerar layout e design.  
- **Banco de dados** — experiência com **MariaDB/MySQL, PostregSQL, MongoDB**, modelagem relacional, otimização de queries e backups automatizados.

### Infraestrutura & DevOps (prática e responsabilidades)
- **Containers e orquestração:** Docker para empacotamento; **Docker Swarm** para orquestração leve em ambientes de produção enxutos; planejamento para migração/adoção de **Kubernetes** quando necessário. **Portainer** <3 
- **Proxy / TLS / Ingress:** Traefik (favorecido pela integração automática de certificados e rotas dinâmicas) e **NGINX** como reverse-proxy quando preciso de controle fino.  
- **VPS e deploys:** construção e manutenção de servidores VPS (configurações, deploys, rotinas de backup e scripts de automação).  
- **Backups & recuperação:** rotinas automatizadas de backups (local e remoto — S3/GCS/drive / ``rclone``) , snapshots de VMs e estratégia para recuperação rápida (uso de snapshots após criação de VMs).  
- **Observabilidade & logs:** centralização de logs, métricas básicas e alertas para serviços críticos (próximos passos: Aprender e implementar de forma pratica Prometheus/Grafana + ELK/EFK quando escalar).  
- **CI/CD:** pipelines automatizados (build → test → image → deploy), imagens Docker versionadas e tags semânticas para releases previsíveis. Usando Github actions (proximos passo: Jenkins e ArgoCD) 
- **Security & hardening:** práticas de segurança em servidores, variáveis de ambiente secretas, gestão de certificados TLS e minimização de superfícies de ataque em serviços expostos.
- **Próximos passos:** estudos de virutalização com VMWARE e Proxmox. Criar um homelab.

---
## 🔧 Ferramentas e preferências

**Frameworks preferidos:**  
React, React Native, Flask, FastAPI, Django, Flutter, TailwindCSS, BulmaCSS, Next.js.  

**Infra & orquestração:**  
Docker, Docker Swarm, Traefik, NGINX, VPS (Linux), com plano de evolução para Kubernetes quando necessário.

---
## 🧩 Projetos Relevantes — Projeto Itaberaí

### 🌸 Aplicativo Rosa  
Aplicativo mobile em **Dart/Flutter** para **Agentes Comunitários de Saúde (ACS)** — permite o cadastro de pacientes e o preenchimento anual de formulários (Hábitos de Vida, Anamnese e Exame Físico). Quando uma alteração mamária é detectada, o caso é encaminhado automaticamente para o RosaWatch.  
**Stack:** Dart/Flutter, Flask (API), MariaDB, Docker, processos de backup e deploy em VPS.
[App Rosa](https://rosawatch.rebracam.org.br/download)

### 💗 RosaWatch  
Plataforma web que dá suporte ao Aplicativo Rosa. Profissionais de saúde usam o RosaWatch para visualizar, triar e acompanhar casos de rastreamento precoce do câncer de mama para apoiar as ações do **PROJETO ITABERAI**. Projeto feito em parceria com **Ministério Público**, **UFG**, **HC** e **CORA** — parte do **Projeto Itaberaí**.  
**Stack:** Flask, BulmaCSS, MariaDB, Docker Swarm, Traefik/NGINX, e relatórios.
[Rosawatch](https://rosawatch.rebracam.org.br/)

### ORAL CONFERENCE
- [Pink APP: Strategy for resolving breast cancer screening actions according to the ITABERAÍ project](https://www.mastology.org/wp-content/uploads/2023/12/MAS-v33Suppl1_04.pdf)
- [Preliminary results of breast cancer screening based on physical breast examination by community health agent (ACS) – Projeto ITABERAÍ](https://www.mastology.org/wp-content/uploads/2023/12/MAS-v33Suppl1_07.pdf)
- [Adherence of community health agents (ACS) to a breast cancer screening program – ITABERAÍ project](https://www.mastology.org/wp-content/uploads/2023/12/MAS-v33Suppl1_17.pdf)
---

## 📊 Estatísticas GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=edmaker89&show_icons=true&theme=tokyonight)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=edmaker89&layout=compact&theme=tokyonight)

---

## 🚀 Roadmap pessoal / próximos passos

- Evoluir orquestração para **Kubernetes** de forma prática (migrar partes críticas primeiro).  
- Implementar **observabilidade completa** (logs centralizados, métricas e alertas).  
- Automatizar pipelines CI/CD com testes e estratégias de deploy seguras (blue/green e canary)
- Implementar microsserviços e mensageria, filas
- Implementar caches robustos
- Escrever artigos técnicos e estudos de caso em [edmaker.dev.br](https://edmaker.dev.br) sobre a arquitetura do Projeto Itaberaí e a jornada de containers → orquestração.
