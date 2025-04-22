# Projeto Azure - Armazenamento de Blobs

## 🌐 Introdução à Nuvem e Azure

Neste projeto, mergulhei no universo da computação em nuvem com foco nos recursos da **plataforma Azure**. Comecei entendendo os **benefícios da nuvem**, os **modelos de serviço (IaaS, PaaS, SaaS)** e as **estratégias de armazenamento** oferecidas por essa poderosa plataforma.

Aprendi sobre os principais componentes da arquitetura do Azure, como **Regiões**, **Zonas de Disponibilidade**, **Assinaturas**, **Grupos de Recursos** e **Grupos de Gerenciamento**, além de explorar os serviços de computação, rede e armazenamento.

## 🚀 Projeto Hands-on: Crie um Armazenamento de Blobs

A seguir, estão as etapas que desenvolvi para concluir o projeto prático de criação de um serviço de armazenamento de blobs no Azure:

### 📌 Introdução
Iniciei o projeto compreendendo os objetivos: criar um ambiente funcional na nuvem utilizando os serviços essenciais do Azure e realizar o armazenamento de imagens usando o **Blob Storage**.

### 🛠️ Criando um Resource Group e SQL Database
Configurei um **Resource Group** para organizar os recursos e, em seguida, criei um **SQL Database** para armazenar os dados da aplicação. Isso permitiu o gerenciamento centralizado e seguro das informações.

### ☁️ Criando um Storage Account
Criei uma **Storage Account**, essencial para armazenar os blobs, como arquivos de imagem. Defini o nome globalmente exclusivo, tipo de redundância e camada de acesso apropriada.

### 🗃️ Configurando o Banco de Dados e Criando a Tabela de Produtos
No banco de dados SQL, criei uma tabela chamada **Produtos** que armazena os detalhes dos itens e o link da imagem armazenada no blob. Realizei as configurações de conexão e permissões necessárias.

### 🖼️ Implementando o Salvamento de Imagens no Blob Storage
Desenvolvi uma funcionalidade que permite fazer o **upload de imagens** diretamente para o **Blob Storage**. Cada imagem é vinculada a um produto no banco de dados, garantindo integridade e acessibilidade via URL pública ou privada.

### ✅ Finalizando o Projeto
Realizei os testes finais, garantindo que todas as integrações estavam funcionais e seguras. Validei o armazenamento, as conexões com o banco de dados e o acesso às imagens hospedadas no blob. Projeto concluído com sucesso!

---

## 📚 Conclusão

Esse projeto me proporcionou uma visão prática sobre como utilizar os serviços da nuvem Azure para construir aplicações escaláveis e eficientes. Através das etapas desenvolvidas, compreendi como orquestrar recursos como **SQL Database**, **Storage Account** e **Blob Storage**, criando um ambiente funcional para armazenar e manipular dados na nuvem.

---

🔗 *Quer aprender mais? Acesse a plataforma oficial da Microsoft ou leia os artigos em:*  
https://web.dio.me/articles