
##############################################################################

[MULLVAD MAC RAM PARA ABRIR OFF LINE O GERADOR DE MACS mac-random.html]


Precisa fazer download da página mac-random.html e grave em ~/Downloads/ ----> https://github.com/leandroibov/gerador-de-enderecos-mac

##############################################################################

executar:

sudo chmod +x mullvad-mac-ram;

sudo cp -r mullvad-mac-ram /bin;

mullvad-mac-ram

ou

na pasta que o script está localizado,


./mullvad-mac-ram



###################################################################################################


MULLVAD RAM JAIL1 - PARA USAR O MULLVAD ONLINE MAS EM FIREJAIL, COM MAC SPOOFING E FAILSAFE NA RAM


Não permite ouvir música ou vídeo. Microfone restrito! '--nosound --novideo'


MULLVAD RAM JAIL2 - PARA USAR O MULLVAD ONLINE MAS EM FIREJAIL, COM MAC SPOOFING E FAILSAFE NA RAM


Permite ver vídeos e ouvir. --novideo.


MULLVAD RAM JAIL3 - PARA USAR O MULLVAD ONLINE MAS EM FIREJAIL E FAILSAFE NA RAM (sem cadastrar mac)


Não permite ouvir música ou vídeo. Microfone restrito! '--nosound --novideo'


MULLVAD RAM JAIL4 - PARA USAR O MULLVAD ONLINE MAS EM FIREJAIL E FAILSAFE NA RAM (sem cadastrar mac)


Permite ver vídeos e ouvir.


MULLVAD RAM - Abre o mullvad sem firejail 100% na shared memory e apaga assim que finaliza uma sessão!

Arquivo original fica intacto na pasta ~/Downloads


###################################################################################################


executar:


sudo chmod +x mullvad-ram-jail1;


sudo chmod +x mullvad-ram-jail2;


sudo chmod +x mullvad-ram-jail3;


sudo chmod +x mullvad-ram-jail4;


sudo chmod +x mullvad-ram;


sudo cp -r mullvad-ram-jail1 /bin;


sudo cp -r mullvad-ram-jail2 /bin;


sudo cp -r mullvad-ram-jail1 /bin;


sudo cp -r mullvad-ram-jail2 /bin;


sudo cp -r mullvad-ram-jail3 /bin;


sudo cp -r mullvad-ram-jail4 /bin;


sudo cp -r mullvad-ram /bin;


mullvad-ram-jail1


mullvad-ram-jail2


mullvad-ram-jail3


mullvad-ram-jail4


mullvad-ram


ou


na pasta que o script está localizado,


./mullvad-ram-jail1


./mullvad-ram-jail2


./mullvad-ram-jail3


./mullvad-ram-jail4


./mullvad-ram


#################################################################################


Detalhes de como usar o mullvad-mac-ram e mac-random.html:


#################################################################################


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



##################################################################################################

Doe monero para nos ajudar: 87JGuuwXzoMGwQAcSD7cvS7D7iacPpN2f5bVqETbUvCgdEmrPZa12gh5DSiKKRgdU7c5n5x1UvZLj8PQ7AAJSso5CQxgjak

Aprenda conosco pelos cursos gravados online e grupo de sinais:

https://traderprofissional.com.br/comprar_nossos_cursos.aspx 

Página oficial de segurança digital:

https://traderprofissional.com.br/seguranca-digital.aspx


##################################################################################################


Doe monero para nos ajudar: 

87JGuuwXzoMGwQAcSD7cvS7D7iacPpN2f5bVqETbUvCgdEmrPZa12gh5DSiKKRgdU7c5n5x1UvZLj8PQ7AAJSso5CQxgjak


Página oficial de segurança digital:


https://traderprofissional.com.br/seguranca-digital.aspx


Vídeo tutorial youtube: 


https://www.youtube.com/watch?v=qqgaVaswzXc







