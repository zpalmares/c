echo `#!/bin/bash` > midls
echo `ls -l --time-style=long-iso --ignore= ".*" | grep -E "^d|^-" ' >> midls
chmod +x midls
##comando midles  contem uma linha de comando para lista arquivos  e pastas, excluindo arquivovo##
