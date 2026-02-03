🚀 **Case: Automação e Consolidação de Dados em Escala (77 Unidades)**
<img width="1748" height="904" alt="image" src="https://github.com/user-attachments/assets/f90ee6b3-11b0-459d-ac8f-abf65a119742" />

<img width="1654" height="941" alt="image" src="https://github.com/user-attachments/assets/9737e534-c60a-48af-8681-1e3ec8922076" />

<img width="1773" height="805" alt="image" src="https://github.com/user-attachments/assets/3ef9de98-098f-4d24-b4ad-b849a6e3206f" />

📋 **O Problema (O Desafio)**
Imagine a tarefa de consolidar mensalmente o inventário de 77 unidades (oficinas) espalhadas pelo país. Cada unidade envia um arquivo Excel (.xlsx) com centenas de linhas.

Gargalo: O processo manual levava horas, era suscetível a erros de digitação e falhas de formatação.

Barreira Técnica: As ferramentas convencionais e scripts padrão do Google enfrentavam erros de latência e segurança (timeout) ao tentar ler e converter arquivos Excel simultaneamente.

🛠 **A Solução Técnica**
Desenvolvi um ecossistema de automação utilizando Google Apps Script (GAS) e otimização de infraestrutura no Google Drive.

Destaques da Implementação:

Otimização de Performance: Implementei um fluxo de conversão em massa de .xlsx para Google Sheets Nativo, reduzindo o tempo de processamento do script em 80%.

Robustez de Dados: O script foi programado para varrer dinamicamente os IDs das pastas, localizar as abas corretas (mesmo com variações de nome como "Estoque 2025" ou "2026") e realizar a transcrição fiel de dados, preservando valores zerados e campos em branco essenciais para a auditoria.

Interface Simplificada (UX): Criei um painel de controle com um botão disparador ("Botão de Atualização") para que o usuário final não precise interagir com o código, tornando a solução acessível a qualquer colaborador.

💻 **O Script Final (Snippet para Portfólio)**
Aqui está o coração da solução: um script resiliente que utiliza MimeType para filtragem e getValues para captura massiva.

📊 **Resultados Alcançados**
Eficiência: Redução do tempo de consolidação de horas para menos de 5 minutos.

Confiabilidade: 100% de integridade nos dados extraídos, sem perda de informações por células vazias.

Escalabilidade: O sistema está pronto para suportar 100+ unidades sem necessidade de alteração no código.
