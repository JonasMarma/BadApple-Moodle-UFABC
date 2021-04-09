# BadApple-Moodle-UFABC
Mostra o clipe "Bad Apple!!" no Moodle da UFABC (também serve para qualquer outro site)

Este repositório foi utilizado para fazer o Moodle da UFABC (na verdade funciona para qualquer site) exibir o clipe "Bad Apple!!".

O repositório está dividido em duas pastas principais:

"BadAppleUFABC" se refere à extensão do Google Chrome criada para fazer as atualizações no html da página. Os frames do vídeo são inseridos agendando alterações no campo "innerhtml" de um parágrafo com id="badapple".

"video-badapple" contém o código em Python utilizado para transformar os frames do vídeo no código em javascript utilizado acima.

OBSERVAÇÃO: O arquivo content.js, que deveria estar no diretório BadAppleUFABC é muito grande e não foi possível fazer seu upload. Este arquivo contém todos os frames já convertidos em html e é gerado pelo conversor.ipynb. Para que o projeto funcione é necessário rodar o conversor.ipynb, copiar o content.js gerado e colá-lo no diretório BadAppleUFABC.

Veja o vídeo:

https://youtu.be/qM9Q4Kg21HM
