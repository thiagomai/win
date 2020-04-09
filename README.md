# win

 WD DATA LIFEGUARD

chkdsk /r
sfc /scannow

MODO DE PROMPT 
BCDEDIT
VERIFICAR
systemroot [partição]
sfc /scannow /offbootdir=X:\ /offwindir=X:\windows - Trocar X por partição verificada
dism /online /cleanup-image /restorehealth

PASSO 3: LIMPESA DE DISCO

DESFRAG
menu iniciar, limpeza de disco;
limpar arquivos do sistema;
mais opçoes, limpar;
marcar caixas nescessarias, CERIFICAR PASTA DOWNLOAD;

CCLEANER

BLOQUEIO DE SITES
bloco de notas(como adm) 
editar arquivo C:\Windows\System32\drivers\etc\host - adicionar o domínio dele (com www e sem www)-
#IPv4
127.0.0.1   www.baixaki.com.br
127.0.0.1   baixaki.com.br
127.0.0.1   superdownloads.com.br
127.0.0.1   www.superdownloads.com.br
127.0.0.1   superd.com.br
127.0.0.1   www.superd.com.br
127.0.0.1   ultradownloads.com.br
127.0.0.1   www.ultradownloads.com.br
127.0.0.1   download.com
127.0.0.1   www.download.com
127.0.0.1   softpedia.com
127.0.0.1   www.softpedia.com
127.0.0.1   softonic.com
127.0.0.1   www.softonic.com

# IPv6
fe80::1%lo0   www.baixaki.com.br
fe80::1%lo0   baixaki.com.br
fe80::1%lo0   superdownloads.com.br
fe80::1%lo0   www.superdownloads.com.br
fe80::1%lo0   superd.com.br
fe80::1%lo0   www.superd.com.br
fe80::1%lo0   ultradownloads.com.br
fe80::1%lo0   www.ultradownloads.com.br
fe80::1%lo0   download.com
fe80::1%lo0   www.download.com
fe80::1%lo0   softpedia.com
fe80::1%lo0   www.softpedia.com
fe80::1%lo0   softonic.com
fe80::1%lo0   www.softonic.com

TESTE DE MEMORIA
mdsched.exe

DEFRAGGLER - 
CONFIGURAÇÕES, MAPA DO DESPOSITIVO - VISAO CUSTOMIZADA - ESTILO(PLANO) - MODO (BARRAS)
CONFIGURAÇÕES, OPÇOES, DESFRAGMENTAR - MOVER ARQUIVOS GRANDES PARA O FINAL DO VOLUME(1000)

