# fundamentosComputacao

## tamanho variaveis

    1 byte: bool e char
    2 bytes: short int
    4 bytes: int e float
    
## percorendo vetor com ponteiro

    int v[2] = {1,2};

    for(int i = 0; i < 2; i++){
       cout << *(v+i) << " ";
    }
