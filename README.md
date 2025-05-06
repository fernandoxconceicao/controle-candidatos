# 📋 Sistema de Validação de Candidatos – Processo Seletivo

Este projeto em **Java** simula um pequeno processo seletivo, com validações e interações automatizadas com candidatos. O sistema verifica valores de salário pretendido, realiza simulações de contato com os participantes e imprime relatórios simples no terminal.

## 🚀 Funcionalidades

* Seleção de até 5 candidatos com base no salário pretendido
* Simulação de tentativa de contato com candidatos (até 3 tentativas por pessoa)
* Impressão organizada da lista de candidatos selecionados
* Avaliação de propostas salariais

## 📂 Estrutura do Código

O código principal está contido na classe `ProcessoSeletivo.java`, com os seguintes métodos:

* `main(String[] args)` – Executa o processo de contato com os candidatos
* `entrandoEmContato(String candidato)` – Simula ligações e controle de tentativas
* `atender()` – Gera aleatoriamente se o candidato atendeu ou não
* `selecaoCandidatos()` – Seleciona os primeiros 5 candidatos com salário dentro do limite
* `valorPretendido()` – Gera salário aleatório entre 1800 e 2200
* `analisarCandidato(double salario)` – Compara valor com salário-base e define ação
* `imprimirSelecionados()` – Mostra candidatos selecionados de duas formas

## 🧪 Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-projeto.git
   ```
2. Navegue até o diretório do projeto:

   ```bash
   cd nome-do-projeto
   ```
3. Compile o arquivo:

   ```bash
   javac candidatura/ProcessoSeletivo.java
   ```
4. Execute:

   ```bash
   java candidatura.ProcessoSeletivo
   ```

## 🛠 Requisitos

* Java JDK 21 (ou compatível)
* Terminal ou IDE compatível (IntelliJ, VS Code, Eclipse etc.)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

---

Se quiser, posso gerar esse README em formato pronto para colar direto no GitHub. Deseja isso?
