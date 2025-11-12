## **Automatic Search and Assembly of Biological Sequences - ASABS_2.0 🧬**

O programa "ASABS – Automatic Search and Assembly of Biological Sequences" é uma ferramenta desenvolvida para automatizar e otimizar a análise de sequências biológicas, com especial foco em genômica e bioinformática. Sua principal função é realizar a busca eficiente por sequências biológicas específicas em grandes bancos de dados e, em seguida, montá-las de forma precisa a partir de fragmentos menores, permitindo a reconstrução de genomas ou outras sequências biológicas de interesse.

---

### Índice 📚
1. [Instruções de Instalação](#instruções-de-instalação)
2. [Instruções de Uso](#instruções-de-uso)
3. [Solução de Problemas](#solução-de-problemas)
4. [Suporte](#suporte)

---

### Instruções de Instalação 🛠️
1. **Baixar o Pacote ASABS** 📥
   - Localize o arquivo chamado `ASABS-PACK.zip` na sua pasta de Downloads.
  
2. **Extrair o Pacote** 📄
   - Clique com o botão direito no arquivo e selecione "Extrair Aqui" para descompactar o conteúdo.
   - Alternativamente, use o terminal:
     ```bash
     tar zxvf ASABS-PACK.zip
     cd ASABS-PACK
     ```

3. **Verificar Conteúdo** 📦
   - Certifique-se de que a pasta extraída contém:
     - `ASABS` (arquivo executável)
     - `Instruções De Suporte` (instruções de suporte)
     - `Support_Menu` (para suporte offline)

4. **Abrir o Terminal** 💻
   - Clique com o botão direito em um espaço vazio dentro da pasta e selecione **"Abrir no Terminal"**.

5. **Executar o Programa** ▶️
   - No terminal, digite:
     ```bash
     ./ASABS -h
     ```
   - Este comando exibe o menu de comandos do programa.

---

### Instruções de Uso 📋
- **Preparar Arquivos de Entrada** 🗃️
  - Mova os arquivos necessários (arquivo de referência e arquivos de fragmentos) para a pasta `ASABS-PACK`.
  - Certifique-se de que o arquivo de referência esteja no formato `.fasta`. Se baixado como `.txt`, converta-o para `.fasta`.

- **Requisitos de Arquivo** 🗂️
  - O arquivo de referência deve ter comprimento adequado; sequências curtas podem levar a comparações ineficazes.

---

### Solução de Problemas ⚠️
- **Problemas Comuns de Instalação** ❗
  1. **Sem Conexão com a Internet**: Verifique se seu dispositivo está conectado à internet.
  2. **Privilégios de Sudo**: Verifique se sua conta de usuário tem direitos de administrador.
  3. **Senha Incorreta**: Certifique-se de digitar a senha correta do sudo quando solicitado.
  4. **Permissões de Arquivo**: Garanta que o programa ASABS tenha permissão para criar arquivos no diretório inicial do usuário.

- **Mensagens de Erro**: Se você encontrar erros durante a instalação ou execução, consulte o documento `Support_Menu` para etapas detalhadas de solução de problemas.

---

### Suporte ⛑️
Para ajuda adicional, visite a página de suporte online:
- [Suporte ASABS](https://sites.google.com/view/bioinfoasabs/suporte)

---
