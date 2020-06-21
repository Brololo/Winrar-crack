# Sujet 2 : Débugger et désassembler des programmes compilés

## Hello World !

J'ai fait le programme qui affiche hello world :

```cpp
#include <lostream>
int main() {
    std::cout << "Hello World!";
    return 0;
}
```

J'ai ensuite désassembler le programme avec ghidra.
J'ai rechercher une chaîne de caractères qui contenait "Hello World!".
ghidra m'a affiché la chaîne de caractère et me précise qu'elle est stockée dans "ds".

## Crack Winrar

Pour crack winrar je l'ai désassembler avec ghidra puis j'ai rechercherla chaine de caractères "evaluation" j'ai cherché quel fonction appelait la chaîne de caractères et j'ai modifié la condition en changeant "JNZ" par "JZ" ce qui inversait la condition et n'appelait plus la chaîne de caractères, j'ai compilé une nouvelle fois winrar et je n'étais plus en version d'évaluation.
