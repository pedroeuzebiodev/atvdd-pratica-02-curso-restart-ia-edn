<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/pedroeuzebiodev/atvdd-pratica-02-curso-restart-ia-edn?color=3b82f6" />

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/pedroeuzebiodev/atvdd-pratica-02-curso-restart-ia-edn" />

  <a href="https://github.com/pedroeuzebiodev/atvdd-pratica-02-curso-restart-ia-edn/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/pedroeuzebiodev/atvdd-pratica-02-curso-restart-ia-edn" />
  </a>

   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen" />

   <a href="https://github.com/pedroeuzebiodev/atvdd-pratica-02-curso-restart-ia-edn/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/pedroeuzebiodev/atvdd-pratica-02-curso-restart-ia-edn?style=social" />
  </a>

  <a href="https://pedroeuzebiodev.github.io/atvdd-pratica-02-curso-restart-ia-edn">
    <img alt="Feito pelo Pedro Euzebio" src="https://img.shields.io/badge/feito%20por-Pedro%20Euzebio-3b82f6" />
  </a>
</p>

<h4 align="center">
 🚧  Atividade Prática 02 do curso Restar + IA da Escola da Nuvem (EdN) 🔗 Concluído 🚀 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Questões</a> •
 <a href="#-tecnologias">Tecnologias</a> •
 <a href="#-autor">Autor</a> •
 <a href="#user-content--licença">Licença</a>
</p>

## Questões

### 1. Conversor de Moeda

Crie um programa que converte um valor em reais para dólares e euros. Use os seguintes dados:

- Valor em reais: R$ 100.00
- Taxa do dólar: R$ 5.20
- Taxa do euro: R$ 6.15

O programa deve calcular e exibir os valores convertidos, arredondando para duas casas decimais.

**Resolução:**

```py
def conversao_moedas():
  valor_reais = 100.00
  taxa_dolar = 5.20
  taxa_euro = 6.15

  valor_dolares = valor_reais / taxa_dolar
  valor_euros = valor_reais / taxa_euro

  print(f"Valor original: R$ {valor_reais:.2f}")
  print(f"Taxa do dólar: R$ {taxa_dolar:.2f}")
  print(f"Taxa do euro: R$ {taxa_euro:.2f}")
  print(f"Valor em dólares: US$ {valor_dolares:.2f}")
  print(f"Valor em euros: € {valor_euros:.2f}")

conversao_moedas()
```

### 2. Calculadora de Desconto

Desenvolva um programa que calcula o desconto em uma loja. Use as seguintes informações:

- Nome do produto: "Camiseta"
- Preço original: R$ 50.00
- Porcentagem de desconto: 20%

O programa deve calcular o valor do desconto e o preço final, exibindo todos os detalhes.

**Resolução:**

```py
def calculo_desconto():
  produto = "Camiseta"
  preco_original = 50.00
  porcentagem_desconto = 20

  valor_desconto = (preco_original * porcentagem_desconto) / 100
  preco_final = preco_original - valor_desconto

  print(f"Produto: {produto}")
  print(f"Preço original: R$ {preco_original:.2f}")
  print(f"Desconto: {porcentagem_desconto}%")
  print(f"Valor do desconto: R$ {valor_desconto:.2f}")
  print(f"Preço final: R$ {preco_final:.2f}")

calculo_desconto()
```

### 3. Calculadora de Média Escolar

Crie um programa que calcula a média escolar de um aluno. Use as seguintes notas:

- Nota 1: 7.5
- Nota 2: 8.0
- Nota 3: 6.5

O programa deve calcular a média e exibir todas as notas e o resultado final, arredondando para duas casas decimais.

**Resolução:**

```py
def media_escolar():
  nota1 = 7.5
  nota2 = 8.0
  nota3 = 6.5

  media = (nota1 + nota2 + nota3) / 3

  print(f"Nota 1: {nota1}")
  print(f"Nota 2: {nota2}")
  print(f"Nota 3: {nota3}")
  print(f"Média final: {media:.2f}")

media_escolar()
```

### 4. Calculadora de Consumo de Combustível

Desenvolva um programa que calcula o consumo médio de combustível de um veículo. Use os seguintes dados:

- Distância percorrida: 300 km
- Combustível gasto: 25 litros

O programa deve calcular o consumo médio (km/l) e exibir todos os dados da viagem, incluindo o resultado final arredondado para duas casas decimais.

**Resolução:**

```py
def consumo_combustivel():
  distancia = 300
  combustivel = 25

  consumo_medio = distancia / combustivel

  print(f"Distância percorrida: {distancia} km")
  print(f"Combustível gasto: {combustivel} litros")
  print(f"Consumo médio: {consumo_medio:.2f} km/l")

consumo_combustivel()
```

---

## 🛠 Tecnologias

A seguinte ferramenta foi usada na construção da atividade:

- **[Python](https://www.python.org)**

---

## 🦸 Autor

<a href="https://www.linkedin.com/in/pedroeuzebio">
  <img style="border-radius: 50%;" src="https://i.imgur.com/uieVTmO.png" width="100px;" alt="" />

  <br />

  <sub>
    <b>Pedro Euzebio</b>
  </sub>
</a>

<br>

<a href="mailto:pedroeuzebio.contato@gmail.com" class="contato">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=plastic&logo=gmail&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/pedroeuzebio" class="contato">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=plastic&logo=linkedin&logoColor=white" />
</a>

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Pedro Euzebio 👋 [Entre em contato!](https://www.linkedin.com/in/pedroeuzebio)
