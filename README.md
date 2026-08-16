#  Minha Micro Nuvem (LG K9 Labs)

Micro nuvem pessoal e laboratório de estudos de infraestrutura e cibersegurança, hospedados de forma autônoma em um dispositivo móvel antigo (LG K9) rodando Android e Termux.

##  Sobre o Projeto
O objetivo deste projeto é transformar um hardware reaproveitado em um servidor web leve e portátil. Através de um ambiente Linux emulado via Termux (`python3 -m http.server`) combinado com túneis públicos (`Serveo`), a nuvem fica acessível externamente de forma rápida e segura para testes, armazenamento de arquivos estáticos e centralização de anotações de estudo.

##  Tecnologias Utilizadas
* **Hardware:** LG K9 (Dispositivo Android dedicado).
* **Ambiente:** Termux (Emulador de terminal Linux).
* **Servidor HTTP:** Python 3 (`http.server`).
* **Tunelamento:** SSH (`Serveo.net`) para exposição pública temporária.
* **Front-end do Painel:** HTML5 / CSS3 (Design moderno inspirado em gerenciadores em nuvem).

##  Estrutura do Repositório
```text
minha-nuvem/
├── index.html          # Painel principal (estilo Google Drive/iCloud)
├── labs/               # Seção dedicada a anotações e testes de segurança
│   └── index.html      # Página interna de laboratório
└── README.md           # Documentação do projeto
