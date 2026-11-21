# Facecams Redondas — Estilo GTA 6 | Estáticas e Animadas

Coleção gratuita de **5 modelos de facecam redonda** em duas versões — **PNG estático** e **WEBM animado** — para personalizar sua webcam em transmissões e gravações no **OBS Studio** e em outros softwares compatíveis.

A estética reúne neon rosa, roxo, azul, pôr do sol, palmeiras, cidade litorânea, carros e elementos de ação, com visual **inspirado no clima de GTA 6**. As artes são projetos independentes do **Guia do Streamer** e **não são produtos oficiais de Grand Theft Auto VI, Rockstar Games ou Take-Two Interactive**.

> **AVISO DE DIREITOS AUTORAIS E LICENÇA**  
> Este repositório é público para facilitar o download, mas seus arquivos **não estão em domínio público** e **não possuem licença para redistribuição**. O uso das facecams é gratuito somente nas condições descritas neste README e no arquivo [`LICENSE.txt`](LICENSE.txt). **Não é uma licença MIT.**

## Prévia dos modelos

| Modelo | Prévia estática | Arquivos para download |
|:---:|:---:|:---|
| **01 — Luxo neon** | <img src="estaticas/facecam%20redonda%20estatica%201%281%29.png" alt="Facecam redonda 1 — luxo neon" width="170"> | [PNG](estaticas/facecam%20redonda%20estatica%201%281%29.png) · [WEBM](animadas/facecam%20animada%201.webm) |
| **02 — Perseguição policial** | <img src="estaticas/facecam%20redonda%20estatica%202%281%29.png" alt="Facecam redonda 2 — perseguição policial" width="170"> | [PNG](estaticas/facecam%20redonda%20estatica%202%281%29.png) · [WEBM](animadas/facecam%20animada%202.webm) |
| **03 — Noite tropical** | <img src="estaticas/facecam%20redonda%20estatica%203%281%29.png" alt="Facecam redonda 3 — noite tropical" width="170"> | [PNG](estaticas/facecam%20redonda%20estatica%203%281%29.png) · [WEBM](animadas/facecam%20animada%203.webm) |
| **04 — Praia e moto** | <img src="estaticas/facecam%20redonda%20estatica%204%281%29.png" alt="Facecam redonda 4 — praia e moto" width="170"> | [PNG](estaticas/facecam%20redonda%20estatica%204%281%29.png) · [WEBM](animadas/facecam%20animada%204.webm) |
| **05 — Cidade neon** | <img src="estaticas/facecam%20redonda%20estatica%205%281%29.png" alt="Facecam redonda 5 — cidade neon" width="170"> | [PNG](estaticas/facecam%20redonda%20estatica%205%281%29.png) · [WEBM](animadas/facecam%20animada%205.webm) |

## Recursos

- **5 artes diferentes**, com versões estáticas e animadas (10 arquivos no total).
- **PNG** com transparência, para facecam fixa.
- **WEBM** com codec VP9 e canal alfa, para usar como fonte de mídia em repetição (loop).
- **Centro transparente** para colocar a webcam recortada em formato circular.
- Paleta com neon magenta, roxo, azul e tons alaranjados.
- Arquivos de mídia prontos para uso; não exigem plugins ou scripts.
- Os arquivos possuem **dimensões originais diferentes** e podem ser redimensionados no software de transmissão.

> As animações contidas nos arquivos WEBM são efeitos visuais em loop. O resultado, transparência e desempenho dependem da implementação do codec no software e do hardware utilizado.

## Como usar no OBS Studio

### 1. Adicione e ajuste a webcam

1. No OBS Studio, adicione sua câmera como **Dispositivo de captura de vídeo**.
2. Clique com o botão direito na câmera e escolha **Filtros**.
3. Em **Filtros de efeito**, adicione **Máscara/Mistura de imagem** (Image Mask/Blend).
4. Escolha o tipo **Máscara alfa (canal de cor)** (*Alpha Mask (Color Channel)*) e selecione uma **imagem de máscara circular própria**: branco no círculo da webcam, preto na parte externa.
5. Ajuste tamanho e posição da webcam para ela ficar centralizada dentro do aro da facecam.

**Importante:** os arquivos deste pacote são **overlays**, não máscaras de recorte. A máscara circular deve ser criada/obtida separadamente; ela não faz parte dos 10 anexos deste pacote.

Tutorial Guia do Streamer para recortar webcam redonda: [https://youtu.be/ZETAlPXif2k](https://youtu.be/ZETAlPXif2k)

### 2. Use uma facecam estática (PNG)

1. Em **Fontes**, clique no botão **+** e escolha **Imagem**.
2. Selecione um dos arquivos da pasta `estaticas/`.
3. Posicione a imagem **acima da webcam** na lista de Fontes.
4. Redimensione até encaixar o contorno redondo ao redor da imagem da câmera.

### 3. Use uma facecam animada (WEBM)

1. Em **Fontes**, clique em **+** e escolha **Fonte de mídia**.
2. Marque **Arquivo local** e selecione um arquivo `.webm` da pasta `animadas/`.
3. Habilite **Repetir** (loop).
4. Mantenha essa Fonte de mídia **acima da webcam** na lista de Fontes.
5. Ajuste as dimensões e confira o centro transparente na prévia.

**Dica:** use uma única versão do modelo por vez — PNG **ou** WEBM — para evitar sobreposição desnecessária. Se a mídia não ficar transparente no seu ambiente, confira o suporte à transparência VP9 da versão do OBS ou do software utilizado.

## Estrutura do repositório

```text
facecams-redondas-estilo-gta6/
├── README.md
├── LICENSE.txt
├── CHANGELOG.md
├── .gitignore
├── estaticas/
│   ├── facecam redonda estatica 1(1).png
│   ├── facecam redonda estatica 2(1).png
│   ├── facecam redonda estatica 3(1).png
│   ├── facecam redonda estatica 4(1).png
│   └── facecam redonda estatica 5(1).png
└── animadas/
    ├── facecam animada 1.webm
    ├── facecam animada 2.webm
    ├── facecam animada 3.webm
    ├── facecam animada 4.webm
    └── facecam animada 5.webm
```

> **Nomes preservados:** os nomes de mídia acima são exatamente os enviados pelo autor, incluindo espaços e o sufixo `(1)` dos PNGs. Eles não foram renomeados nem recomprimidos.

## Como baixar

- Para obter **toda a coleção**, clique em **Code > Download ZIP** no repositório oficial.
- Para baixar um único modelo, abra os links da tabela de prévia acima e utilize **Download raw file** no GitHub.

## Licença de uso

Copyright © 2026 Leonardo — Guia do Streamer. Todos os direitos reservados.

### Você pode

- Utilizar gratuitamente as facecams em suas próprias lives, gravações e vídeos, inclusive monetizados.
- Ajustar tamanho, posicionamento, cor e efeitos para **uso próprio**.
- Editar os arquivos para melhorar o encaixe com sua webcam, sem republicar os arquivos resultantes.
- Exibir as facecams em capturas de tela, tutoriais e materiais que mostrem sua própria transmissão, mantendo a atribuição correta quando mencionar a origem do pacote.

### Você não pode

- Redistribuir, republicar, fazer reupload ou oferecer cópias dos arquivos originais ou modificados.
- Criar repositórios espelho, links alternativos de download, pacotes, coleções ou templates contendo as facecams.
- Vender, sublicenciar, alugar ou incluir os arquivos em produtos ou pacotes pagos ou gratuitos para terceiros.
- Apresentar as artes como criação própria, remover avisos de autoria ou sugerir que há uma parceria oficial com o Guia do Streamer.

**Para compartilhar corretamente**, envie apenas o link do repositório oficial:  
`https://github.com/guiadostreamer/facecams-redondas-estilo-gta6`

Consulte os termos integrais em [`LICENSE.txt`](LICENSE.txt). Qualquer uso não previsto necessita de autorização prévia e escrita do responsável.

## Autoria e identificação

- **Projeto:** Facecams Redondas — Estilo GTA 6 | Estáticas e Animadas
- **Coleção inicial:** 1.0.0
- **Identificador:** `GDS-FACECAM-REDONDA-NEON-2026-01`
- **Direção criativa, conceito, personalização e publicação:** Leonardo — Guia do Streamer
- **Criação dos recursos visuais:** com auxílio de ferramentas de Inteligência Artificial
- **Repositório oficial (previsto):** [guiadostreamer/facecams-redondas-estilo-gta6](https://github.com/guiadostreamer/facecams-redondas-estilo-gta6)

## Direitos de terceiros e independência

A referência a **Grand Theft Auto VI (GTA 6)** descreve somente a **inspiração estética**, sem alegação de vínculo, autorização, patrocínio ou aprovação. **GTA, Grand Theft Auto, Rockstar Games e Take-Two Interactive** são nomes e marcas de seus respectivos titulares. Elementos de terceiros, quando existentes, continuam sujeitos aos direitos de seus proprietários; esta licença **não concede direitos sobre marcas ou obras de terceiros**.

O mesmo vale para **OBS Studio** e seus respectivos titulares. Compatibilidade de uso não implica endosso.

## Aviso de funcionamento

Arquivos disponibilizados **no estado em que se encontram**, sem garantia de compatibilidade com todas as versões dos programas de transmissão ou configurações de computador. O desempenho e a transparência do WEBM podem variar conforme o software e o decoder utilizado.

## Créditos

Criado para a comunidade do **[Guia do Streamer](https://github.com/guiadostreamer)**.

Se o pacote ajudou sua live, compartilhe **somente o link oficial** do repositório e preserve os créditos.
