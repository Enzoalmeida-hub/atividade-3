# atividade-3
algoritmo "ProcessoSeletivoGitHub"

var
   idade, projetos : inteiro

   inicio
      // Entrada de dados
         Escreva("Digite a sua idade: ")
            Leia(idade)
               Escreva("Quantos projetos você tem no GitHub? ")
                  Leia(projetos)

                     // Verificação com o operador E (as duas condições devem ser verdadeiras)
                        Se (idade > 18) E (projetos >= 5) Entao
                              EscrevaL("Candidato aprovado para a entrevista!")
                                 Senao
                                       EscrevaL("Candidato não atende aos requisitos mínimos.")
                                          FimSe
                                          fimalgoritmo