# Onde Estacionei?

Projeto desenvolvido para a disciplina de **Desenvolvimento de Software para Web 2**, ministrada no Departamento de Computação (DC) da Universidade Federal de São Carlos (UFSCar).

A aplicação "Onde Estacionei?" foi criada para solucionar um problema comum: a dificuldade de motoristas em localizar seus veículos em grandes estacionamentos ou áreas desconhecidas. Com um simples toque, o usuário salva a localização do seu carro e pode consultá-la posteriormente em um mapa interativo para retornar ao veículo sem dificuldades.

## 🚀 Funcionalidades

* **📍 Registro de Localização com Um Clique:** Permite que o usuário capture e armazene suas coordenadas geográficas atuais de forma rápida através de um botão de destaque na interface principal.
* **🗺️ Visualização em Mapa Interativo:** Exibe a localização salva em um mapa, mostrando a posição atual do usuário para guiar o caminho de volta ao veículo.
* **📜 Histórico de Estacionamentos:** Uma tela secundária lista os últimos locais de estacionamento registrados, permitindo que o usuário consulte seus registros anteriores.

## 🛠️ Tecnologias Utilizadas

* **Frontend:** React, HTML5, CSS3
* **APIs do Navegador:**
    * **Geolocation API:** Para obter as coordenadas precisas do usuário.
    * **Web Storage API (localStorage):** Para persistir os dados de localização (atual e histórico) no dispositivo.
* **Serviços Externos:**
    * **OpenStreetMap:** API utilizada para carregar os mapas na interface.

## ✅ Atendimento aos Requisitos da Disciplina

O projeto foi cuidadosamente planejado e desenvolvido para atender integralmente aos 6 requisitos (R1-R6) propostos pela disciplina.

| Requisito | Descrição                    | Como foi Atendido no Projeto                                                                                                                                                                                          |
| :---     | :---                         | :---                                                                                                                                                                                                                  |
| **R1** | **Identidade Visual e Layout** | Foi desenvolvida uma identidade visual e um layout minimalista e intuitivo. A paleta de cores e a iconografia foram escolhidas para remeter a aplicativos de navegação, conferindo uma aparência de aplicativo real. |
| **R2** | **Múltiplas Telas/Páginas** | O aplicativo conta com duas telas principais: a **Tela Principal** (para registro e visualização no mapa) e a **Tela de Histórico**.                                                                                 |
| **R3** | **Layout Responsivo** | A aplicação foi projetada com um layout responsivo, garantindo a adequada visualização e funcionalidade em dispositivos móveis, tablets e desktops.| **R4** | **Duas Telas Funcionais** | Ambas as telas são funcionais: a **Tela Principal** implementa a lógica de captura e exibição da localização, e a **Tela de Histórico** consulta e exibe os dados salvos no Web Storage.                            |
| **R5** | **Acesso à Rede** | O acesso à rede é feito para carregar os mapas do serviço externo OpenStreetMap.                                                                                                                                      |
| **R6** | **Uso de API Adicional** | O projeto utiliza duas APIs adicionais: a **API de Geolocalização**, para obter as coordenadas do usuário, e a **API de Web Storage**, para persistir os dados localmente no navegador.                               |

## 🧑‍💻 Autores

* Gustavo Kim Alcantara
* Gustavo Borguetti Daré
* Murilo Eduardo Feijó Ramos
