# intelig-ncia-artificial-
 Script de inteligência Artificial Desenvolvido em Python!

# Importando a biblioteca random para simular entradas
import random

# Função para tomada de decisão inteligente
def decidir(input):
    # Condição para input positivo
    if input == "positivo":
        print("A escolha é sim!")
    # Condição para input negativo
    elif input == "negativo":
        print("A escolha é não!")
    # Condição para input neutro
    else:
        print("Não consigo decidir.")

# Simulação de input
input_usuario = random.choice(["positivo", "negativo", "neutro"])

# Chamada da função de decisão com o input simulado
decidir(input_usuario)
