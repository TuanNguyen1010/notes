| Ruby terms | JavaScript equivalent |
| ----- | ---- |
| classes ```class Object``` | prototype ```function Cat(name, age) {};``` |
| variables ```hat = []``` | ```var hat = []```|
| variable naming in snake case ```my_hats``` | camel case ```var myHats``` |
| arrays ```[2, 3, 'Four']``` | ```var arr = []``` |
| hashes ```{key: topping, value: pineapple}``` | ```{}``` |
| add new key & value to hash ```hash[:topping] = "pineapple"```  | ```hash.topping = "pineapple"``` |
| addition ```2+2``` | same |
| subtraction ```2-1``` | same |
| multiplication ```2*2``` | same |
| modulus ```2%4``` | same |
| iteration ```.map``` ```.each``` | ```[].forEach(function(n){});``` |
| methods ```def say_hello``` | function ```function hello() { };```|
| method naming ```def increase_temperature``` | ```Thermostat.prototype.increaseTemperature = function() { };``` |
| method naming with ? ```def purebreed?``` | ```isPurebreed``` |
| private methods in class ```private``` | ```Banana.prototype._myPrivateMethod``` |
| print ```puts``` ```print``` ```p``` | ```console.log();``` |
| instance variables ```@id``` / attr_reader ```attr_reader :id``` / initialize ``` def initialize(id:)```  | ```this.id = id;```  |
| method within class ```def hello ... end ``` | ```this.meow = function() { };```|
| ```self``` | ```this``` |
| create instance of class ```Cat.new("Tibs")``` | ```new Cat("Tibs")``` |
| conditionals ```if ... else ... end``` ```unless```| ```if (condition) {} else if (condition2) {} else {};```|
| comparitors ```==``` ```>``` ```<=```| ```==``` compares any types, so ```1 == '1'``` is true, ```===``` doesn't compare different types, so ```1 === '1'``` is false |
| booleans ```true``` ```false``` | Examples of expressions that can be converted to false are: ```null;``` ```NaN;``` ```0``` empty string (```""``` or ```''```) |
| negation ```!``` | same |
| and / or ```&&``` / ``` \|\|``` | same |
| converst to string ```to_s``` | ```toString()```|
| convert to string to integer ```to_i```| ```parseInt(string, 10)```  where 10 is the base number i.e. radix |
| convert to symbol ```to_sym``` | ```Symbol()``` |
| ```return``` | same |
| raise error ```raise``` ```fail``` | ```throw``` |
| switches ```case ... when ... end``` | ```switch(expression) { case x: ... break; case y: ... break; default: ... }``` |
| falsey values | [Source:](https://flatironschool.com/blog/javascript-vs-ruby) "Like in Ruby, null (in Ruby, it’s nil) and false will return false, however, some truthful values in Ruby will return false in JavaScript, like 0, empty strings (“”), and undefined." |
| one liner assignment | ```var person = "John Doe", carName = "Volvo", price = 200;```|
| increment ```+=``` | ```++``` |
| decrement ```-=``` | ```--``` |
| to the power of ```**``` | same |
| | ```typeof 3``` returns 'number' |
| string interpolation ```"Hello, #{person}"``` | ``` `Hello, ${person}` ``` Note: have to use backs ticks |
| constants ```MY_TOTAL = 10``` | there are no constants, they can be changed ```Poker.prototype.MY_TOTAL = 10;```, ES6: ```const MY_TOTAL = 10;```|
| scope of variables |  |
