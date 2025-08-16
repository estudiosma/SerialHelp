# 🖥️ MA-SerialHelp

**MA-SerialHelp** é uma ferramenta desenvolvida para a visualização e gravação online de sinais adquiridos por dispositivos de comunicação serial. Oferece uma interface intuitiva e está otimizada para uso educacional, de pesquisa e experimental.

![Interface MA-SerialHelp](img/Product.png)

---

## 🚀 Funcionalidades do Software

- ✅ Conexão direta e fácil com dispositivos baseados em porta serial (COM).
- 📈 Visualização online de sinais no domínio do tempo.
- 💾 Registro de dados em arquivos de texto `.txt` para análise posterior.
- ⚙️ Configuração de parâmetros-chave para visualização, como taxa de amostragem (Fs) e duração da janela de tempo.

---

## Elementos da Interface

![Interface MA-SerialHelp](img/System.png)

1. **Conectar / Desconectar**  
   Estabelece ou encerra a conexão com um dispositivo serial.

2. **Configurações**  
   Permite selecionar a porta COM e configurar os parâmetros de comunicação do dispositivo.

3. **Limpar**  
   Limpa o gráfico atual.

4. **Enviar**  
   Envia comandos para o dispositivo pela porta serial.

5. **Plotar**  
   - Ativado: Exibe os dados recebidos em um gráfico em tempo real.  
   - Desativado: Exibe os dados em formato de texto, sem gerar gráfico.

6. **Fs (Hz)**  
   - Define a taxa de amostragem a ser usada para desenhar o eixo do tempo.  
   👉 *Importante*: Este **Fs** não altera a taxa de amostragem do dispositivo; ele apenas informa ao monitor como distribuir os dados no eixo do tempo, assumindo que eles chegam periodicamente.

7. **Tempo (s)**  
   - Define o comprimento visível do gráfico em segundos.  
   *Exemplo*: Se definido como 10 s, a janela exibirá apenas os últimos 10 segundos de dados, rolando automaticamente conforme chegam novos dados.

8. **Salvar**  
   Salva os dados plotados em um arquivo de texto para análise posterior.

9. **Gráfico**  
   Área principal onde o sinal é exibido (Amplitude vs. Tempo), atualizada dinamicamente.

10. **Entrada de texto**  
    Campo para enviar comandos manuais ao dispositivo via serial.

---

## 📌 Requisitos do Sistema

- Sistema operacional: **Windows 7, 8, 10 ou 11**.  
- Porta USB.

---

## 📥 Download e instalação fácil

Basta baixar e executar o arquivo **MA-SerialHelp vX.X.exe** e seguir as instruções na tela.

---

## 📣 Tem dúvidas ou precisa de suporte?

📲 **Entre em contato diretamente por:**  

[**WhatsApp EC**](https://wa.me/593979287659?text=Ol%C3%A1%21+Quero+adquirir+o+dispositivo+%2AAccelHelp)  
[**WhatsApp BR**](https://wa.me/5521998957829?text=Ol%C3%A1%21+Quero+adquirir+o+dispositivo+%2AAccelHelp)

---

## Créditos e atribuição

Este projeto foi desenvolvido por **Estudios MA**, com foco em sistemas de aquisição biomédica e análise de sinais.

Se você utilizar este código, hardware ou documentação como parte de seu projeto pessoal ou acadêmico, **por favor, referencie:**  

Estudios MA, Molina-Vidal, D.A. (2025). *SerialHelp*. Disponível online: https://github.com/estudiosma/SerialHelp

---

## ✍️ Autor

**Estudios MA – Engenharia Eletrônica e Biomédica**  
Eng. Danilo Molina, M.Sc  
🌐 [https://linkfly.to/EstudiosMA](https://linkfly.to/EstudiosMA)
