### automatons-and-languages-project
A final project for automatons and languages subject

# COMPILAR ANALIZADOR LÉXICO
* java Main scanner *

# COMPILAR PARSER
* java java_cup.Main parser *

# ARREGLAR EXCEPCIÓN EN parser.java de NUMBER FORMAT [cambiando el (Integer) por Integer.parseInt()]
* javac parser.java *

# UNIR EL SCANNER Y EL PARSER
* javac -d . parser.java sym.java scanner.java *

# EJECUTAR PARSER CON ARCHIVO
* java parser 0<archivo.txt *
