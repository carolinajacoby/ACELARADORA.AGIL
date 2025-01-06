# Sistema de Gerenciamento de Produtos - AgilStore 💻

Este sistema foi desenvolvido em Python para gerenciar o inventário de produtos de uma loja fictícia chamada **AgilStore**. Ele permite o controle completo de produtos, incluindo cadastro, atualização, exclusão e geração de relatórios.

# Tecnologias Utilizadas #

- 🐍 **Python**: Linguagem principal utilizada no desenvolvimento.
- ✅ **Pytest**: Framework utilizado para testes automatizados.
- 📄 **JSON**: Formato utilizado para persistência de dados.
- 💻 **CLI (Command-Line Interface)**: Interface do sistema baseada em linha de comando.

## 👩‍💻 Funcionalidades Adicionadas pela Desenvolvedora  

**Cadastro de Lote, Marca e Valor de Custo**: Para melhorar a gestão do inventário e facilitar a identificação de produtos em situações críticas, como **recalls**, foram adicionados campos para **lote**, **marca** e **valor de custo** aos produtos cadastrados no sistema.

  ### ⚙️ Como Funciona: 
**Lote**: Cada produto pode ser associado a um número de lote. Esse campo é crucial em caso de **recall** (quando a empresa precisa recolher produtos defeituosos). O lote permite rastrear rapidamente quais unidades de um produto foram afetadas.

**Marca**: O sistema agora permite registrar a **marca** do produto, o que facilita a organização do inventário e a identificação de produtos de diferentes fabricantes.

**Valor de Custo**: O **valor de custo** é registrado para cada produto, permitindo calcular a margem de lucro e gerenciar o controle financeiro do inventário.

### 🌟 Benefícios:
 - ✅ Facilidade na rastreabilidade de lotes para recalls.
- 💡 Melhor controle financeiro com registro do custo.
- 🚀 Organização eficiente com o uso de categorias e marcas.
  
### Exemplo:
Se um produto eletrônico de marca **Samsung** for parte de um **recall** e o lote afetado for **L123**, a funcionalidade de lote ajuda a localizar todas as unidades desse lote rapidamente, tornando o processo de recall muito mais eficiente.
  

## Funcionalidades Principais

- **Adicionar Produto**: Cadastro com nome, categoria, marca, lote, preço e quantidade. ✅
- **Listar Produtos**: Visualização em formato de tabela.✅
- **Atualizar Produto**: Modificação de dados existentes.✅
- **Excluir Produto**: Remoção segura com confirmação.✅
- **Buscar Produto**: Busca por ID, nome, categoria, marca ou lote.✅
- **Persistência de Dados**: Armazena informações em JSON.✅

## Como Avaliar e Testar o Sistema

Para avaliar e testar o sistema de forma rápida, siga estas instruções:

### **1. Acesse o Repositório no GitHub**
- Vá para o repositório do projeto: [ACELARADORA.AGIL](https://github.com/carolinajacoby/ACELARADORA.AGIL).

### **2. Clone o Repositório**
- **No GitHub**, clique no botão **"Code"** e copie o link do repositório.
- No seu terminal, execute o seguinte comando para clonar o repositório:
  ```bash
  git clone https://github.com/carolinajacoby/ACELARADORA.AGIL.git
  
### **3. Instale as Dependências (se necessário)**
```bash
cd ACELARADORA.AGIL
```

- Instale as dependências do Py
````bash
pip install -r requirements.txt
````

### **4. Execute o sistema**
- Rode o arquivo principal para iniciar o sistema
````bash  
python gerenciador_carolaceleradora.py
````

### **5. Passo a Passo para Executar os Testes**

- O sistema conta com alguns testes para garantir o funcionamento das principais funcionalidades.  Siga as instruções abaixo para executá-los:

#### **5.1 Verificar as dependências de teste**

````pip install pytest````

####  **5.1 Executar os testes**
- Para rodar todos os testes do projeto, use o seguinte comando na raiz do repositório:

````pytest````

#### **5.2 Visualize o resultado dos testes**

- O terminal exibirá um relatório indicando quais testes passaram, falharam ou foram ignorados

### **6. Contribuições**

Contribuições são bem-vindas! Siga as etapas abaixo para colaborar:

1. Faça um fork do repositório.
2. Crie uma branch para sua funcionalidade ou correção: `git checkout -b minha-feature`.
3. Faça as alterações necessárias e commit: `git commit -m "Descrição da alteração"`.
4. Envie as alterações para o seu fork: `git push origin minha-feature`.
5. Abra um Pull Request no repositório original.

Obrigado por contribuir!

### **📧 7. Entre em Contato Comigo!**
Criado por [Carolina Jacoby](https://github.com/carolina_jacoby).

Se você tiver dúvidas ou encontrar problemas, entre em contato através do email: **anacarolinajacoby0@gmail.com**.





