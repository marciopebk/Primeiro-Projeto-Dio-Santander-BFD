## IMC
Algoritmo "IMC"

Var
   M, A , IMC: REAL

Inicio
      ESCREVA ("MASSA (KG): ")
      LEIA (M)
      ESCREVA ("ALTURA (M): ")
      LEIA (A)
      IMC <- M / (A^2)
      ESCREVAL ("IMC: ", IMC:4:2)
      SE (IMC < 17) ENTAO
         ESCREVAL("MUITO ABAIXO DO PESO")
      SENAO
           SE (IMC >= 17) E (IMC < 18.5) ENTAO
              ESCREVAL("ABAIXO DO PESO")
           SENAO
                SE (IMC >= 18.5) E (IMC < 25) ENTAO
                   ESCREVAL("PESO IDEAL")
                SENAO
                     SE (IMC >= 25) E (IMC < 30) ENTAO
                        ESCREVAL("SOBREPESO")
                     SENAO
                          SE (IMC >= 30) E (IMC < 35) ENTAO
                             ESCREVAL("OBESIDADE")
                          SENAO
                               SE (IMC >= 35) E (IMC <40) ENTAO
                                  ESCREVAL("OBESIDADE SEVERA")
                               SENAO
                                    ESCREVAL("OBESIDADE MORBIDA")
                               FIMSE
                          FIMSE
                     FIMSE
                FIMSE
           FIMSE
      FIMSE


Fimalgoritmo