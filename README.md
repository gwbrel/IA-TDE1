# IA-TDE1
Intelligent Agent with MCP and Voice Command

Requisitos:
- Python 3.10+
- Bibliotecas: speechrecognition, openpyxl, pyaudio (para microfone)

Como executar:
1. Instale as dependências:
   pip install speechrecognition openpyxl pyaudio
2. Execute o programa:
   python agente_mcp.py
3. Use comandos de voz como:
   - "adicionar arroz"
   - "listar produtos"
   - "enviar lista"
   - "sair"

Descrição:
O agente utiliza reconhecimento de voz para gerenciar uma lista de compras em uma planilha Excel. Ele pode adicionar, listar e enviar a lista via WhatsApp usando um link pré-preenchido. Não há interface gráfica e todo o processamento é feito localmente.
