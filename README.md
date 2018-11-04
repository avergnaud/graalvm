
graalvm-demos récupéré ici : https://github.com/graalvm/graalvm-demos

# polyglot-javascript-java-r

## install
cd graalvm-demos/polyglot-javascript-java-r

sudo $GRAAL_HOME/bin/gu install R

$GRAAL_HOME/bin/gu list

## build
./build.sh

## run
$GRAAL_HOME/bin/node --jvm --polyglot server.js
