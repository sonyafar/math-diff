# math-diff
NPM package for symbolic differentiation plugin [math.diff.js](https://github.com/hausen/math.diff.js).

[![npm version](https://badge.fury.io/js/math-diff.svg)](https://badge.fury.io/js/math-diff)
![lifetimeDownloadCount](https://img.shields.io/npm/dt/math-diff.svg?maxAge=2592000)
<a href='https://pledgie.com/campaigns/31873'><img alt='Pledge To Arupex!' src='https://pledgie.com/campaigns/31873.png?skin_name=chrome' border='0' ></a>
    
## Install

    npm install math-diff --save  

## Usage

    let math_diff = require('math-diff');
    let equation = '2x^5-cos(x)-x*exp(x)';
    
    let derivative =  math_diff(equation, 'x').toString(); // Output: 10 * x ^ 4 - -sin(x) - (exp(x) + x * exp'(x))
