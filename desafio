import random

palavras = ["sonho", "valsa", "prata", "azul", "rosa", "tulipa", "tempo"]

palavra = palavras[random.randint(0, 6)]
word = [" "] * len(palavra)
i = 0

for char in palavra:
    word[i] = char
    i += 1

adivinha = ["_"] * len(palavra)

print("Vamos jogar jogo da forca!")

chutes = ()
tentativas = 10
acertouLetra = 0

while tentativas > 0 and word != adivinha:
    print("\nVocê tem mais", + tentativas, 'tentativas.')
    chutes = input("Digite uma letra: ")

    for i in range(0, len(palavra)):
        if word[i] == chutes:
            adivinha[i] = chutes
            acertouLetra = 1

    if acertouLetra == 1:
        print("\nVocê acertou a letra!")

    else:
        print("\nVocê errou a letra!")

    tentativas -= 1
    print(" ".join(adivinha))

if word == adivinha:
    print("\nVocê acertou a palavra!")
else:
    print("\nVocê perdeu! :(")
