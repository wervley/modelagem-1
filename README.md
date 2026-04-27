📌 Sobre o projeto
A Rodway Digital é uma simulação de plataforma de reservas de viagens fluviais na região amazônica, desenvolvida como trabalho de faculdade. A aplicação permite ao usuário consultar embarcações, comparar rotas e acomodações, fazer uma reserva e gerar um QR Code que serve como bilhete digital de embarque.
O sistema é totalmente client-side (não há backend): as reservas existem apenas na sessão atual do navegador.
✨ Funcionalidades

Listagem de embarcações com fotos, horários e preços
Filtro de rotas por destino (Belém ↔ Manaus, Belém ↔ Santarém)
Três tipos de acomodação: Rede, Poltrona e Cabine
Formulário de reserva com nome, CPF e seleção de embarcação
Resumo da viagem em tempo real conforme o usuário preenche
Geração de QR Code como bilhete digital
Painel "Minhas Viagens" para visualizar e cancelar reservas
Design responsivo (mobile e desktop)
Avaliações com sistema de estrelas e políticas de cancelamento/check-in

🚤 Embarcações disponíveis
EmbarcaçãoRotaDuraçãoFaixa de preçoN/M Irmãos MirandaBelém ↔ Manaus30hR$ 158 – R$ 474F/B San Marino IIBelém ↔ Manaus30hR$ 127 – R$ 421F/B Amazonas IIBelém ↔ Santarém24hR$ 200 – R$ 379
🧭 Seções da aplicação
SeçãoDescriçãoInícioBoas-vindas, diferenciais do serviço e próximas partidasHoráriosLista de embarcações disponíveis com filtro por rotaDetalhesGaleria de imagens, comodidades, avaliações e políticasReservaFormulário de reserva com resumo dinâmicoMinhas ViagensReservas confirmadas com QR Code e opção de cancelamento
🛠️ Tecnologias utilizadas

HTML5 — estrutura semântica
Tailwind CSS (via CDN) — estilização utilitária
JavaScript (Vanilla) — toda a lógica e interatividade
Font Awesome 6.4.0 — ícones
Google Fonts (Poppins) — tipografia
QRCode.js — geração dos QR Codes dos bilhetes

📂 Estrutura do projeto
rodway-online/
├── IMAGENS/
│   ├── barco-3.jpeg
│   ├── barco-4.jpg
│   ├── barco-5.jpeg
│   ├── cabine1.jpeg
│   ├── cabine2.jpeg
│   └── cabine3.jpeg
├── index.html           # Página principal (estrutura, estilos e scripts)
├── rodwaydigital.txt    # Anotações do projeto
└── README.md
🚀 Como executar localmente
Como é um site estático, basta abrir o index.html no navegador:
bash# clone o repositório
git clone https://github.com/wervley/rodway-online.git
cd rodway-online

# abra o index.html
# Windows
start index.html
# macOS
open index.html
# Linux
xdg-open index.html
Ou, se preferir servir com um servidor local:
bash# Python 3
python -m http.server 8000

# Node (com npx serve)
npx serve .
Depois acesse http://localhost:8000 no navegador.
🌐 Deploy
O projeto está publicado via GitHub Pages:
🔗 https://wervley.github.io/rodway-online/
👤 Autor
Feito por Wervley Almeida

GitHub: @wervley

📄 Licença
Projeto acadêmico disponibilizado sob a licença MIT — livre para estudo e referência.
