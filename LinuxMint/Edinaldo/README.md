Objetivo da atividade de hoje 08/11/22

Primeira etapa: iniciar Máquina Virtual no Linux Mint

Segunda Etapa: SEM NECESSIDADE DE ATUALIZAÇÃO.

Terceira Etapa: continuar o procedimentos de comandos básicos de arquivos
e diretórios, basicos comandos d rede ( coisas simples para assimilar as aulas
de Microsoft Windows )

-----------------------------------------------------------------------------
1 #Primeira etapa:
Windows 
NTFS/FAT32
Resumidamente, o NTFS é ideal para HDs internos que lidam com o Windows, enquanto o exFAT é a melhor opção para pen drives e HDs externos. O FAT32 é útil para lidar com dispositivos que não suportam os outros sistemas de arquivos

GNU/Linux
EXT4
O ext4 é a evolução do conhecido ext3, hoje o file-system padrão do GNU/Linux. O Linux oferece suporte a uma infinidade de file-systens e em uma instalação normal do sistema, os file-systens mais famosos são o reiserfs e o ext3.

Particionamento

2# Segunda etapa
Redes (TCP/IPv4)

Comando Windows    comando GNU/LINUX
ipconfing          ifconfig
ipconfing /all     

gateway            route -n (UG) (tradução gateway)
DNS                resolvectl 

COMANDO PARA TESTA A REDE
nslookup (igual no Windows e GNU/Linux)
ping ( testa conexão com a rede )

ping google.com no linux
ping google.com -t

3# Terceira Etapa:
windows        GNU/LINUX
               pwd (diretório corrente)
dir ls		   ls -lh
cd             cd 
criar diretório
md              mkdir
criar arquivo
                touch README .md

