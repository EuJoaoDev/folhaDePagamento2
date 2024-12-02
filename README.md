# 🌟 Folha de Pagamento 2.0

---

## 🗂️ Estrutura do Projeto

📦 FolhaPagamento2.0
├── 📂 classes
│   └── Funcionario.ts
├── 📄 .gitignore
├── 📄 README.md
├── 📄 index.ts
├── 📄 package-lock.json
├── 📄 package.json
├── 📄 teste.ts
├── 📄 tsconfig.json
└── 📄 typescript.txt


---

## 📖 Sobre o Projeto

**Folha de Pagamento 2.0** é um sistema de gerenciamento de funcionários e cálculo de folha de pagamento desenvolvido em **Node.js** com **TypeScript**.  
Projetado para ser executado diretamente no **terminal integrado do VS Code**, oferece funcionalidades como:

- Cadastro de funcionários 👥
- Registro de horas trabalhadas ⏱️
- Geração de relatórios salariais 📊

---

## ⚙️ Configuração no VS Code

### **1. Abrir o Projeto**
   - No VS Code, vá em **File > Open Folder** e selecione a pasta do projeto.

### **2. Instalar Dependências**
   - Abra o terminal integrado (`Ctrl + J`) e execute:
     ```bash
     npm install
     ```

### **3. Executar o Projeto**
   - No terminal integrado, digite:
     ```bash
     npx ts-node index.ts
     ```

---

## 🚀 Fluxo de Execução no Terminal Integrado

Ao rodar o projeto, o seguinte menu será exibido:

--- Sistema de Folha de Pagamento --- 1 - Adicionar Funcionário 2 - Registrar Horas Trabalhadas 3 - Exibir Lista de Funcionários 4 - Exibir Relatório de Pagamento 5 - Sair


**Navegue pelo sistema interativo:**  
- Selecione a opção desejada.  
- Insira os dados conforme solicitado.

---

## 🧩 Principais Componentes do Código

### **`index.ts` — Controlador Principal**
- **Funções Importantes:**
  - `adicionarFuncionario`: Cadastra novos funcionários.
  - `exibirLista`: Lista todos os funcionários.
  - `gerarRelatorioPagamento`: Gera um relatório completo com detalhes salariais.

### **`classes/Funcionario.ts` — Modelo de Funcionário**
- **Classe `Funcionario`:**
  - **Atributos:** `id`, `nome`, `cargo`, `taxaHoraria`, `horasTrabalhadas`.
  - **Métodos:**
    - `registrarHoras`: Registra horas trabalhadas.
    - `calcularSalarioMensal`: Calcula o salário bruto.
    - `calcularInss`: Calcula o desconto do INSS.

---

## 🎨 Atalhos Essenciais do VS Code

- **Abrir Terminal Integrado:** `Ctrl + J`
- **Formatar Código:** `Shift + Alt + F`
- **Buscar Arquivos:** `Ctrl + P`
- **Depuração (Debug):**
  - Adicione breakpoints clicando à esquerda do número da linha.
  - Pressione `F5` para iniciar o depurador.

---

## 📦 Extensões Recomendadas

- **TypeScript Essentials:** Facilita o desenvolvimento e validação do código TypeScript.
- **ESLint:** Ajuda a manter o código limpo e padronizado.
- **Prettier:** Formatação automática de código.
- **Node.js Debugging:** Facilita a depuração de projetos Node.js diretamente no VS Code.

---

## 📝 Notas Finais

- **Experimente:** Teste diferentes taxas horárias e registre horas variadas para ver os cálculos em ação.  
- **Customização:** Adapte a lógica de cálculo ou adicione novos atributos conforme necessário.

---

🚀 **Pronto para Gerenciar Folhas de Pagamento? Execute o Projeto e Explore no VS Code!** 🚀
