Algoritmo "Cadastro Agência de Viagem"
//
//
// Descrição   : Cadastro cliente, destino e consulta de dados.
// Autor(a)    : Thiago Muniz Ferreira
// Data atual  : 26/06/2022

tipo

   Clientes = registro

    Nome : caracter
    endereco: caracter
    destino : caracter
    telefone:real
    cpf: real
    nascimento : real
    data_ida: real
    data_volta: real

             fimregistro


Var
   // Seção de Declarações das variáveis


       lista_clientes: vetor[0..1] de clientes




       opcao:inteiro

   nome, endereco, destino:caracter
   cpf,telefone,data_nascimento:real
   data_ida, data_volta: real
   
   alt_name, alt_end, alt_cpf, alt_tel, data_nasc:caracter
   alt_dest, alt_ida, alt_volt: caracter
   cons_nome, cons_end, cons_cpf, cons_tel, cons_nasc:caracter
   cons_dest, cons_ida, cons_volt:caracter
   exc_nome, exc_end, exc_cpf, exc_tel, exc_nasc:caracter
   exc_dest, exc_ida, exc_volt:caracter
   nome_cliente: caractere
   




Inicio
   // Seção de Comandos, procedimento, funções, operadores, etc...






   repita





      escreval("*****Cadastro de cliente*****")
      escreval("1-incluir")
      escreval("2-consultar")
      escreval("3-Sair")
      leia(opcao)
      escolha opcao


   
      caso 1



      escreval("          Cadastro de Clientes           ")

      para opcao de 1 ate 1 faca

      escreval ("Digite o nome do cliente:")
      leia(lista_clientes[opcao].nome)

      escreval("Digite o endereço:")
      leia(lista_clientes[opcao].endereco)
      
      escreval ("Digite o telefone:")
      leia(lista_clientes[opcao].telefone)

      escreval("Digite o CPF:")
      leia(lista_clientes[opcao].cpf)

      escreval("Digite a data de nascimento:")
      leia(lista_clientes[opcao].nascimento)

      escreval("Digite o destino:")
      leia(lista_clientes[opcao].destino)

      escreval("Digite data de ida:")
      leia(lista_clientes[opcao].data_ida)

      escreval("Digite data de volta:")
      leia(lista_clientes[opcao].data_volta)


      fimpara

            //Impressão dos Dados Inseridos

      escreval("          Dados de Clientes           ")

      para opcao de 1 ate 1 faca

           // Cliente .... com destino para ....  na data de ida de .... e volta ....

      escreval ("Cliente ")

      escreval("-------------------------------------")

      escreval(lista_clientes[opcao].nome)
      escreval("-------------------------------------")
      escreval(lista_clientes[opcao]. endereco)
      escreval("-------------------------------------")
      escreval(lista_clientes[opcao].cpf)
      escreval("-------------------------------------")
      escreval(lista_clientes[opcao].nascimento)
      escreval("-------------------------------------")


      escreval("com destino para")
      escreval(lista_clientes[opcao].destino)

      escreval("-------------------------------------")

      escreval("na data de ida ")
      escreval(lista_clientes[opcao].data_ida)

      escreval("-------------------------------------")

      escreval("e volta marcada para ")
      escreval(lista_clientes[opcao].data_volta)


      fimpara


      caso 2

         escreval("*****Consultar dados*****")
         escreval("1 - Consultar Nome")
         escreval("2 - Consultar Endereço")
         escreval("3 - Consultar CPF")
         escreval("4 - Consultar Telefone")
         escreval("5 - Consultar Data de Nascimento")
         escreval("6 - Consultar Destino")
         escreval("7 - Consultar Data de Ida")
         escreval("8 - Consultar Data de Volta")
         leia(opcao)
         se opcao=1 então
            escreva("Consulte o Nome:")
            leia(cons_nome)
         senao
            se opcao=2 então
               escreva("Consulte o Endereço:")
               leia(cons_end)
            senao
               se opcao=3 então
                  escreva("Consulte o CPF:")
                  leia(cons_cpf)
               senao
                  se opcao=4 então
                     escreva("Consulte o Telefone:")
                     leia(cons_tel)
                  senao
                     se opcao=5 então
                        escreva("Consulte a Data de Nascimento:")
                        leia(cons_nasc)
                     senao
                        se opcao=6 entao
                           escreva("Consulte o Destino:")
                           leia(cons_dest)
                        senao
                           se opcao=7 entao
                              escreva("Consulte a Data de Ida:")
                              leia(cons_ida)
                           senao
                              se opca=8 entao
                                 escreva("Consulte a Data de Volta:")
                                 leia(cons_volt)
                              fimse
                           fimse
                        fimse
                     fimse
                  fimse
               fimse
            fimse
         fimse


      caso 3
         escreva("Programa encerrado!")
      outrocaso
         escreval("opção Invalida")
      fimescolha
   ate opcao=3
//fimalgoritmo




Fimalgoritmo
