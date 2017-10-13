#TLT
/ functions
/ if statements
- local vs global variables
- if statements
    - 'if () []'
- Using '&&' and '||' in an if condition
    - '&&' two conditions must be true
    - '||' either condition must be true
- 'get' is a fucntion within an object
    - runs when you access thgat property
    - an object is a type of data structure using key value pairs, value inside
    - '''

            var car = {
                color: 'blue',
                model: 'convertiable'
                get brakestatus () {
                    console.log('okay!')
                }
            };
            car.color; // 'blue'
            car.brakeStatus; // ' okay!'
- functions parameters are optional
- function parameters go inside the parenthesis ()
- function code goes inside curly brackets '{}'
- how to return values from functions
    - '''

        function getCookies () {
            return 'a gazillion cookies';
        }
        var what = get cookies ();
        what; // 'a gazillion cookies' = the value of what is a gazillion cookies