### Interpreter impl.

Just having fun with `Crafting-Interpreters` book

see: https://craftinginterpreters.com


### Running

* Interactive interpreter: `mvn exec:java`
* Running a file: `mvn exec:java -Dexec.args=<path to file>`
* Running AST classes generator: `mvn exec:java@generate_ast -Dexec.args=<destination>`
    
    E.g. `mvn exec:java@generate_ast -Dexec.args="$(pwd)/src/main/java/com/davfigue/lox/"`
