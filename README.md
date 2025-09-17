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
   - Após validações, desliguei a VM para evitar custos.  
