# C-digo-Simples-de-vogais
Um código simples em Python que identifica um input contém vogal ou não
while True:
    try:
        vogal = input('Insira uma Vogal: ')
        if vogal.lower() in ['a', 'e', 'i', 'o', 'u']:
            print('É Vogal')
            break
        else:
            print('Não é Vogal')
            continue
    except Exception as erro:
        print(f'erro, {erro.__cause__}')
