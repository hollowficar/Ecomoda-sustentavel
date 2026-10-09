<div align="center">

# Haruki Ecomoda 🛍️✨

Web app de e-commerce de vestuário. Uma interface moderna que une a cultura urbana a uma experiência de compra interativa, desenvolvida como protótipo front-end para fins educacionais.

<br>

![Versão](https://img.shields.io/badge/VERSÃO-V2.0.0-5865F2?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-PROJETO_ACADÊMICO-FF9800?style=for-the-badge)
![Stack](https://img.shields.io/badge/STACK-HTML5_%7C_CSS3_%7C_JS-F1C40F?style=for-the-badge)

<br>

### [🛒 Visualizar Interface (Front-end)](#)
<small>Web • Responsivo • Protótipo de Interatividade</small>

<br>

> 🔒 **REPOSITÓRIO OFICIAL • HARUKI ECOMODA**
> 
> Desenvolvido e mantido por Harukihk.

</div>

---

> [!WARNING]
> **Aviso de Projeto Escolar / Acadêmico**
> Este repositório contém um projeto de cunho estritamente educacional. Trata-se de um **protótipo Front-end** e **não é 100% funcional**. A aplicação não possui integração com um banco de dados real (Back-end) ou gateways de pagamento (Checkout real). As funcionalidades aqui presentes servem para demonstrar lógicas de Interface de Usuário (UI) e Experiência do Usuário (UX).

## 📌 O que o projeto apresenta no momento?

Apesar de ser um protótipo, a aplicação demonstra conceitos sólidos de desenvolvimento web, onde o cliente tem autonomia para simular a personalização da sua encomenda.

<details>
  <summary>🎨 <b>Visual Shopping (Troca Dinâmica de Cor)</b></summary>
  <br>
  O cliente pode alternar entre as cores disponíveis (Azul, Preta, Branca) utilizando botões interativos (<i>swatches</i>). O JavaScript deteta o clique e substitui instantaneamente a imagem principal do produto sem recarregar a tela.
</details>

<details>
  <summary>📏 <b>Gestão de Tamanhos</b></summary>
  <br>
  Interface de seleção intuitiva para os tamanhos (P, M, G) com feedback visual imediato para a opção selecionada, simulando a escolha antes de adicionar ao carrinho.
</details>

<details>
  <summary>🚚 <b>Simulação de Cálculo de Frete</b></summary>
  <br>
  Integração de um simulador de CEP na própria página do produto. O cliente introduz o seu código postal e recebe uma estimativa de valor imediata.
</details>

## 🛠️ Limitações e Lógica Simulada (Mock)

> [!TIP]
> Como não há um servidor back-end real rodando a API dos Correios ou transportadoras, o **Cálculo de Frete foi simulado (Mock)** diretamente no Front-end com JavaScript puro.

**Como funciona a simulação:**
O script sanitiza o campo de digitação (removendo qualquer caractere que não seja número) e valida se o CEP possui exatamente 8 dígitos. O cálculo do valor falso é feito com base no último dígito do CEP digitado:
*   **Terminados em número Par:** R$ 19,90
*   **Terminados em número Ímpar:** R$ 24,90

O botão de "Adicionar ao carrinho" no momento apenas cumpre o papel visual e de design, não armazenando a sessão de compra.

## 🚀 Instruções de Execução

1. Faça o download ou clone este repositório.
2. Certifique-se de que os seguintes arquivos estão no mesmo diretório:
   - `index.html`
   - `style.css`
   - Imagens (ex: `logo.png`, `sobre.png`, `camiseta azul.png`, etc.)
3. Abra o arquivo `index.html` em qualquer navegador web moderno.
4. **Teste a interatividade Front-end:** Clique nas cores na seção "Sua Peça" para ver a imagem trocar e insira um CEP válido (ex: `01001000`) para testar a lógica do simulador.
