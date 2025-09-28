# ⚙️ Hiago Car - Assistente Virtual  

Este projeto é um **chatbot em HTML, CSS e JavaScript** desenvolvido para a oficina **Hiago Car**.  
Ele auxilia clientes de forma rápida e prática, permitindo:  

- Solicitar **orçamentos automáticos** com geração de PDF.  
- Realizar **agendamentos de serviços**, com integração ao **Google Sheets**.  
- Visualizar a **lista de serviços disponíveis e seus valores**.  
- Falar diretamente com um atendente via **WhatsApp**.  

---

## 📂 Estrutura do Projeto  

- `index.html` → Contém todo o código do chatbot (HTML, CSS e JS).  
- Integração com **Google Sheets** via **Google Apps Script**.  
- Geração de **PDF** utilizando a biblioteca [jsPDF](https://github.com/parallax/jsPDF).  

---

## 🚀 Funcionalidades  

1. **Menu Principal**  
   - 1️⃣ Solicitar Orçamento 🧾  
   - 2️⃣ Agendar Serviço 📅  
   - 3️⃣ Conhecer nossos Serviços 🛠️  
   - 4️⃣ Falar com Atendente 📞  

2. **Orçamento Automático**  
   - Cliente informa **nome, placa, modelo** e seleciona os serviços desejados.  
   - O sistema calcula o valor total.  
   - É possível **baixar o orçamento em PDF**.  

3. **Agendamento de Serviços**  
   - Cliente escolhe **data e horário disponível**.  
   - Dados são enviados automaticamente para o **Google Sheets**.  
   - Confirmação enviada para o WhatsApp da oficina.  

4. **Lista de Serviços** (com valores)  
   - Alinhamento → R$ 80  
   - Balanceamento → R$ 70  
   - Troca de Óleo → R$ 150  
   - Troca de Filtros → R$ 90  
   - Suspensão → R$ 200  

5. **Atendimento via WhatsApp**  
   - Botão abre o WhatsApp com mensagem automática para o número da Hiago Car.  

---

## ⚙️ Tecnologias Utilizadas  

- **HTML5** → Estrutura da aplicação  
- **CSS3** → Estilização do chat  
- **JavaScript (Vanilla JS)** → Lógica do chatbot  
- **[jsPDF](https://cdnjs.com/libraries/jspdf)** → Geração de orçamento em PDF  
- **Google Apps Script** → Integração com Google Sheets  
- **WhatsApp API** → Abertura de conversa automática  

---

## 📑 Como Usar  

1. Baixe o código ou clone o repositório:  
   ```bash
   git clone https://github.com/seu-repositorio/hiago-car-chatbot.git
