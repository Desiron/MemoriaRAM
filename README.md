# MemoriaRAM
Atividade 02 - Memória RAM, Memória ROM, Mémória SWAP e Paginação de Memória


Memória RAM

A memória RAM (Random Access Memory - Memória de Acesso Aleatório) é um hardware de armazenamento randômico e volátil de memória. Isto significa que esta peça armazena dados de programas em execução enquanto o computador está ligado. 
A memória RAM é de acesso rápido, ou seja, é essencial para acompanhar a velocidade do processador. Este tipo de memória recebe as 
informações do HD, e as armazena temporariamente, disponibilizando este conteúdo ao processador.

Memória ROM

O termo memória ROM se refere a uma memória de armazenamento que permite apenas a leitura da informação e não de sua destruição, independente da presença ou não de uma fonte de energia que a alimente. 
Elas não estão mais presentes em armazenamentos de BIOS, que tem como função preparar a máquina como um todo para entrega-la ao sistema operacional. Nessa memória está presente todas os primeiros comandos que devem ser executados, desde checagem de hardware a apontamento de leitura de arquivos no HD.

Memória Swap

O swap é a memória virtual (também é conhecido como área de troca). A memória virtual funciona como uma extensão da memória RAM, que fica armazenada no disco. O porquê da memória swap precisar existir é simples: o sistema operacional precisa de memória para funcionar, e se a memória acabar, o sistema falha. O swap fica como uma reserva emergencial caso a memória RAM acabe. A memória swap era bastante útil em tempos passados onde memória RAM era algo mais escasso. 

Paginação de Memória

A técnica de paginação surgiu com a necessidade de evitar o desperdício de memória causada pelas partições variáveis em função da fragmentação externa. A fragmentação externa consiste no fato de cada programa necessitar ocupar uma área continua na memória, se essa necessidade for eliminada e partes do programa puderem ser espalhadas pela memória, o problema da fragmentação externa estaria acabado é aí que entra a paginação. A paginação nada mais é que o programa poder ser espalhado por áreas não continuas da memória.

A paginação ocorre quando o programa é executado, o mesmo é escrito com a suposição de que ele vai ocupar uma área continua na memória, ou seja, que ocupará a memória lógica. O endereço da memória lógica é dividido em duas partes o número da página lógica e o deslocamento dentro da memória lógica.


Exemplo de memória física/lógica
Num. Des. Mem
000 | 00 | A1
000 | 01 | A2
000 | 10 | A3
000 | 11 | A4

O a primeira coluna (Num.), é o número da página lógica, a segunda coluna (Des.) é o deslocamento dentro da tabela, ao ser criada a pagina lógica é também criada a página física com o mesmo formato da página lógica só diferem que a memória física não necessita que suas páginas estejam na mesma ordem que as páginas na memória lógica, mas precisa que o deslocamento dentro das páginas seja o mesmo tanto na memória física quanto na lógica, por tanto a página da memória física será carrega com o mesmo formato da memória lógica, tendo diferente apenas seus endereço de página, durante essa carga é criada a tabela de páginas. Essa tabela é usada para saber qual página da memória lógica corresponde à página da memória física.



FONTES:
http://www.infoescola.com/informatica/memoria-ram/
http://queconceito.com.br/memoria-rom
http://sotekno.blogspot.com.br/2009/11/paginacao-de-memoria.html


