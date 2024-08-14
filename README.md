hashs sha256sum

f882b6be104b6ab52ef2b9e16f117ea98401234d0757e26d858633e810fb78af  mullvad-mac-ram

executar:

sudo chmod +x mullvad-mac-ram;

sudo cp -r mullvad-mac-ram /bin;

mullvad-mac-ram

ou

./mullvad-mac-ram

Detalhes de como usar:


https://www.traderprofissional.com.br/gerador-de-mac-address-amnesico.html


Instale o mullvad-browser. Ele deve estar instalado em ~/Downloads/mullvad-browser.


Faça download da página mac-random.html e grave em ~/Downloads/ ----> https://github.com/leandroibov/gerador-de-enderecos-mac


Instale o firejail no Linux: sudo apt install firejail -y.


Abra essa página rodando o script mullvad-mac-ram (com firejail, bloqueando a internet e abrindo mac-random.html em failsafe), que será executado na pasta /dev/shm da memória compartilhada (failsafe) no Linux!


Sem o firejail (menos seguro), rode o script em um ambiente offline, como o Tails Linux SO, sem internet!


Digitando file:///home/ na barra de navegação, você poderá navegar até o arquivo mac-random.html onde você salvou. No entanto, o script mullvad-mac-ram copia tudo para /dev/shm para rodar tudo em failsafe!


Remova a extensão ublock em about:addons para o java script gerador de macs funcionar!



No fim da página, você terá uma lista de mac vendors para escolher, copiar e colar para gerar a lista de MACs na caixa de diálogo abaixo! Clique no botão "Gerar Endereços MAC" e use o MAC que desejar!



Os MACs spoofados e gerados não podem ser gravados em arquivos e neutralizam os ataques físicos forenses de recuperação de dados e metadados!


Você deve cadastrar esses MACs ao rodar o script tor-ram-jail1 ou tor-ram-jail2 (https://github.com/leandroibov/tor-browser-firejail-sandbox/), que aniquila os metadados de bridges e MACs das conexões com o Tor Browser no Linux, gerando mais anonimidade e segurança, (similar ao Tails Linux).


Os MACs spoofados gerados não podem ser interceptados, enviados para algum servidor e guardados por um navegador hackeado, com keylogger, etc., porque enjaulamos um novo Mullvad Browser, bloqueando toda a conexão com a internet e tudo rodando 100% na memória RAM, que não salvará nada no HD após terminar de usar o script mullvad-mac-ram



Depois de terminar, ao desligar o Mullvad Browser, tudo desaparecerá na memória RAM!
