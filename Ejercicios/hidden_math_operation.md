# Operación matemática oculta

Encuentra la lógica de las siguientes operaciones y números:

5 + 4 = 19  
8 + 2 = 610  
10 + 8 = 218  
12 + 9 = 321  
18 + 2 = 1620  
21 + 5 = 1626  

## Solución

{% tabs %}

{% tab title="Ruby" %}
  ```ruby
  def hidden_math_operation number1, number2
    "#{number1 - number2}#{number1 + number2}"
  end
  ```
{% endtab %}

{% tab title="JavaScript" %}
  ```javascript
  const hidden_math_operation = (number1, number2) => {
    return `${number1 - number2}${number1 + number2}`
  }
  ```
{% endtab %}

{% tab title="Python" %}
  ```python

  ```
{% endtab %}

{% endtabs %}