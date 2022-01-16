# React.js_Ex2_Sem10

Quando o useReducer é preferível em relação ao useState? Cite 1 exemplo.

useReducer é geralmente preferível em relação ao useState quando se tem uma lógica de estado complexa que envolve múltiplos sub-valores, ou quando o próximo estado depende do estado anterior. useReducer também possibilita a otimização da performance de componentes que disparam atualizações profundas porque é possível passar o dispatch para baixo, ao invés de callbacks.
Exmplo: soma dos valores de uma array, contar valores iguais em um objeto, agrupar objetos por uma propriedade, remover valores duplicados, etc
