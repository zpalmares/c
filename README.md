echo `#!/bin/bash` > midls
echo `ls -l --time-style=long-iso --ignore= ".*" | grep -E "^d|^-" ' >> midls
chmod +x midls
