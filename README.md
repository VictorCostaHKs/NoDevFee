# Remove DevFee of Phoemix Miner 
No DevFee for Phoemix miner in Ethermine.

## Required
Windows 10

.Net Framework 4.72

## PT-BR: COMO USAR 
1 - Ative o firewall do windows.

2 - Configure sua linha de comando no arquivo "commandLine.ini"

3 - Execute NoDeveFee.exe como Administrador


O firewall do windows deve estar ativo, pois ele irá bloquear as conexões SSL.

Copie e cole sua linha de comando no arquivo "commandLine.ini", utilize um nome para seu trabalhador, pois assim você sempre vera quando uma tentativa de coleta for executada, exemplo:

-pool asia1.ethermine.org:4444 -wal 0x96306961eD9B627a24922191930e98bacc9289D2 -worker NomeDoTrabalhador -epsw x -acm -mode 1 -log 0 -mport 0 -etha 0 -ftime 55 -retrydelay 1 -coin eth

Clique com botão auxilar em NoDevFee.exe e va em "Executar como administrador"


OBS:
 conexões SSL não são suportadas pelo NoDevFee.
 
 Sempre que uma tentativa de devfee for redirecionada o contador DevFee Redirected irá subir +1.
 
 As conexões DevFee serão feitas utilizando WorkerName = Default.
 
 Donate ETH: 0x96306961eD9B627a24922191930e98bacc9289D2
 
## EN-US: HOW USE 

1 -> Activate the windows firewall.

2 -> Configure your command line in the "commandLine.ini" file

3 -> Run NoDeveFee.exe as an Administrator


The windows firewall must be active, as it will block SSL connections.

Copy and paste your command line into the file "commandLine.ini" example:
-pool asia1.ethermine.org:4444 -wal 0x96306961eD9B627a24922191930e98bacc9289D2 -worker Worker1 -epsw x -acm -mode 1 -log 0 -port 0 -etha 0 -ftime 55 -retrydelay 1 -coin eth

Click on the auxiliary button in NoDevFee.exe and go to "Run as administrator"


OBS. SSL connections are not supported by NoDevFee.


Donate ETH: 0x96306961eD9B627a24922191930e98bacc9289D2
