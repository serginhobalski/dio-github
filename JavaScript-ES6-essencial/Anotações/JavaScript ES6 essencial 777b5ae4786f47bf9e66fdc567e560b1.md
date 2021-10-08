# JavaScript ES6 essencial

## Introdução ao ES6

- **História e conceitos**
    - Lançado em 1995
    - Criado por Brendan Eich
    - ECMAScript ⇒ É a padronização do JavaScript pela ECMA.
    - TC39 ⇒ Comitê responsável pela evolução do JavaScript
        - Fluxo de proposta:
            - Stage 0: strawman (formulário p/ sugestão de evolução do ES)
            - Stage 1: proposal (entrega da proposta)
            - Stage 2: draft (a 1ª versão da proposta)
            - Stage 3: candidate (proposta quase finalizada)
            - Stage 4: finished (pronta para ser implementada)
    - ES2018 ⇒ Última implementação
        - Operações res/spread
        - Iteração assíncrona
        - Promisse.prototype.finaly()
    - [ES.Next](http://ES.Next) ⇒ Especificação que possui futuras implementações
    
    **CONCEITOS JavaScript**
    
    - Linguagem interpretada
    - Linguagem de tipagem fraca e dinâmica
    - Typescript ([https://www.typescriptlang.org/](https://www.typescriptlang.org/)) ⇒ É um "superset" da linguagem JavaScript que adiciona funcionalidades que o JS não possui por padrão, como interface, e-nums, etc.
    - Flow ([https://flow.org/en/](https://flow.org/en/)) ⇒ faz uma checagem de tipos do JS
    - Funções de primeira classe e ordem maior ⇒ a função pode ser atribuída a uma variável ou rede de dados e ser passada por argumentos e ser retornada por outras funções.
    - Closure (escopo léxico) ⇒ É a capacidade de uma função lembrar o ambiente em que foi criada
- **Currying, Hoisting, Imutabilidade, Tipos e Variáveis**
    
    **Curryng** ⇒ É a técnica de transformar uma função com *n* parâmetros em uma função que recebe apenas um parâmetro
    
    ```jsx
    function soma(a){
    	return function(b) {
    		return a + b;
    	}
    }
    
    const soma2 = soma(2);
    
    console.log(soma2(2));
    console.log(soma2(3));
    console.log(soma2(4));
    console.log(soma2(5));
    ```
    
    ---
    
    **Hoisting** ⇒ Significa levantar ou suspender algo 
    

## Tipos, variáveis, operadores, condicionais e repetição em JavaScript ES6

- **Tipos e variáveis**
- **Functions e operadores**
- **Spread, estruturas condicionais e repetição**

## Orientação a objetos e Design Patterns com a linguagem ES6

- **Introdução a orientação a objetos**
    
    Prototype
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%201.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%202.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%203.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%204.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%205.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%206.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%207.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%208.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%209.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2010.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2011.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2012.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2013.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2014.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2015.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2016.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2017.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2018.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2019.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2020.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2021.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2022.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2023.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2024.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2025.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2026.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2027.png)
    
- **Introdução a Design Patterns**
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2028.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2029.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2030.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2031.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2032.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2033.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2034.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2035.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2036.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2037.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2038.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2039.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2040.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2041.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2042.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2043.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2044.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2045.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2046.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2047.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2048.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2049.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2050.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2051.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2052.png)
    

## Manipulação e iteração de arrays

- **Criando e manipulando arrays**
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2053.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2054.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2055.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2056.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2057.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2058.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2059.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2060.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2061.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2062.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2063.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2064.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2065.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2066.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2067.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2068.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2069.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2070.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2071.png)
    
- **Iterar, buscar e transformar elementos**
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2072.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2073.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2074.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2075.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2076.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2077.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2078.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2079.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2080.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2081.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2082.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2083.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2084.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2085.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2086.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2087.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2088.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2089.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2090.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2091.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2092.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2093.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2094.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2095.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2096.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2097.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2098.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%2099.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20100.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20101.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20102.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20103.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20104.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20105.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20106.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20107.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20108.png)
    
    ![Untitled](JavaScript%20ES6%20essencial%20777b5ae4786f47bf9e66fdc567e560b1/Untitled%20109.png)
    

## AVALIAÇÃO