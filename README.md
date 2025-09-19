# resumo-do-lab
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Nuvem Privada: As organizações criam o ambiente em nuvem em seu próprio Datacenter.

Nuvem publica: Ex: Fornecida pela Microsoft.

Nuvem Hibrida: É o melhor dos dois mundos(Privada + Publica)

Capex: Despesas de capitais - gasto para criar o ambiente - reduz com o tempo ex: comprou mais um servidor para o ompremiss -capex coloca o investimento na frente.

Opex:  Despesas operacionais - Gasto com produtos e serviços - seja cobrado imediato - adiciono mais um recurso na nuvem - opex - adiquiri e depois paga.

LAboratório DIO.

## 🎯 Objetivos de Aprendizagem
- Aplicar os conceitos aprendidos em um ambiente prático.
- Documentar processos técnicos de forma clara e estruturada.
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.

---

## 🛠️ Passo a Passo Realizado
1. **Acessar o Portal do Azure**  
   - Portal: [https://portal.azure.com](https://portal.azure.com)  
   - Fiz login com minha conta Microsoft.  

2. **Criar Grupo de Recursos**  
   - Nome: `meu-grupo-recursos`  
   - Região: *Brazil South*  

3. **Criar Máquina Virtual (VM)**  
   - Sistema operacional: **Windows Server 2019 Datacenter** (pode ser Linux, se preferir)  
   - Tamanho: `Standard_B1s`  
   - Usuário admin: `azureuser`  
   - Senha: definida durante a criação  

4. **Configuração de Rede**  
   - Criado IP público.  
   - Porta RDP (3389) liberada para acesso remoto.  

5. **Conectar à VM**  
   - Baixei arquivo `.rdp` e conectei usando Remote Desktop.  
   - Testei login com usuário e senha criados.  

6. **Encerrar/Testar a VM**  
   - Após validações, desliguei a VM para evitar custos.   🎯 Objetivos do Desafio
- Consolidar os conhecimentos adquiridos sobre **Banco de Dados no Azure**.  
- Criar e configurar uma instância de **Azure SQL Database**.  
- Documentar os processos técnicos de forma clara e organizada.  
- Utilizar o **GitHub** como ferramenta para compartilhar documentação técnica.  
- Construir um portfólio público de projetos que poderá ser usado em entrevistas.  

---

## 🛠️ Passo a Passo Realizado

1. **Acessar o Portal do Azure**  
   - URL: [https://portal.azure.com](https://portal.azure.com)  
   - Login realizado com conta Microsoft.  

2. **Criar Grupo de Recursos**  
   - Nome do grupo: `dio-grupo-banco`  
   - Região: *Brazil South*  

3. **Criar Servidor SQL**  
   - Nome do servidor: `servidor-sql-dio`  
   - Usuário administrador: `azureuser`  
   - Senha: criada durante a configuração  

4. **Criar Banco de Dados**  
   - Nome do banco: `db-dio-projeto`  
   - Camada de desempenho: `Basic` (ideal para testes)  

5. **Configurar Firewall/IP**  
   - Liberação do IP local para permitir acesso externo.  
   - Habilitado acesso via portal do Azure.  

6. **Conectar ao Banco**  
   - Ferramenta utilizada: **Azure Data Studio**  
   - Teste de conexão bem-sucedido.  
   - Comando executado para validar:  
     ```sql
     SELECT @@VERSION;
     ```  

7. **Encerramento/Teste**  
   - Banco criado com sucesso e acessível.  
   - Serviço pausado após testes para evitar custos desnecessários.
   -   
## 📌 Descrição
Este repositório foi criado como parte do desafio da **DIO** para consolidar os conhecimentos adquiridos durante o laboratório prático.  
O objetivo é documentar os principais aprendizados e reforçar a importância do GitHub como ferramenta para organização e compartilhamento de estudos técnicos.

## 📝 O que Aprendi

Durante o desenvolvimento do lab, aprendi a:

- Compreender melhor os **componentes de arquitetura do Azure**.  
- Entender a função de **grupos de recursos (Resource Groups)** como forma de organizar e gerenciar serviços.  
- Criar e configurar serviços no **Portal do Azure**, entendendo a relação entre **recursos, regiões e assinaturas**.  
- Reconhecer a importância de boas práticas de governança, como apagar recursos quando não estão mais em uso para evitar custos.  
- Utilizar o **GitHub** como repositório de conhecimento técnico e como ferramenta para expor meu portfólio profissional.  
- Documentar processos técnicos de forma estruturada com **Markdown**.

- Objetivos do Desafio
- Aplicar os conceitos aprendidos em um ambiente prático.  
- Documentar processos técnicos de forma clara e estruturada.  
- Utilizar o **GitHub** como ferramenta para compartilhamento de documentação técnica.  

---

## 📝 Resumo do que aprendi
Durante a execução do laboratório, aprendi a:  

1. **Criar e gerenciar recursos no Azure** por meio do portal.  
2. **Organizar recursos em Resource Groups**, facilitando a administração.  
3. **Configurar uma instância no Azure**, entendendo conceitos de máquinas virtuais, redes e armazenamento.  
4. **Navegar na interface do Azure**, explorando as principais funcionalidades do portal.  
5. **Documentar processos técnicos no GitHub**, utilizando o arquivo `README.md` em Markdown.  

---

## 🛠️ Passo a Passo realizado
1. Acesse o portal do Azure.  
2. Crie e configure os recursos necessários para o laboratório.  
3. Organize os recursos em um **Resource Group**.  
4. Teste a execução do ambiente.  
5. Documente a experiência neste repositório.
