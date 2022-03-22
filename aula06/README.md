# Terceira aula

### Conversões de tipos:

Já que toda vez que eu fizer uma chamada com o window.prompt eu vou ter uma String, então eu faço as conversões

* Number.parseInt(n)
* Number.parseFloat(n)
* Nas versões mais recentes do JS: Number(n)

Para transformar de Número para String eu faço o mesmo

* String(n)
* n.toString()

Para formatação de números eu tenho:

* n.toFixed(2) -> Para determinar a quantidade de casas decimais
* n.toFixed(2).replacec('.', ',') -> Para trocar ponto por vírgula

n.toLocaleString('pt-br', {style: 'currency', currency: 'BRL'}) -> Para trabalhar com conversão de moedas