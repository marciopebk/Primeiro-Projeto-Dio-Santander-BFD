## Média X Classificação

Algoritmo "MEDIA_X_CLASSIFICACAO"

Var
   ALUNO: CARACTERE
   N1, N2, N3, N4, M: REAL

Inicio
      ESCREVA("INFORME O NOME DO ALUNO: ")
      LEIA(ALUNO)
      ESCREVA("INFORME A NOTA DA UNIDADE 1 DO ALUNO: ")
      LEIA(N1)
      ESCREVA("INFORME A NOTA DA UNIDADE 2 DO ALUNO: ")
      LEIA(N2)
      ESCREVA("INFORME A NOTA DA UNIDADE 3 DO ALUNO: ")
      LEIA(N3)
      ESCREVA("INFORME A NOTA DA UNIDADE 4 DO ALUNO: ")
      LEIA(N4)
      M <- (N1 +N2 + N3 + N4)/4
      SE (M >= 7)
         ESCREVAL("PARABÉNS VOCÊ FOI APROVADO")
      SENAO
           SE (M >= 4) E (M < 7) ENTAO
              ESCREVAL("FOI QUASE, MAS VOCÊ PRECISARÁ FAZER RECUPERAÇÃO")
           SENAO
                ESCREVAL("INFELIZMENTE NÃO FOI DESSA VEZ, TENTE NO PRÓXIMO ANO")
           FIMSE
      FIMSE
      ESCREVAL("A MEDIA ANUAL DO ALUNO ", ALUNO, " FOI DE ", M:4:2, " PONTOS")
      SE (M >= 9) E (M <= 10) ENTAO
         ESCREVA("CLASSIFICAÇÃO: A")
      SENAO
           SE (M >= 8) E (M < 9) ENTAO
              ESCREVA("CLASSIFICAÇÃO: B")
           SENAO
                SE (M >= 7) E (M < 8) ENTAO
                   ESCREVA("CLASSIFICAÇÃO: C")
                SENAO
                     SE (M >= 6) E (M < 7) ENTAO
                        ESCREVA("CLASSIFICAÇÃO: D")
                     SENAO
                          SE (M >=5) E (M <6) ENTAO
                             ESCREVA("CALSSIFICAÇÃO: E")
                          SENAO
                          ESCREVA("CALSSIFICAÇÃO: F")
                          FIMSE
                     FIMSE
                FIMSE
           FIMSE
      
      FIMSE

Fimalgoritmo