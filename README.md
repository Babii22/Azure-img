# 🤖 Microsoft AI for Tech - README

📘 Este repositório reúne anotações, exemplos práticos e recursos utilizados no curso *Microsoft AI for Tech*, com foco em computação em nuvem, serviços Azure, integração de dados e boas práticas em IA.

---

## ☁️ Conceitos de Computação em Nuvem

A nuvem oferece uma maneira moderna, escalável e econômica de acessar recursos de TI pela internet. Os modelos principais são:

---

### 🧱 IaaS - Infrastructure as a Service

> 🔧 Infraestrutura sob demanda (rede, máquinas virtuais, armazenamento)

✅ O que o usuário gerencia:
- Sistema Operacional
- Aplicações
- Dados

---

### 🧰 PaaS - Platform as a Service

> 🧪 Ambiente pronto para desenvolver, testar e implantar aplicações

✅ O que o usuário gerencia:
- Aplicações e dados

---

### 🧑‍💼 SaaS - Software as a Service

> 🖥️ Aplicações completas entregues como serviço via navegador

✅ O que o usuário faz:
- Apenas consome o software, sem se preocupar com nada técnico  

---

## 🏭 Azure Data Factory

### 📌 O que é?

O *Azure Data Factory (ADF)* é um serviço de *integração de dados* em nuvem. Ele permite criar pipelines para mover, transformar e orquestrar dados de diversas fontes.

---

### 🛠️ Passos para Criar uma Data Factory:

1. 🔍 Acesse o [Portal Azure](https://portal.azure.com)
2. ➕ Vá em *Criar recurso* > Pesquise por Data Factory > *Criar*
3. 📝 Preencha as informações:
   - *Nome da Factory*
   - *Região*
   - *Grupo de Recursos* (novo ou existente)
   - *Versão:* V2
4. 📦 Crie ou selecione um Resource Group
5. 🔧 Após criação, acesse a Data Factory e comece a criar pipelines
6. 💾 Clique em *Publicar* para aplicar as alterações

---

## 🔒 Bloqueios de Recursos no Azure

Para evitar exclusões acidentais de recursos como a Data Factory, você pode aplicar *locks* diretamente no portal Azure.

### 🔐 Tipos de Lock:

- *🔒 Read-only:* Apenas leitura (sem alterações)
- *🚫 Delete:* Impede exclusão

---

### ✅ Como aplicar um bloqueio:

1. Acesse o *Resource Group* ou recurso desejado
2. No menu lateral, clique em *Bloqueios (Locks)*
3. Clique em *➕ Adicionar*
4. Preencha:
   - 🏷️ Nome: protecao-delete
   - 🔒 Tipo: Delete
   - 🗒️ Notas: (opcional)
5. 💾 Salvar

> ⚠️ Apenas usuários com permissões adequadas (Owner, Contributor com gestão de recursos) podem remover ou editar bloqueios.

---

## 🧠 Conclusão

Compreender os modelos de serviço em nuvem (IaaS, PaaS, SaaS), utilizar ferramentas como o Azure Data Factory e proteger seus recursos com bloqueios são passos essenciais para criar soluções escaláveis, seguras e modernas na plataforma Azure. 
