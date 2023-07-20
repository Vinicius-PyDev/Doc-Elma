# Documentação do Modulo Elma
### Modulo Elma:
### Ola, seja bem vindo a home page do modulo Elma um Modulo de programação para python feito para poder auxiliar quase quelquer tipo de projeto com os seus recursos rapidos de emplementação basica como por exemplo calcular tempo de execução ou ate mesmo criar uma variavel de Switch (do tipo interruptor que liga e desliga)

## Switch()
### Object: Switch()
Lampada = Switch() # Cria um objeto Switch
Switch: Methods
Trade():
sempre retora o valhor oposto do estado atual da variavel de True para False e de False para True
## Telltime()
### Telltime(back=False) # Default
Tt() \# Voce pode abreviar a função dessa forma
Telltime() \# Retorna no final do seu codigo o tempo de execução independente de onde voce chame essa função
\# Obs: A função precisa estar dentro de um contexto funcional então se estiver dentro de um if só sera chamada se a condição do if for atendida
Telltime(back=True) # retorna a string referente ao inicio do script e quando voce faz isso 2 coisas acontecem
# 1 - A referencia do tempo muda então a proxima vez que voce chamar essa função ela vai comparar o tempo atual com a ultima vez que voce usou essa função
# 2 - A função que mostra o seu tempo no final do codigo não não sera chamada por isso ser uma ativação com a flag True
