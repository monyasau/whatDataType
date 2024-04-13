# Installation:
 npm i whatdatatype

# Usage:

    yourCode.js:
            const checkDataType = require('whatDataType'); //import the package
            console.log(checkDataType(123)); // returns number
            console.log(checkDataType("Hello world)); // returns string
            console.log(checkDataType(true)); // returns boolean
            console.log(checkDataType(()=>{})); // returns function
            console.log(checkDataType({a:"aa",b:"bb"})); // returns object
            console.log(checkDataType([1,"aaa",true])); // returns array
            console.log(checkDataType()); // returns undefined
        These code will return: number, string, boolean, function, object, array, undefined. respectively