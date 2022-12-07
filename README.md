# Tarefa backend #1

### Série de tarefas para treinar os conhecimentos em Backend.

✅ Task:

Desafio, API que retorna o endereço.\*

Eu gostaria de obter o endereço completo como o json abaixo:
<br>

```yaml
{
  "cep": "08340-146",
  "logradouro": "Rua Forte do Triunfo",
  "bairro": "Parque São Lourenço",
  "localidade": "São Paulo",
  "uf": "SP",
}
```

<br>
Resultado de quando passo o cep na url por exemplo:
{url_da_aplicação}/cep/<cep_escrito>

Pegar o url param do cep, enviar para a api do via cep https://viacep.com.br/ws/01001000/json/
E tratar o valor para retornar o json que foi descrito ali no começo.

A aplicação também deve ter testes.

---

### Planejamento

Essa aplicação deve consultar um CEP

### Extras

- Essa aplicação deve calcular preços e prazos
- Essa aplicação deve rastrear uma encomenda
