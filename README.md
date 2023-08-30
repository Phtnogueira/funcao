def carros(marca, modelo, ano, placa):
    print(f"Carro inserido com sucesso! {marca}/{modelo}/{ano}/{placa}")

carros(" Fiat", "Palio", 1999, "ABC-1234 ")
carros(marca = "Fiat", modelo = "Palio", ano = "1999", placa = "ABC-1234")
carros(**{"marca": "Fiat", "modelo": "Palio", "ano": 1999, "Placa": "ABC-1234"})
#Essa de cima é um dicionario com a função.
