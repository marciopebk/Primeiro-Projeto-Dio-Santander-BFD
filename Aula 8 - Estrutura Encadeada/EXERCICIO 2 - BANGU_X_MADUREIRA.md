## Bangu X Madureira

Algoritmo "BANGU_X_MADUREIRA"

Var
   DIF, GB, GM: REAL
   RESULTADO: CARACTERE

Inicio
      ESCREVAL("**********************************")
      ESCREVAL(" PARTIDA ENTRE BANGU X MADUREIRA")
      ESCREVAL("**********************************")
      ESCREVA("QUANTOS GOL(S) O BANGU MARCOU? ")
      LEIA(GB)
      ESCREVA("QUANTOS GOL(S) O MADUREIRA MARCOU? ")
      LEIA(GM)
      DIF <- ABS(GB-GM)
      
      ESCOLHA (RESULTADO)
      
              CASO 0
                   RESULTADO <- ("PARTIDA EMPATADA")
              CASO 1, 2, 3
                   RESULTADO <- ("PARTIDA NORMAL")
              OUTROCASO
                   RESULTADO <- ("GOLEADA")
                   
      FIMESCOLHA
      
      ESCREVAL("**********************************")
      ESCREVAL("   UMA DIFERENÇA DE GOLS DE: ", DIF)
      ESCREVAL("**********************************")
      ESCREVAL("      TIVEMOS UMA PARTIDA ", RESULTADO)
      ESCREVAL("**********************************")

Fimalgoritmo