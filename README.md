# WA-ME
Boas vindas a WellsFromANPMadeEasy 👋

A "documentação" deste código pode ser encontrada em: https://drive.google.com/drive/folders/1Ic-FxjAcCJ2eJCWjnlaeNc2JZWwRHUq2?usp=sharing

O objetivo deste projeto é facilitar o acesso a dados de poços disponibilizados pela ANP (Agência Nacional do Petróleo, Gás Natural e Biocombustíveis - Brasil) para usuários do software de interpretação sísmica PaleoScan. O código percorre uma pasta maior (que deve ser criada pelo usuário) com subpastas e arquivos de dados geológicos (estes teoricamente já são fornecidos no “padrão correto” pela ANP). Ele faz isso a fim de procurar arquivos específicos de cada tipo (las, dlis, lis, sgy, txt), bem como informações sobre coordenadas UTM Norte e Leste de fundo de poço, dados direcionais (MD, inclinação, TVD e azimute) e litologia interpretada, lito e cronoestratigrafia* quando disponíveis, em cada subpasta e coletando informações estruturadas desses arquivos. Ao final, um arquivo xlsx é gerado, contendo uma página InfoAllWells com uma tabela de yes/no relativa a cada poço e suas informações disponíveis. Nesse arquivo, também podem haver outras páginas, com tabelas com dados específicos para cada poço (direcionais, litoestratigráficos e cronoestratigráficos), caso disponíveis. Esses dados também são salvos como arquivos txt separados. Por fim, o código exibe uma mensagem com o caminho do arquivo Excel gerado e os arquivos txt. Isso cria um resumo completo e organizado dos dados dos poços selecionados, separados em abas no Excel e arquivos de texto individuais para cada tipo de dado.

ATENÇÃO: Como os dados da ANP nem sempre seguem o mesmo padrão, pode ser que essas informações não sejam de todo corretas. Sendo assim, é recomendável checar alguns padrões para chegar a suas próprias conclusões. Um exemplo concreto disso é o pensamento: "se meu poço tem informações complexas  trabalhosas e adquirir, como litologia interpretada, com certeza ele tem coordenadas UTM, que são bem mais básicos e podem estar só em PDF, e, provavelmente, tem dados de lito e/ou cronoestratigrafia, que costumam estar ligados". Ademais, se o seu trabalho for extremamente detalhado e depender da maior quantidade de poços com informações específicas disponíveis, é recomendável abrir os arquivos disponibilizados pela ANP um a um e checar manualmente todas as informações.

🏠 Homepage: https://github.com/dudafrancklim/geolog-python-ufrj

👤 Author: Maria Eduarda Francklim - Github: https://github.com/dudafrancklim; LinkedIn: https://linkedin.com/in/mefrancklim

🤝 Agradecimentos: 
Gostaria de agradecer a todos que ajudaram diretamente na confecção desse código: Fellippe Bione, Diana Moreira, Davi Melonio, Francisco Tognoli, João Victor Sampaio, um desconhecido usuário do StackOverflow que me ajudou com o pontapé inicial do código e por último, mas nem um pouco menos importante, meu bestie de programação ChatGPT, que revisou muito código sem nexo e me passou muito (muito mesmo) código errado pra revisar. O que eu pensava ser algo trivial de executar provou ser bem trabalhoso, mas vocês fizeram algumas etapas serem menos difíceis 🩵

🫰 Contribuições, avisos sobre problemas e outros comentários são sempre bem vindos! 


This README was generated with ❤️ by readme-md-generator (https://github.com/kefranabg/readme-md-generator)
