# Mais

em construção.

## WebSDR da Univesidade de Twente

WebSDR mantida pela universidade de Twente localizada na Holanda. Como outros WebSDR disponíveis on-line, é uma boa porta de entrada pra entender melhor as funcionalidades e opções disponíveis na mundo dos SDR: 

[http://websdr.ewi.utwente.nl:8901/](http://websdr.ewi.utwente.nl:8901/)

## Voice of Korea

Rádio SW estatal norte-coreana “Voice of Korea”, com transmissões em diferentes línguas e uma programação de notícias e música. Os horários estão em UTC. Deve-se observar a área-alvo das transmissões para procurar WebSDR dentro de seu perímetro:

[https://en.wikipedia.org/wiki/Voice_of_Korea](https://en.wikipedia.org/wiki/Voice_of_Korea)

## GNU Radio

O GNU Radio é uma plataforma em C++ de desenvolvimento de software para SDR gratuita e open-source, usada para processamento de sinais digitais. Por meio de um esquema de blocos montado pelo usuário, um código em Python é gerado e permite-se conectar um hardware externo ou fazer simulações no seu próprio ambiente.

[https://www.gnuradio.org/](https://www.gnuradio.org/)

## Signal Id Wiki

No site abaixo é possível identificar os mais diversos tipos de sinais e navegar entre diversas opções ligadas ao mundo da comunicação.

[https://www.sigidwiki.com/wiki/Signal_Identification_Guide](https://www.sigidwiki.com/wiki/Signal_Identification_Guide)

## In the Sky

In The Sky atualiza 24h o posicionamento de satélites orbitando a Terra. Com essa ferramenta fica fácil saber aonde o sinal do satélite desejado pode ser recebido. É possível também descobrir quais deles estarão passando no céu numa hora e local determinados.

[https://in-the-sky.org/index.php](https://in-the-sky.org/index.php)

## Lista de WebSDRs usando KiwiSDR

[http://rx.linkfanel.net/](http://rx.linkfanel.net/)

## Priyom

Site de monitoramento e log de estações militares, principalmente "*number stations*".

[https://priyom.org/](https://priyom.org/)

## Classificação de transmissões ITU por sigla

[https://en.wikipedia.org/wiki/Types_of_radio_emissions](https://en.wikipedia.org/wiki/Types_of_radio_emissions)

# Recepção de sinais por satélite

Com certeza um dos projetos mais legais para se trabalhar ao adquirir um RTL-SDR é a recepção de sinais de satélites orbitando a Terra. Ainda assim, não é fácil, já que demanda-se conhecimento do posicionamento do mesmo e de como seu sinal é enviado e codificado. A recepção também pode ser muito ruim sem uma antena ideal bem posicionada e tratamento adequado contra interferências. 

Atualmente, os satélites NOAA-15,18 e 19 (Nasa/NOAA) transmitem imagens de análise climática por APT (Automatic Picture Transmission em AM) e outras informações adicionais em DST (Direct Sound Transmission em PSK), tudo está bem documentado online. Outra opção popular é captar dados e imagens da Estação Espacial Internacional (ISS). Para imagens, é utilizado o modo SSTV (Slow-Scan Television em FM) na forma PD-120 (intervalos de 2 minutos entre fotos) na frequência 145,800 MHz.

Muitos outros satélites estão constantemente mandando sinais para a Terra, todos estes podendo ser captados com conhecimento prévio de seus tipos de transmissão. Felizmente, não é difícil achar informações online, sem falar que existem centenas de softwares feitos por amadores para decodificar essas mensagens com alguns cliques.