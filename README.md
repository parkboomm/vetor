int main()
{
    #define tam_max 5
    int Vet1[tam_max];
    int Maior;
    int i;
    int contador = 0;
    
    
    for (i=0; i<tam_max; i++)
        scanf("%d", &Vet1[i]);
        
        
    for(i=0; i<tam_max; i++)
        if(Vet1[i] > 100)
           contador++;
    printf("Os elemento maiores que 100: %d\n", contador);
    
    
    return 0;
}
