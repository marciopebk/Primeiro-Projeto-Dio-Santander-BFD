## Média X Siatuação escolar
Algoritmo "MEDIA_ALUNO_X_SITUAÇÃO"

Var
   ALUNO: CARACTERE
   N1, N2, M: REAL

Inicio
      ESCREVA ("INFORME O NOME DO ALUNO: ")
      LEIA(ALUNO)
      ESCREVA("DIGITE A NOTA 1 DO ALUNO: ")
      LEIA(N1)
      ESCREVA ("DIGITE A NOTA 2 DO ALUNO: ")
      LEIA(N2)
      M <- (N1 + N2)/2
      ESCREVAL("A MÉDIA DO ALUNO É ", M:4:2)
      SE (M>= 7.00) ENTAO
         ESCREVA ("ALUNO APROVADO")
         SENAO
              SE (M >= 4) E (M < 7) ENTAO
                 ESCREVA("ALUNO EM RECUPERAÇÃO")
              SENAO
                   ESCREVAL("ALUNO REPROVADO")
              FIMSE
      FIMSE


Fimalgoritmo