# Locadora

Programa de locadora utilizando herança, getters and setters, construtores, encapsulamento, exception, overloading e outros metodos em java.

A main (Locadora) é responsavel apenas por printar as informações na tela e chamar as funções ja criadas. 

Na classe "Veiculos", temos a importação de algumas bibliotecas pra que os metodos utilizados sejam funcionais, como o "LocalDate", "regex.Matcher" e "regex.Pattern". Temos tambem a inserção de alguns dados como modelo; placa; montadora; cor; data_fabricacao; tipo_combustivel; placa_valida. E na sequencia os guetters and setters com suas devidas exceptions para não haver erro na compilação e por fim o validador de placa.

Nas demais classes (carro, moto e caminhão) são basicamente as mesmas coisas, porem com informações diferentes, recebendo informações porherança da classe "veículos" e sem a função de validar_placa.
