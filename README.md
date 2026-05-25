# ⚡ Easy Power - Sistema de Gestão de Geradores e Frota

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=#00C7B7)

Um sistema completo (ERP + CRM) desenvolvido para empresas de locação e manutenção de geradores de energia. O projeto centraliza o controle da frota, histórico de manutenções, funil de vendas e gestão de estoque de peças em uma única plataforma intuitiva.

---

## 📸 Demonstração

<div align="center">
  
  <img width="1920" height="913" alt="image" src="https://github.com/user-attachments/assets/eb70cc38-7d83-42d5-b073-5c2d80d9d240" />

  **Tela de Login:** Porta de entrada com design moderno e responsivo, oferecendo autenticação segura e acesso à criação de novas contas.

  <img width="1906" height="911" alt="image" src="https://github.com/user-attachments/assets/9dad514e-d7ee-4b85-b291-4ab795f47f90" />

  **Dashboard:** Painel gerencial principal com indicadores-chave (KPIs), métricas financeiras, gráficos de valor por categoria e tabela de movimentações recentes.

  <img width="1909" height="911" alt="image" src="https://github.com/user-attachments/assets/4d749dd9-3dca-4424-be21-c07075f3fed8" />
  <img width="1911" height="913" alt="image" src="https://github.com/user-attachments/assets/3a170387-7379-4878-9688-8ca534ef48a1" />

  **Gestão de Estoque:** Controle detalhado de peças e insumos (SKU, quantidade, preço e status) acompanhado de um modal ágil para cadastro de novos itens.
  
  <img width="1907" height="914" alt="image" src="https://github.com/user-attachments/assets/6710e3c7-f59f-49c2-b5cf-bd87a98af1f9" />
  <img width="1915" height="910" alt="image" src="https://github.com/user-attachments/assets/76fadce8-030c-4d87-a805-958a91670f3c" />

  **Frota de Geradores:** Central para listagem e gerenciamento dos ativos. Inclui formulário para registro de novos equipamentos com dados técnicos (kVA, modelo, horímetro e status).
  
  <img width="1909" height="910" alt="image" src="https://github.com/user-attachments/assets/770244fb-0bc0-4428-9587-569ea65ec6eb" /> 
  <img width="1909" height="910" alt="image" src="https://github.com/user-attachments/assets/c76c7563-e438-42de-8310-c0002d37ef05" />
  <img width="591" height="836" alt="image" src="https://github.com/user-attachments/assets/720cf416-ca06-4c9a-9050-15e85b17bc1b" />

  **Comercial & Propostas:** Módulo de vendas duplo. Conta com um formulário para criar orçamentos detalhados e um funil visual (Kanban) para acompanhar as etapas de negociação.

  <img width="1899" height="920" alt="image" src="https://github.com/user-attachments/assets/4803462e-77e4-44a5-b1c2-43ed3d197666" />
  <img width="1898" height="883" alt="image" src="https://github.com/user-attachments/assets/fabb7a13-7212-4afb-869b-1b7018906b51" />

  **Gestão de Clientes:** Diretório organizado em formato de cards, exibindo dados de contato rápido, documentação e o valor total já investido por cada cliente.

  <img width="1906" height="915" alt="image" src="https://github.com/user-attachments/assets/4ac7c9e8-572c-4225-a15a-8cb4100166c3" />

  **Histórico de Atividades:** Log do sistema focado em rastreabilidade, registrando eventos e ações recentes para auditoria.

  <img width="1903" height="908" alt="image" src="https://github.com/user-attachments/assets/093a94d8-adc1-4aa6-8a2e-b82e886d7ab6" />

  **Configurações:** Painel de preferências do usuário, incluindo alternância para o Modo Escuro (Dark Mode) e informações técnicas sobre a versão do ambiente.

</div>

---

## 🎯 O Problema Resolvido

Empresas de engenharia e locação de maquinário pesado costumam perder o controle dos custos de manutenção e do status de seus ativos utilizando planilhas descentralizadas. Este sistema resolve o problema unificando os setores:
1. **Operacional:** Controle em tempo real de quais geradores estão disponíveis, alugados ou em manutenção, acompanhando o horímetro e número de série.
2. **Comercial:** Um CRM integrado com um funil de vendas (Kanban) para gerenciar propostas e vincular contratos aos clientes cadastrados.
3. **Financeiro e Técnico:** Registro de intervenções preventivas e corretivas, gerando gráficos de maiores custos e relatórios de atividades detalhados.

## ✨ Principais Funcionalidades

* **Controle de Ativos:** Cadastro de geradores com especificações de potência (kVA), modelo, localização e upload de imagens.
* **Histórico Financeiro:** Lançamento de manutenções vinculadas a cada equipamento, calculando o custo total da frota e separando os ativos mais caros.
* **Funil de Vendas (Kanban):** Gestão visual de propostas comerciais (Proposta, Negociação, Fechado, Perdido) integradas ao banco de dados de clientes.
* **Gestão de Estoque:** Controle de peças de reposição (filtros, óleo, correias) com registro de entradas e saídas (Transactions).
* **Segurança de Dados:** Banco de dados relacional protegido por políticas de RLS (Row Level Security).

---

## 🛠️ Tecnologias Utilizadas

**Front-end:**
* React (Vite) com TypeScript
* Tailwind CSS (para estilização rápida e responsiva)
* Lucide React e FontAwesome (Ícones)
* Hospedagem: Netlify

**Back-end & Banco de Dados:**
* Supabase (PostgreSQL como banco de dados relacional)
* Supabase Storage (para armazenamento de imagens da frota)
* Políticas de Segurança RLS (Row Level Security)

**Desenvolvimento & Ferramentas:**

* AI-Assisted Development: Google Gemini (como assistente de Pair Programming para auxílio na tipagem avançada do TypeScript, otimização de queries e refatoração de componentes).

---

## ⚙️ Arquitetura do Sistema

O fluxo de gerenciamento de dados segue a estrutura:
1. A interface em React consome serviços isolados (ex: `generatorService.ts`) que tipam os dados utilizando interfaces do TypeScript.
2. Os serviços se comunicam com o Supabase via requisições assíncronas para realizar o CRUD nas tabelas relacionais (`generators`, `clients`, `maintenance_records`, `proposals`).
3. O histórico de manutenções está ligado aos geradores por chaves estrangeiras (`CASCADE DELETE`), garantindo a integridade do banco.
4. O *Build* final do Vite é otimizado e implantado na plataforma da Netlify, operando sem a necessidade de um servidor Node.js intermediário graças à arquitetura BaaS (Backend as a Service) do Supabase.

---

## 👨‍💻 Autor

**Christian Duarte** Graduando em Ciência da Computação (5º período) pela Universidade Anhanguera. Desenvolvi este sistema full-stack para aplicar meus conhecimentos em integrações de banco de dados, tipagem estática e arquitetura de componentes escaláveis. Durante o desenvolvimento, utilizei o Google Gemini como assistente de inteligência artificial, o que me permitiu acelerar o debugging e aplicar boas práticas estruturais no código.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christianduart)
