# Dongle RTL

## O que é SDR?

A sigla significa “Software Defined Radio”, ou seja, softwares substituem funções que normalmente seriam hardware num rádio. A adaptabilidade e consequente praticidade desse sistema faz com que a popularidade do SDR cresça e eventualmente torne obsoleto o uso de rádios analógicos.

Diversas aplicações militares, médicas e civis dependem de radiocomunicação. A facilidade de acesso à diversas bandas e o possibilidade de processamento de variados sinais sem a necessidade de equipamento diverso, custoso e de difícil transporte demonstra a primazia do SDR. A liberdade para o usuário de criar seus próprios protocolos e projetar o software desejado trazem ainda mais vantagens.

As implementações usadas atualmente são em FPGA, DSP ou processadores de uso geral, como em computadores comuns, esta última sendo a mais acessível para amadores. Nela, uma antena, equipamento de amplificação RF, um sintonizador e conversores ADC configuram a aparelhagem externa básica para a recepção. Isto tudo podendo ser compactado em antena, cabos e um dongle. O resto do trabalho se dará digitalmente.

## Quais os SDR acessíveis ao público?

Os dongles RTL-SDR recebem esse nome pelo uso do microchip RTL2832U da Realtek, originalmente usado para DVB (Transmissão de Vídeo Digital). A maior parte deles utiliza os sintonizadores R820T ou R820T2 da Rafael Micro, que estão para ser descontinuados, ou o E4000 da Elonics. É interessante pesquisar qual sintonizador é usado no modelo que se pretende adquirir, já que influencia na qualidade do sinal passado.

Outra peça a ser considerada é o TCXO (Temperature Compensated Crystal Oscillator) ou outra compensação de variação de frequência de acordo com a mudança de temperatura. A falta de correção, nesse caso, faz com que o dispositivo esteja “conectado” a uma certa frequência diferente da indicada, e requer uma correção do usuário.

Evidentemente, cada aparelho cobrirá certa extensão de frequências. Essa parte da escolha é relativamente pessoal, mas é claro que a maioria dos usuários desejará ter acesso a maior quantidade de opções possível. A diferença costuma aparecer nas ondas curtas/HF (ainda assim, é possível sintonizar SW com modificações de hardware na maioria dos produtos que não indicam alcançá-las em suas faixas de frequência).

Não tão importante, mas interessante de se observar, é o conector com a antena. Certos RTL-SDR fazem a conexão usando SMA, outros MCX, etc. E por esse meio também pode ser possível passar corrente DC no cabo coaxial para outros aparelho conectados entre a antena e o SDR, desde que o dongle suporte Bias-Tee. Essa funcionalidade permite o uso direto de amplificadores, por exemplo.