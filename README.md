# api documentation for  [numbers (v0.6.0)](https://github.com/numbers/numbers.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-numbers.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-numbers) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-numbers.svg)](https://travis-ci.org/npmdoc/node-npmdoc-numbers)
#### Advanced Mathematics Library for JavaScript

[![NPM](https://nodei.co/npm/numbers.png?downloads=true)](https://www.npmjs.com/package/numbers)

[![apidoc](https://npmdoc.github.io/node-npmdoc-numbers/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-numbers_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-numbers/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-numbers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-numbers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Kaliski",
        "email": "sjkaliski@gmail.com",
        "url": "https://github.com/sjkaliski"
    },
    "bugs": {
        "url": "https://github.com/numbers/numbers.js/issues"
    },
    "contributors": [
        {
            "name": "David Byrd",
            "url": "https://github.com/davidbyrd11"
        },
        {
            "name": "Ethan Resnick",
            "url": "https://github.comc/ethanresnick"
        },
        {
            "name": "Dakota St. Laurent",
            "url": "https://github.com/StDako"
        },
        {
            "name": "Kartik Talwar",
            "url": "https://github.com/KartikTalwar"
        },
        {
            "name": "Larry Battle",
            "url": "https://github.com/LarryBattle"
        }
    ],
    "dependencies": {},
    "description": "Advanced Mathematics Library for JavaScript",
    "devDependencies": {
        "browserify": "~5.12.1",
        "del": "~0.1.3",
        "gulp": "~3.8.8",
        "gulp-jsbeautifier": "0.0.3",
        "gulp-jshint": "~1.8.4",
        "gulp-mocha": "~1.1.0",
        "gulp-rename": "~1.2.0",
        "gulp-uglify": "~1.0.1",
        "jshint-stylish": "~1.0.0",
        "mocha": "~1.8.0",
        "seedrandom": "~2.3.10",
        "uglify-js": "~2.2.2",
        "vinyl-buffer": "~1.0.0",
        "vinyl-source-stream": "~1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fd4af298e748b47d617305a9133a4c1302b8d9af",
        "tarball": "https://registry.npmjs.org/numbers/-/numbers-0.6.0.tgz"
    },
    "engines": {
        "node": ">= v0.6.0"
    },
    "homepage": "https://github.com/numbers/numbers.js",
    "keywords": [
        "math",
        "mathematics",
        "numbers",
        "statistics"
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "sjkaliski",
            "email": "sjkaliski@gmail.com"
        }
    ],
    "name": "numbers",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/numbers/numbers.js.git"
    },
    "scripts": {
        "build": "gulp build",
        "format": "gulp format",
        "lint": "gulp lint",
        "test": "gulp test"
    },
    "version": "0.6.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module numbers](#apidoc.module.numbers)
1.  [function <span class="apidocSignatureSpan">numbers.</span>complex (re, im)](#apidoc.element.numbers.complex)
1.  number <span class="apidocSignatureSpan">numbers.</span>EPSILON
1.  object <span class="apidocSignatureSpan"></span>numbers
1.  object <span class="apidocSignatureSpan">numbers.</span>basic
1.  object <span class="apidocSignatureSpan">numbers.</span>calculus
1.  object <span class="apidocSignatureSpan">numbers.</span>complex.prototype
1.  object <span class="apidocSignatureSpan">numbers.</span>dsp
1.  object <span class="apidocSignatureSpan">numbers.</span>generate
1.  object <span class="apidocSignatureSpan">numbers.</span>matrix
1.  object <span class="apidocSignatureSpan">numbers.</span>prime
1.  object <span class="apidocSignatureSpan">numbers.</span>random
1.  object <span class="apidocSignatureSpan">numbers.</span>random.distribution
1.  object <span class="apidocSignatureSpan">numbers.</span>statistic

#### [module numbers.basic](#apidoc.module.numbers.basic)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>binomial (n, k)](#apidoc.element.numbers.basic.binomial)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>divMod (a, b)](#apidoc.element.numbers.basic.divMod)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>egcd (a, b)](#apidoc.element.numbers.basic.egcd)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>factorial (num)](#apidoc.element.numbers.basic.factorial)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>fallingFactorial (n, k)](#apidoc.element.numbers.basic.fallingFactorial)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>gcd (a, b)](#apidoc.element.numbers.basic.gcd)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>isInt (n)](#apidoc.element.numbers.basic.isInt)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>lcm (num1, num2)](#apidoc.element.numbers.basic.lcm)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>max (arr)](#apidoc.element.numbers.basic.max)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>min (arr)](#apidoc.element.numbers.basic.min)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>modInverse (a, m)](#apidoc.element.numbers.basic.modInverse)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>numbersEqual (first, second, epsilon)](#apidoc.element.numbers.basic.numbersEqual)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>permutation (n, k)](#apidoc.element.numbers.basic.permutation)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>powerMod (a, b, m)](#apidoc.element.numbers.basic.powerMod)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>product (arr)](#apidoc.element.numbers.basic.product)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>random (arr, quant, allowDuplicates)](#apidoc.element.numbers.basic.random)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>range (start, stop, step)](#apidoc.element.numbers.basic.range)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>shuffle (array)](#apidoc.element.numbers.basic.shuffle)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>square (num)](#apidoc.element.numbers.basic.square)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>subtraction (arr)](#apidoc.element.numbers.basic.subtraction)
1.  [function <span class="apidocSignatureSpan">numbers.basic.</span>sum (arr)](#apidoc.element.numbers.basic.sum)

#### [module numbers.calculus](#apidoc.module.numbers.calculus)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>LanczosGamma (num)](#apidoc.element.numbers.calculus.LanczosGamma)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>MonteCarlo (func, N)](#apidoc.element.numbers.calculus.MonteCarlo)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>Riemann (func, start, finish, n, sampler)](#apidoc.element.numbers.calculus.Riemann)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>StirlingGamma (num)](#apidoc.element.numbers.calculus.StirlingGamma)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>adaptiveSimpson (func, a, b, eps)](#apidoc.element.numbers.calculus.adaptiveSimpson)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>limit (func, point, approach)](#apidoc.element.numbers.calculus.limit)
1.  [function <span class="apidocSignatureSpan">numbers.calculus.</span>pointDiff (func, point)](#apidoc.element.numbers.calculus.pointDiff)

#### [module numbers.complex](#apidoc.module.numbers.complex)
1.  [function <span class="apidocSignatureSpan">numbers.</span>complex (re, im)](#apidoc.element.numbers.complex.complex)

#### [module numbers.complex.prototype](#apidoc.module.numbers.complex.prototype)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>add (addend)](#apidoc.element.numbers.complex.prototype.add)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>complexPow (complexN)](#apidoc.element.numbers.complex.prototype.complexPow)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>conjugate ()](#apidoc.element.numbers.complex.prototype.conjugate)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>cos ()](#apidoc.element.numbers.complex.prototype.cos)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>divide (divisor)](#apidoc.element.numbers.complex.prototype.divide)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>equals (complex, epsilon)](#apidoc.element.numbers.complex.prototype.equals)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>magnitude ()](#apidoc.element.numbers.complex.prototype.magnitude)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>multiply (multiplier)](#apidoc.element.numbers.complex.prototype.multiply)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>phase ()](#apidoc.element.numbers.complex.prototype.phase)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>pow (n)](#apidoc.element.numbers.complex.prototype.pow)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>roots (n)](#apidoc.element.numbers.complex.prototype.roots)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>sin ()](#apidoc.element.numbers.complex.prototype.sin)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>subtract (subtrahend)](#apidoc.element.numbers.complex.prototype.subtract)
1.  [function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>tan ()](#apidoc.element.numbers.complex.prototype.tan)

#### [module numbers.dsp](#apidoc.module.numbers.dsp)
1.  [function <span class="apidocSignatureSpan">numbers.dsp.</span>fft (x)](#apidoc.element.numbers.dsp.fft)
1.  [function <span class="apidocSignatureSpan">numbers.dsp.</span>segment (arr, start, step)](#apidoc.element.numbers.dsp.segment)

#### [module numbers.generate](#apidoc.module.numbers.generate)
1.  [function <span class="apidocSignatureSpan">numbers.generate.</span>collatz (n, result)](#apidoc.element.numbers.generate.collatz)
1.  [function <span class="apidocSignatureSpan">numbers.generate.</span>fibonacci (n)](#apidoc.element.numbers.generate.fibonacci)

#### [module numbers.matrix](#apidoc.module.numbers.matrix)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>GaussJordanEliminate (m, epsilon)](#apidoc.element.numbers.matrix.GaussJordanEliminate)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>_check2DVector (point)](#apidoc.element.numbers.matrix._check2DVector)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>addition (arrA, arrB)](#apidoc.element.numbers.matrix.addition)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>affine (point, tx, ty)](#apidoc.element.numbers.matrix.affine)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>deepCopy (arr)](#apidoc.element.numbers.matrix.deepCopy)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>determinant (m)](#apidoc.element.numbers.matrix.determinant)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>dotproduct (vectorA, vectorB)](#apidoc.element.numbers.matrix.dotproduct)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>getCol (M, n)](#apidoc.element.numbers.matrix.getCol)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>identity (n)](#apidoc.element.numbers.matrix.identity)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>inverse (m)](#apidoc.element.numbers.matrix.inverse)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isColumnDD (M)](#apidoc.element.numbers.matrix.isColumnDD)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isLowerBand (M, p)](#apidoc.element.numbers.matrix.isLowerBand)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isRowDD (M)](#apidoc.element.numbers.matrix.isRowDD)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isSquare (arr)](#apidoc.element.numbers.matrix.isSquare)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isStrictlyColumnDD (M)](#apidoc.element.numbers.matrix.isStrictlyColumnDD)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isStrictlyRowDD (M)](#apidoc.element.numbers.matrix.isStrictlyRowDD)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>isUpperBand (M, q)](#apidoc.element.numbers.matrix.isUpperBand)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>lupDecomposition (arr)](#apidoc.element.numbers.matrix.lupDecomposition)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>matrixNorm (M, p)](#apidoc.element.numbers.matrix.matrixNorm)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>multiply (arrA, arrB)](#apidoc.element.numbers.matrix.multiply)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>reorderCols (M, L)](#apidoc.element.numbers.matrix.reorderCols)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>reorderRows (M, L)](#apidoc.element.numbers.matrix.reorderRows)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>reverseCols (M)](#apidoc.element.numbers.matrix.reverseCols)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>reverseRows (M)](#apidoc.element.numbers.matrix.reverseRows)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>rotate (point, degree, direction)](#apidoc.element.numbers.matrix.rotate)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>rowAddMultiple (m, from, to, scale)](#apidoc.element.numbers.matrix.rowAddMultiple)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>rowReduce (m, epsilon)](#apidoc.element.numbers.matrix.rowReduce)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>rowScale (m, row, scale)](#apidoc.element.numbers.matrix.rowScale)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>rowSwitch (m, row1, row2)](#apidoc.element.numbers.matrix.rowSwitch)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>scalar (arr, val)](#apidoc.element.numbers.matrix.scalar)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>scale (point, sx, sy)](#apidoc.element.numbers.matrix.scale)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>shear (point, k, direction)](#apidoc.element.numbers.matrix.shear)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>subtraction (arrA, arrB)](#apidoc.element.numbers.matrix.subtraction)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>transpose (arr)](#apidoc.element.numbers.matrix.transpose)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>vectorNorm (v, p)](#apidoc.element.numbers.matrix.vectorNorm)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>zeros (n, m)](#apidoc.element.numbers.matrix.zeros)
1.  [function <span class="apidocSignatureSpan">numbers.matrix.</span>zigzag (n, point, dir)](#apidoc.element.numbers.matrix.zigzag)

#### [module numbers.numbers](#apidoc.module.numbers.numbers)
1.  [function <span class="apidocSignatureSpan">numbers.numbers.</span>complex (re, im)](#apidoc.element.numbers.numbers.complex)
1.  number <span class="apidocSignatureSpan">numbers.numbers.</span>EPSILON
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>basic
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>calculus
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>dsp
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>generate
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>matrix
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>prime
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>random
1.  object <span class="apidocSignatureSpan">numbers.numbers.</span>statistic

#### [module numbers.prime](#apidoc.module.numbers.prime)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>coprime (a, b)](#apidoc.element.numbers.prime.coprime)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>factorization (num)](#apidoc.element.numbers.prime.factorization)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>getPerfectPower (n)](#apidoc.element.numbers.prime.getPerfectPower)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>getPrimePower (n)](#apidoc.element.numbers.prime.getPrimePower)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>millerRabin (n, k)](#apidoc.element.numbers.prime.millerRabin)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>sieve (n)](#apidoc.element.numbers.prime.sieve)
1.  [function <span class="apidocSignatureSpan">numbers.prime.</span>simple (n)](#apidoc.element.numbers.prime.simple)

#### [module numbers.random](#apidoc.module.numbers.random)
1.  [function <span class="apidocSignatureSpan">numbers.random.</span>bates (n, b, a)](#apidoc.element.numbers.random.bates)
1.  [function <span class="apidocSignatureSpan">numbers.random.</span>boxMullerTransform (mu, sigma)](#apidoc.element.numbers.random.boxMullerTransform)
1.  [function <span class="apidocSignatureSpan">numbers.random.</span>irwinHall (n, sub)](#apidoc.element.numbers.random.irwinHall)
1.  [function <span class="apidocSignatureSpan">numbers.random.</span>sample (lower, upper, n)](#apidoc.element.numbers.random.sample)
1.  [function <span class="apidocSignatureSpan">numbers.random.</span>setGenerator (fn)](#apidoc.element.numbers.random.setGenerator)
1.  object <span class="apidocSignatureSpan">numbers.random.</span>distribution

#### [module numbers.random.distribution](#apidoc.module.numbers.random.distribution)
1.  [function <span class="apidocSignatureSpan">numbers.random.distribution.</span>bates (n, b, a)](#apidoc.element.numbers.random.distribution.bates)
1.  [function <span class="apidocSignatureSpan">numbers.random.distribution.</span>boxMuller (n, mu, sigma, rc)](#apidoc.element.numbers.random.distribution.boxMuller)
1.  [function <span class="apidocSignatureSpan">numbers.random.distribution.</span>irwinHall (n, m, sub)](#apidoc.element.numbers.random.distribution.irwinHall)
1.  [function <span class="apidocSignatureSpan">numbers.random.distribution.</span>irwinHallNormal (n)](#apidoc.element.numbers.random.distribution.irwinHallNormal)
1.  [function <span class="apidocSignatureSpan">numbers.random.distribution.</span>logNormal (n, mu, sigma)](#apidoc.element.numbers.random.distribution.logNormal)
1.  [function <span class="apidocSignatureSpan">numbers.random.distribution.</span>normal (n, mu, sigma)](#apidoc.element.numbers.random.distribution.normal)

#### [module numbers.statistic](#apidoc.module.numbers.statistic)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>correlation (arrX, arrY)](#apidoc.element.numbers.statistic.correlation)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>covariance (set1, set2)](#apidoc.element.numbers.statistic.covariance)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>exponentialRegression (arrY)](#apidoc.element.numbers.statistic.exponentialRegression)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>linearRegression (arrX, arrY)](#apidoc.element.numbers.statistic.linearRegression)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>mean (arr)](#apidoc.element.numbers.statistic.mean)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>median (arr)](#apidoc.element.numbers.statistic.median)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>mode (arr)](#apidoc.element.numbers.statistic.mode)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>quantile (arr, k, q)](#apidoc.element.numbers.statistic.quantile)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>rSquared (source, regression)](#apidoc.element.numbers.statistic.rSquared)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>report (array)](#apidoc.element.numbers.statistic.report)
1.  [function <span class="apidocSignatureSpan">numbers.statistic.</span>standardDev (arr)](#apidoc.element.numbers.statistic.standardDev)



# <a name="apidoc.module.numbers"></a>[module numbers](#apidoc.module.numbers)

#### <a name="apidoc.element.numbers.complex"></a>[function <span class="apidocSignatureSpan">numbers.</span>complex (re, im)](#apidoc.element.numbers.complex)
- description and source-code
```javascript
complex = function (re, im) {
  this.re = re;
  this.im = im;
  this.r  = this.magnitude();
  this.t  = this.phase(); // theta = t = arg(z)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.basic"></a>[module numbers.basic](#apidoc.module.numbers.basic)

#### <a name="apidoc.element.numbers.basic.binomial"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>binomial (n, k)](#apidoc.element.numbers.basic.binomial)
- description and source-code
```javascript
binomial = function (n, k) {

  var arr = [];

  function _binomial (n, k) {
    if (typeof(n) !== 'number' && typeof(k) !== 'number') {
      throw new Error('Input must be a number.');
    }
    if (n >= 0 && k === 0) return 1;
    if (n === 0 && k > 0) return 0;
    if (arr[n] && arr[n][k] > 0) return arr[n][k];
    if (!arr[n]) arr[n] = [];

    arr[n][k] = _binomial(n - 1, k - 1) + _binomial(n - 1, k);
    return arr[n][k];
  }

  return _binomial(n, k);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.divMod"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>divMod (a, b)](#apidoc.element.numbers.basic.divMod)
- description and source-code
```javascript
divMod = function (a, b) {
  if(b <= 0) throw new Error("b cannot be zero. Undefined.");
  if (!basic.isInt(a) || !basic.isInt(b)) throw new Error("A or B are not integers.");
  return [Math.floor(a / b), a % b];
}
```
- example usage
```shell
...
  if (n === 2) return true;
  if (!basic.isInt(n) || n <= 1 || n % 2 === 0) return false;

  var s = 0;
  var d = n - 1;

  while (true) {
var dm = basic.divMod(d, 2);
var quotient = dm[0];
var remainder = dm[1];

if (remainder === 1) break;

s += 1;
d = quotient;
...
```

#### <a name="apidoc.element.numbers.basic.egcd"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>egcd (a, b)](#apidoc.element.numbers.basic.egcd)
- description and source-code
```javascript
egcd = function (a, b) {
  a = +a;
  b = +b;
  // Same as isNaN() but faster
  if (a !== a || b !== b) {
    return [NaN, NaN, NaN];
  }
  //Same as !isFinite() but faster
  if (a === Infinity || a === -Infinity || b === Infinity || b === -Infinity) {
    return [Infinity, Infinity, Infinity];
  }
  // Checks if a or b are decimals
  if ((a % 1 !== 0) || (b % 1 !== 0)) {
    throw new Error("Can only operate on integers");
  }
  var signX = (a < 0) ? -1 : 1,
      signY = (b < 0) ? -1 : 1,
      x = 0,
      y = 1,
      oldX = 1,
      oldY = 0,
      q, r, m, n;
    a = Math.abs(a);
    b = Math.abs(b);

  while(a !== 0){
    q = Math.floor(b/a);
    r = b % a;
    m = x - oldX*q;
    n = y - oldY*q;
    b = a;
    a = r;
    x = oldX;
    y = oldY;
    oldX = m;
    oldY = n;
  }
  return [b, signX*x, signY*y];
}
```
- example usage
```shell
...
 * Calculate the modular inverse of a number.
 *
 * @param {Number} Number a.
 * @param {Number} Modulo m.
 * @return {Number} if true, return number, else throw error.
 */
basic.modInverse = function (a, m) {
 var r = basic.egcd(a, m);
 if (r[0] != 1) throw new Error('No modular inverse exists');
 return r[1] % m;
};


/**
* Determine is two numbers are equal within a given margin of precision.
...
```

#### <a name="apidoc.element.numbers.basic.factorial"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>factorial (num)](#apidoc.element.numbers.basic.factorial)
- description and source-code
```javascript
factorial = function (num){
  if(typeof(num) !== 'number') throw new Error("Input must be a number.");
  if(num < 0) throw new Error("Input must not be negative.");
  var i = 2, o = 1;

  while (i <= num) {
    o *= i++;
  }

  return o;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.fallingFactorial"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>fallingFactorial (n, k)](#apidoc.element.numbers.basic.fallingFactorial)
- description and source-code
```javascript
fallingFactorial = function (n, k) {
  var i = (n-k+1), r = 1;

  if(n<0) { throw new Error("n cannot be negative."); }
  if(k>n) { throw new Error("k cannot be greater than n."); }

  while(i <= n) {
    r *= i++;
  }

  return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.gcd"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>gcd (a, b)](#apidoc.element.numbers.basic.gcd)
- description and source-code
```javascript
gcd = function (a, b) {
  var c;
  a = +a;
  b = +b;
  // Same as isNaN() but faster
  if (a !== a || b !== b) {
    return NaN;
  }
  //Same as !isFinite() but faster
  if (a === Infinity || a === -Infinity || b === Infinity || b === -Infinity) {
    return Infinity;
  }
  // Checks if a or b are decimals
  if ((a % 1 !== 0) || (b % 1 !== 0)) {
    throw new Error("Can only operate on integers");
  }
  while (b) {
    c = a % b;
    a = b;
    b = c;
  }
  return (0 < a) ? a : -a;
}
```
- example usage
```shell
...
* Calculate the least common multiple amongst two integers.
*
* @param {Number} number A.
* @param {Number} number B.
* @return {Number} least common multiple for integers A, B.
*/
basic.lcm = function (num1, num2) {
 return Math.abs(num1 * num2) / basic.gcd(num1, num2);
};

/**
* Retrieve a specified quantity of elements from an array, at random.
*
* @param {Array} set of values to select from.
* @param {Number} quantity of elements to retrieve.
...
```

#### <a name="apidoc.element.numbers.basic.isInt"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>isInt (n)](#apidoc.element.numbers.basic.isInt)
- description and source-code
```javascript
isInt = function (n) {
  return n % 1 === 0;
}
```
- example usage
```shell
...
* Calculate the divisor and modulus of two integers.
*
* @param {Number} int a.
* @param {Number} int b.
* @return {Array} [div, mod].
*/
basic.divMod = function (a, b) {
if (!basic.isInt(a) || !basic.isInt(b)) return false;
return [Math.floor(a / b), a % b];
};

/**
* Calculate:
* if b >= 1: a^b mod m.
* if b = -1: modInverse(a, m).
...
```

#### <a name="apidoc.element.numbers.basic.lcm"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>lcm (num1, num2)](#apidoc.element.numbers.basic.lcm)
- description and source-code
```javascript
lcm = function (num1, num2) {
  return Math.abs(num1 * num2) / basic.gcd(num1, num2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.max"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>max (arr)](#apidoc.element.numbers.basic.max)
- description and source-code
```javascript
max = function (arr) {
  if (!Array.isArray(arr)) {
    throw new Error("Input must be of type Array");
  }
  var max = -Infinity, val;
  for (var i = 0, len = arr.length; i < len; i++) {
    val = +arr[i];
    if (max < val) {
      max = val;
    }
    // Math.max() returns NaN if one of the elements is not a number.
    if( val !== val ){
      return NaN;
    }
  }
  return max;
}
```
- example usage
```shell
...
  }
  var max = -Infinity, val;
  for (var i = 0, len = arr.length; i < len; i++) {
    val = +arr[i];
    if (max < val) {
      max = val;
    }
    // Math.max() returns NaN if one of the elements is not a number.
    if( val !== val ){
      return NaN;
    }
  }
  return max;
};
...
```

#### <a name="apidoc.element.numbers.basic.min"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>min (arr)](#apidoc.element.numbers.basic.min)
- description and source-code
```javascript
min = function (arr) {
  if (!Array.isArray(arr)) {
    throw new Error("Input must be of type Array");
  }
  var min = +Infinity, val;
  for (var i = 0, len = arr.length; i < len; i++) {
    val = +arr[i];
    if (val < min) {
      min = val;
    }
    // Math.min() returns NaN if one of the elements is not a number.
    if( val !== val ){
      return NaN;
    }
  }
  return min;
}
```
- example usage
```shell
...
  }
  var min = +Infinity, val;
  for (var i = 0, len = arr.length; i < len; i++) {
    val = +arr[i];
    if (val < min) {
      min = val;
    }
    // Math.min() returns NaN if one of the elements is not a number.
    if( val !== val ){
      return NaN;
    }
  }
  return min;
};
...
```

#### <a name="apidoc.element.numbers.basic.modInverse"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>modInverse (a, m)](#apidoc.element.numbers.basic.modInverse)
- description and source-code
```javascript
modInverse = function (a, m) {
  var r = basic.egcd(a, m);
  if (r[0] != 1) throw new Error('No modular inverse exists');
  return r[1] % m;
}
```
- example usage
```shell
...

     a = (a * a) % m;
     b = b >> 1;
   }
   return result;
 }

 if (b === -1) return basic.modInverse(a, m);
 if (b < 1) {
   return basic.powerMod(a, Math.pow(b, -1), m);
 }
};

/**
* Calculate the extended Euclid Algorithm or extended GCD.
...
```

#### <a name="apidoc.element.numbers.basic.numbersEqual"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>numbersEqual (first, second, epsilon)](#apidoc.element.numbers.basic.numbersEqual)
- description and source-code
```javascript
numbersEqual = function (first, second, epsilon) {
  if(typeof(first) !== 'number' || typeof(second) !== 'number' || typeof(epsilon) !== 'number') throw new Error("First and Second
 must be numbers.");
  return (first - second) < epsilon && (first - second) > -epsilon;
}
```
- example usage
```shell
...
 * within a given range defined by epsilon.
 *
 * @param {Complex} complex number to check this number against.
 * @param {Number} epsilon
 * @return {boolean} true if equal within epsilon, false otherwise
 */
Complex.prototype.equals = function(complex, epsilon) {
  return basic.numbersEqual(this.re, complex.re, epsilon) &&
         basic.numbersEqual(this.im, complex.im, epsilon);
};

module.exports = Complex;

},{"../numbers":2}],6:[function(require,module,exports){
/**
...
```

#### <a name="apidoc.element.numbers.basic.permutation"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>permutation (n, k)](#apidoc.element.numbers.basic.permutation)
- description and source-code
```javascript
permutation = function (n, k) {
    if (n <= 0) {
        throw new Error("n cannot be less than or equal to 0.");
    }
    if (n < k) {
        throw new Error("k cannot be greater than k.");
    }
    var binomial = basic.binomial(n, k);
    var permutation = binomial * basic.factorial(k);
    return permutation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.powerMod"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>powerMod (a, b, m)](#apidoc.element.numbers.basic.powerMod)
- description and source-code
```javascript
powerMod = function (a, b, m) {
  if(typeof(a) !== 'number' || typeof(b) !== 'number' || typeof(m) !== 'number') throw new Error("Inputs must be numbers.");
  // If b < -1 should be a small number, this method should work for now.
  if (b < -1) return Math.pow(a, b) % m;
  if (b === 0) return 1 % m;
  if (b >= 1) {
    var result = 1;
    while (b > 0) {
      if ((b % 2) === 1) {
        result = (result * a) % m;
      }

      a = (a * a) % m;
      b = b >> 1;
    }
    return result;
  }

  if (b === -1) return basic.modInverse(a, m);
  if (b < 1) {
    return basic.powerMod(a, Math.pow(b, -1), m);
  }
}
```
- example usage
```shell
...
     b = b >> 1;
   }
   return result;
 }

 if (b === -1) return basic.modInverse(a, m);
 if (b < 1) {
   return basic.powerMod(a, Math.pow(b, -1), m);
 }
};

/**
* Calculate the extended Euclid Algorithm or extended GCD.
*
* @param {Number} int a.
...
```

#### <a name="apidoc.element.numbers.basic.product"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>product (arr)](#apidoc.element.numbers.basic.product)
- description and source-code
```javascript
product = function (arr) {
  if (Object.prototype.toString.call(arr) === '[object Array]') {
    var total = arr[0];
    if (typeof(total) !== 'number') {
      throw new Error('All elements in array must be numbers');
    }
    for (var i = 1, length = arr.length; i < length; i++) {
      if (typeof(arr[i]) === 'number') {
        total = total * arr[i];
      } else {
        throw new Error('All elements in array must be numbers');
      }
    }
    return total;
  } else {
    throw new Error('Input must be of type Array');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.random"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>random (arr, quant, allowDuplicates)](#apidoc.element.numbers.basic.random)
- description and source-code
```javascript
random = function (arr, quant, allowDuplicates) {
  if (arr.length === 0){
    throw new Error('Empty array');
  } else if (quant > arr.length  && !allowDuplicates){
    throw new Error('Quantity requested exceeds size of array');
  }

  if (allowDuplicates === true) {
    var result = [], i;
    for (i = 0; i < quant; i++) {
      result[i] = arr[Math.floor(Math.random() * arr.length)];
    }
    return result;
  } else {
    return basic.shuffle(arr).slice(0, quant);
  }
}
```
- example usage
```shell
...
  } else if (quant > arr.length  && !allowDuplicates){
    throw new Error('Quantity requested exceeds size of array');
  }

  if (allowDuplicates === true) {
    var result = [], i;
    for (i = 0; i < quant; i++) {
      result[i] = arr[Math.floor(Math.random() * arr.length)];
    }
    return result;
  } else {
    return basic.shuffle(arr).slice(0, quant);
  }
};
...
```

#### <a name="apidoc.element.numbers.basic.range"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>range (start, stop, step)](#apidoc.element.numbers.basic.range)
- description and source-code
```javascript
range = function (start, stop, step) {
  var array, i = 0, len;

  if (arguments.length <= 1) {
    stop = start || 0;
    start = 0;
  }

  step = step || 1;

  if (stop < start) {
    step = 0 - Math.abs(step);
  }

  len = Math.max(Math.ceil((stop - start) / step) + 1, 0);

  array = new Array(len);

  while (i < len) {
    array[i++] = start;
    start += step;
  }

  return array;
}
```
- example usage
```shell
...
 * Create a function to calculate the exponential regression of a dataset.
 *
 * @param {Array} set of values.
 * @return {Function} function to accept X values and return corresponding regression Y values.
 */
statistic.exponentialRegression = function (arrY) {
var n = arrY.length;
var arrX = basic.range(1,n);

var xSum = basic.sum(arrX);
var ySum = basic.sum(arrY);
var yMean = statistic.mean(arrY);
var yLog = arrY.map(function (d) { return Math.log(d); });
var xSquared = arrX.map(function (d) { return d * d; });
var xSquaredSum = basic.sum(xSquared);
...
```

#### <a name="apidoc.element.numbers.basic.shuffle"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>shuffle (array)](#apidoc.element.numbers.basic.shuffle)
- description and source-code
```javascript
shuffle = function (array) {
  var m = array.length, t, i;

  while (m) {
    i = Math.floor(Math.random() * m--);

    t = array[m];
    array[m] = array[i];
    array[i] = t;
  }

  return array;
}
```
- example usage
```shell
...
 if (allowDuplicates === true) {
   var result = [], i;
   for (i = 0; i < quant; i++) {
     result[i] = arr[Math.floor(Math.random() * arr.length)];
   }
   return result;
 } else {
   return basic.shuffle(arr).slice(0, quant);
 }
};

/**
* Shuffle an array, in place.
*
* @param {Array} array to be shuffled.
...
```

#### <a name="apidoc.element.numbers.basic.square"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>square (num)](#apidoc.element.numbers.basic.square)
- description and source-code
```javascript
square = function (num) {
  if (typeof(num) !== 'number') {
    throw new Error('Input must be a number.');
  } else {
    return num * num;
  }

}
```
- example usage
```shell
...
 *
 * @param {Array} Source data.
 * @param {Array} Regression data.
 * @return {Number} A number between 0 and 1.0 that represents how well the regression line fits the data.
 */
statistic.rSquared = function (source, regression) {
var residualSumOfSquares = basic.sum(source.map(function (d,i) {
  return basic.square(d - regression[i]);
}));

var totalSumOfSquares = basic.sum(source.map(function (d) {
  return basic.square(d - statistic.mean(source));
}));

return 1 - (residualSumOfSquares / totalSumOfSquares);
...
```

#### <a name="apidoc.element.numbers.basic.subtraction"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>subtraction (arr)](#apidoc.element.numbers.basic.subtraction)
- description and source-code
```javascript
subtraction = function (arr) {
  if (Object.prototype.toString.call(arr) === '[object Array]') {
    var total = arr[0];
    if (typeof(total) !== 'number') {
      throw new Error('All elements in array must be numbers');
    }
    for (var i = 1, length = arr.length; i < length; i++) {
      if (typeof(arr[i]) === 'number') {
        total -= arr[i];
      } else {
        throw new Error('All elements in array must be numbers');
      }
    }
    return total;
  } else {
    throw new Error('Input must be of type Array');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.basic.sum"></a>[function <span class="apidocSignatureSpan">numbers.basic.</span>sum (arr)](#apidoc.element.numbers.basic.sum)
- description and source-code
```javascript
sum = function (arr) {
  if (Object.prototype.toString.call(arr) === '[object Array]') {
    var total = 0;
    for (var i = 0 ; i < arr.length ; i++) {
      if (typeof(arr[i]) === 'number') {
        total = total + arr[i];
      } else {
        throw new Error('All elements in array must be numbers');
      }
    }
    return total;
  } else {
    throw new Error('Input must be of type Array');
  }
}
```
- example usage
```shell
...
* Calculate the mean value of a set of numbers in array.
*
* @param {Array} set of values.
* @return {Number} mean value.
*/
statistic.mean = function (arr) {
 var count = arr.length;
 var sum = basic.sum(arr);
 return sum / count;
};

/**
* Calculate the median value of a set of numbers in array.
*
* @param {Array} set of values.
...
```



# <a name="apidoc.module.numbers.calculus"></a>[module numbers.calculus](#apidoc.module.numbers.calculus)

#### <a name="apidoc.element.numbers.calculus.LanczosGamma"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>LanczosGamma (num)](#apidoc.element.numbers.calculus.LanczosGamma)
- description and source-code
```javascript
LanczosGamma = function (num) {
  var p = [
    0.99999999999980993, 676.5203681218851, -1259.1392167224028,
    771.32342877765313, -176.61502916214059, 12.507343278686905,
    -0.13857109526572012, 9.9843695780195716e-6, 1.5056327351493116e-7
  ];

  var i;
  var g = 7;

  if(num < 0.5) return Math.PI / (Math.sin(Math.PI * num) * calculus.LanczosGamma(1 - num));

  num -= 1;

  var a = p[0];
  var t = num + g + 0.5;

  for (i = 1; i < p.length; i++) {
    a += p[i] / (num + i);
  }

  return Math.sqrt(2 * Math.PI) * Math.pow(t, num + 0.5) * Math.exp(-t) * a;
}
```
- example usage
```shell
...
  771.32342877765313, -176.61502916214059, 12.507343278686905,
  -0.13857109526572012, 9.9843695780195716e-6, 1.5056327351493116e-7
];

var i;
var g = 7;

if(num < 0.5) return Math.PI / (Math.sin(Math.PI * num) * calculus.LanczosGamma(1 - num));

num -= 1;

var a = p[0];
var t = num + g + 0.5;

for (i = 1; i < p.length; i++) {
...
```

#### <a name="apidoc.element.numbers.calculus.MonteCarlo"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>MonteCarlo (func, N)](#apidoc.element.numbers.calculus.MonteCarlo)
- description and source-code
```javascript
MonteCarlo = function (func, N) {
  //takes an arbitrary number of arguments after N
  //all of the arguments must be arrays which are intervals
  if (arguments.length < 2) {
    throw new Error('Please enter at least one interval.');
  } else if (N <= 0) {
    throw new Error('Please use a positive integer for N.');
  }
  var L = [];
  N = Math.ceil(N);
  for (var i=2; i<arguments.length; i++) {L.push(arguments[i]);}

  var coeff = L.map(function(l) { //subtract the endpoints
    return l[1] - l[0];
  }).reduce(function(a,b) { //multiply each endpoint difference
    return a*b;
  }) / N;

  var fvals = numbers.matrix.transpose(L.map(function(l) {
    //generate an array of arrays, each nested array being N
    //random values in each interval - N-by-3 array, and then
    //transpose it to get a 3-by-N array
    return numbers.statistic.randomSample(l[0],l[1],N);
  })).map(function(l) {
    //evaluate func at each set of points
    return func.apply(null, [ l[0],l[1],l[2] ]);
  });

  return coeff * fvals.reduce(function(a,b) {return a+b;});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.calculus.Riemann"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>Riemann (func, start, finish, n, sampler)](#apidoc.element.numbers.calculus.Riemann)
- description and source-code
```javascript
Riemann = function (func, start, finish, n, sampler) {
  var inc = (finish - start) / n;
  var totalHeight = 0;
  var i;

  if (typeof sampler === 'function') {
    for (i = start; i < finish; i += inc) {
      totalHeight += func(sampler(i, i + inc));
    }
  } else {
    for (i = start; i < finish; i += inc) {
      totalHeight += func(i);
    }
  }

  return totalHeight * inc;
}
```
- example usage
```shell
...
'''

For example, if we wanted to estimate the integral of sin(x) from -2 to 4, we could:

Use Riemann integrals (with 200 subdivisions)

'''javascript
numbers.calculus.Riemann(Math.sin, -2, 4, 200);
'''

Or use adaptive simpson quadrature (with epsilon .0001)

'''javascript
numbers.calculus.adaptiveSimpson(Math.sin, -2, 4, .0001);
'''
...
```

#### <a name="apidoc.element.numbers.calculus.StirlingGamma"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>StirlingGamma (num)](#apidoc.element.numbers.calculus.StirlingGamma)
- description and source-code
```javascript
StirlingGamma = function (num) {
  return Math.sqrt(2 * Math.PI / num) * Math.pow((num / Math.E), num);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.calculus.adaptiveSimpson"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>adaptiveSimpson (func, a, b, eps)](#apidoc.element.numbers.calculus.adaptiveSimpson)
- description and source-code
```javascript
adaptiveSimpson = function (func, a, b, eps) {
  eps = (typeof eps === 'undefined') ? numbers.EPSILON : eps;

  return SimpsonRecursive(func, a, b, SimpsonDef(func, a, b), eps);
}
```
- example usage
```shell
...
'''javascript
numbers.calculus.Riemann(Math.sin, -2, 4, 200);
'''

Or use adaptive simpson quadrature (with epsilon .0001)

'''javascript
numbers.calculus.adaptiveSimpson(Math.sin, -2, 4, .0001);
'''

User-defined functions can be used too:

'''
var myFunc = function(x) {
return 2*Math.pow(x,2) + 1;
...
```

#### <a name="apidoc.element.numbers.calculus.limit"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>limit (func, point, approach)](#apidoc.element.numbers.calculus.limit)
- description and source-code
```javascript
limit = function (func, point, approach) {
  if (approach === 'left') {
    return func(point - 1e-15);
  } else if (approach === 'right') {
    return func(point + 1e-15);
  } else if (approach === 'middle') {
    return (calculus.limit(func, point, 'left') + calculus.limit(func, point, 'right')) / 2;
  } else {
    throw new Error('Approach not provided');
  }
}
```
- example usage
```shell
...
*/
calculus.limit = function (func, point, approach) {
 if (approach === 'left') {
   return func(point - 1e-15);
 } else if (approach === 'right') {
   return func(point + 1e-15);
 } else if (approach === 'middle') {
   return (calculus.limit(func, point, 'left') + calculus.limit(func, point, 'right')) / 2;
 } else {
   throw new Error('Approach not provided');
 }
};

/**
* Calculate Stirling approximation gamma.
...
```

#### <a name="apidoc.element.numbers.calculus.pointDiff"></a>[function <span class="apidocSignatureSpan">numbers.calculus.</span>pointDiff (func, point)](#apidoc.element.numbers.calculus.pointDiff)
- description and source-code
```javascript
pointDiff = function (func, point) {
  var a = func(point - 0.001);
  var b = func(point + 0.001);

  return (b - a) / (0.002);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.complex"></a>[module numbers.complex](#apidoc.module.numbers.complex)

#### <a name="apidoc.element.numbers.complex.complex"></a>[function <span class="apidocSignatureSpan">numbers.</span>complex (re, im)](#apidoc.element.numbers.complex.complex)
- description and source-code
```javascript
complex = function (re, im) {
  this.re = re;
  this.im = im;
  this.r  = this.magnitude();
  this.t  = this.phase(); // theta = t = arg(z)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.complex.prototype"></a>[module numbers.complex.prototype](#apidoc.module.numbers.complex.prototype)

#### <a name="apidoc.element.numbers.complex.prototype.add"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>add (addend)](#apidoc.element.numbers.complex.prototype.add)
- description and source-code
```javascript
add = function (addend) {
  return new Complex(this.re + addend.re, this.im + addend.im);
}
```
- example usage
```shell
...
*
* @return {Complex} the cosine of this complex number.
*/
Complex.prototype.cos = function() {
 var E = new Complex(Math.E, 0);
 var i = new Complex(0, 1);
 var negativeI = new Complex(0, -1);
 var numerator = E.complexPow(i.multiply(this)).add(E.complexPow(negativeI.multiply(this)));

 return numerator.divide(new Complex(2, 0));
};

/**
* Returns the tangent of this complex number.
*
...
```

#### <a name="apidoc.element.numbers.complex.prototype.complexPow"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>complexPow (complexN)](#apidoc.element.numbers.complex.prototype.complexPow)
- description and source-code
```javascript
complexPow = function (complexN) {
  var realSqPlusImSq =  Math.pow(this.re, 2) + Math.pow(this.im, 2);
  var multiplier = Math.pow(realSqPlusImSq, complexN.re / 2) * Math.pow(Math.E, -complexN.im * this.phase());
  var theta = complexN.re * this.phase() + 0.5 * complexN.im * Math.log(realSqPlusImSq);

  return new Complex(multiplier * Math.cos(theta), multiplier * Math.sin(theta));
}
```
- example usage
```shell
...
*
* @return {Complex} the sine of this complex number.
*/
Complex.prototype.sin = function() {
 var E = new Complex(Math.E, 0);
 var i = new Complex(0, 1);
 var negativeI = new Complex(0, -1);
 var numerator = E.complexPow(i.multiply(this)).subtract(E.complexPow(negativeI.multiply(this)));

 return numerator.divide(new Complex(0, 2));
};

/**
* Returns the cosine of this complex number.
*
...
```

#### <a name="apidoc.element.numbers.complex.prototype.conjugate"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>conjugate ()](#apidoc.element.numbers.complex.prototype.conjugate)
- description and source-code
```javascript
conjugate = function () {
  return new Complex(this.re, -1 * this.im);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.complex.prototype.cos"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>cos ()](#apidoc.element.numbers.complex.prototype.cos)
- description and source-code
```javascript
cos = function () {
  var E = new Complex(Math.E, 0);
  var i = new Complex(0, 1);
  var negativeI = new Complex(0, -1);
  var numerator = E.complexPow(i.multiply(this)).add(E.complexPow(negativeI.multiply(this)));

  return numerator.divide(new Complex(2, 0));
}
```
- example usage
```shell
...
*
* @param {number} power to raise this complex number to.
* @return {Complex} the nth power of this complex number.
*/
Complex.prototype.pow = function(n) {
 var constant = Math.pow(this.magnitude(), n);

 return new Complex(constant * Math.cos(n * this.phase()), constant * Math.sin(n * this.phase()));
};

/**
* Raises this complex number to given complex power.
*
* @param complexN the complex number to raise this complex number to.
* @return {Complex} this complex number raised to the given complex number.
...
```

#### <a name="apidoc.element.numbers.complex.prototype.divide"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>divide (divisor)](#apidoc.element.numbers.complex.prototype.divide)
- description and source-code
```javascript
divide = function (divisor) {
  var denominator = divisor.re * divisor.re + divisor.im * divisor.im;
  var re = (this.re * divisor.re + this.im * divisor.im) / denominator;
  var im = (this.im * divisor.re - this.re * divisor.im) / denominator;

  return new Complex(re,im);
}
```
- example usage
```shell
...
*/
Complex.prototype.sin = function() {
 var E = new Complex(Math.E, 0);
 var i = new Complex(0, 1);
 var negativeI = new Complex(0, -1);
 var numerator = E.complexPow(i.multiply(this)).subtract(E.complexPow(negativeI.multiply(this)));

 return numerator.divide(new Complex(0, 2));
};

/**
* Returns the cosine of this complex number.
*
* @return {Complex} the cosine of this complex number.
*/
...
```

#### <a name="apidoc.element.numbers.complex.prototype.equals"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>equals (complex, epsilon)](#apidoc.element.numbers.complex.prototype.equals)
- description and source-code
```javascript
equals = function (complex, epsilon) {
  return basic.numbersEqual(this.re, complex.re, epsilon) &&
         basic.numbersEqual(this.im, complex.im, epsilon);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.complex.prototype.magnitude"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>magnitude ()](#apidoc.element.numbers.complex.prototype.magnitude)
- description and source-code
```javascript
magnitude = function () {
  return Math.sqrt(this.re * this.re + this.im * this.im);
}
```
- example usage
```shell
...

var numbers = require('../numbers');
var basic = numbers.basic;

var Complex = function (re, im) {
 this.re = re;
 this.im = im;
 this.r  = this.magnitude();
 this.t  = this.phase(); // theta = t = arg(z)
};

/**
* Add a complex number to this one.
*
* @param {Complex} Number to add.
...
```

#### <a name="apidoc.element.numbers.complex.prototype.multiply"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>multiply (multiplier)](#apidoc.element.numbers.complex.prototype.multiply)
- description and source-code
```javascript
multiply = function (multiplier) {
  var re = this.re * multiplier.re - this.im * multiplier.im;
  var im = this.im * multiplier.re + this.re * multiplier.im;

  return new Complex(re, im);
}
```
- example usage
```shell
...
*
* @return {Complex} the sine of this complex number.
*/
Complex.prototype.sin = function() {
 var E = new Complex(Math.E, 0);
 var i = new Complex(0, 1);
 var negativeI = new Complex(0, -1);
 var numerator = E.complexPow(i.multiply(this)).subtract(E.complexPow(negativeI.multiply(this)));

 return numerator.divide(new Complex(0, 2));
};

/**
* Returns the cosine of this complex number.
*
...
```

#### <a name="apidoc.element.numbers.complex.prototype.phase"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>phase ()](#apidoc.element.numbers.complex.prototype.phase)
- description and source-code
```javascript
phase = function () {
  return Math.atan2(this.im, this.re);
}
```
- example usage
```shell
...
var numbers = require('../numbers');
var basic = numbers.basic;

var Complex = function (re, im) {
 this.re = re;
 this.im = im;
 this.r  = this.magnitude();
 this.t  = this.phase(); // theta = t = arg(z)
};

/**
* Add a complex number to this one.
*
* @param {Complex} Number to add.
* @return {Complex} New complex number (sum).
...
```

#### <a name="apidoc.element.numbers.complex.prototype.pow"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>pow (n)](#apidoc.element.numbers.complex.prototype.pow)
- description and source-code
```javascript
pow = function (n) {
  var constant = Math.pow(this.magnitude(), n);

  return new Complex(constant * Math.cos(n * this.phase()), constant * Math.sin(n * this.phase()));
}
```
- example usage
```shell
...
numbers.calculus.adaptiveSimpson(Math.sin, -2, 4, .0001);
'''

User-defined functions can be used too:

'''
var myFunc = function(x) {
  return 2*Math.pow(x,2) + 1;
}

numbers.calculus.Riemann(myFunc, -2, 4, 200);
numbers.calculus.adaptiveSimpson(myFunc, -2, 4, .0001);
'''

Now say we wanted to run some matrix calculations:
...
```

#### <a name="apidoc.element.numbers.complex.prototype.roots"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>roots (n)](#apidoc.element.numbers.complex.prototype.roots)
- description and source-code
```javascript
roots = function (n) {
  var result = new Array(n);

  for(var i = 0; i < n; i++) {
    var theta = (this.phase() + 2*Math.PI*i) / n;
    var radiusConstant = Math.pow(this.magnitude(), 1 / n);

    result[i] = (new Complex(radiusConstant * Math.cos(theta), radiusConstant * Math.sin(theta)));
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.complex.prototype.sin"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>sin ()](#apidoc.element.numbers.complex.prototype.sin)
- description and source-code
```javascript
sin = function () {
  var E = new Complex(Math.E, 0);
  var i = new Complex(0, 1);
  var negativeI = new Complex(0, -1);
  var numerator = E.complexPow(i.multiply(this)).subtract(E.complexPow(negativeI.multiply(this)));

  return numerator.divide(new Complex(0, 2));
}
```
- example usage
```shell
...
  771.32342877765313, -176.61502916214059, 12.507343278686905,
  -0.13857109526572012, 9.9843695780195716e-6, 1.5056327351493116e-7
];

var i;
var g = 7;

if(num < 0.5) return Math.PI / (Math.sin(Math.PI * num) * calculus.LanczosGamma(1 - num));

num -= 1;

var a = p[0];
var t = num + g + 0.5;

for (i = 1; i < p.length; i++) {
...
```

#### <a name="apidoc.element.numbers.complex.prototype.subtract"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>subtract (subtrahend)](#apidoc.element.numbers.complex.prototype.subtract)
- description and source-code
```javascript
subtract = function (subtrahend) {
  return new Complex(this.re - subtrahend.re, this.im - subtrahend.im);
}
```
- example usage
```shell
...
*
* @return {Complex} the sine of this complex number.
*/
Complex.prototype.sin = function() {
 var E = new Complex(Math.E, 0);
 var i = new Complex(0, 1);
 var negativeI = new Complex(0, -1);
 var numerator = E.complexPow(i.multiply(this)).subtract(E.complexPow(negativeI.multiply(this)));

 return numerator.divide(new Complex(0, 2));
};

/**
* Returns the cosine of this complex number.
*
...
```

#### <a name="apidoc.element.numbers.complex.prototype.tan"></a>[function <span class="apidocSignatureSpan">numbers.complex.prototype.</span>tan ()](#apidoc.element.numbers.complex.prototype.tan)
- description and source-code
```javascript
tan = function () {
  return this.sin().divide(this.cos());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.dsp"></a>[module numbers.dsp](#apidoc.module.numbers.dsp)

#### <a name="apidoc.element.numbers.dsp.fft"></a>[function <span class="apidocSignatureSpan">numbers.dsp.</span>fft (x)](#apidoc.element.numbers.dsp.fft)
- description and source-code
```javascript
fft = function (x) {
  var N = x.length;

  if (N <= 1) {
    return [new Complex(x[0], 0)];
  }

  if (Math.log(N) / Math.LN2 % 1 !== 0) {
    throw new Error ('Array length must be integer power of 2');
  }

  var even = dsp.fft(dsp.segment(x, 0, 2));
  var odd = dsp.fft(dsp.segment(x, 1, 2));
  var res = [], Nby2 = N / 2;

  for (var k = 0; k < N; k++) {
    var tmpPhase = -2 * Math.PI * k / N;
    var phasor = new Complex(Math.cos(tmpPhase), Math.sin(tmpPhase));
    if (k < Nby2) {
      res[k] = even[k].add(phasor.multiply(odd[k]));
    } else {
      res[k] = even[k - Nby2].subtract(phasor.multiply(odd[k - Nby2]));
    }
  }

  return res;
}
```
- example usage
```shell
...
  return [new Complex(x[0], 0)];
}

if (Math.log(N) / Math.LN2 % 1 !== 0) {
  throw new Error ('Array length must be integer power of 2');
}

var even = dsp.fft(dsp.segment(x, 0, 2));
var odd = dsp.fft(dsp.segment(x, 1, 2));
var res = [], Nby2 = N / 2;

for (var k = 0; k < N; k++) {
  var tmpPhase = -2 * Math.PI * k / N;
  var phasor = new Complex(Math.cos(tmpPhase), Math.sin(tmpPhase));
  if (k < Nby2) {
...
```

#### <a name="apidoc.element.numbers.dsp.segment"></a>[function <span class="apidocSignatureSpan">numbers.dsp.</span>segment (arr, start, step)](#apidoc.element.numbers.dsp.segment)
- description and source-code
```javascript
segment = function (arr, start, step) {
  var result = [];

  for (var i = start; i < arr.length; i += step) {
    result.push(arr[i]);
  }

  return result;
}
```
- example usage
```shell
...
  return [new Complex(x[0], 0)];
}

if (Math.log(N) / Math.LN2 % 1 !== 0) {
  throw new Error ('Array length must be integer power of 2');
}

var even = dsp.fft(dsp.segment(x, 0, 2));
var odd = dsp.fft(dsp.segment(x, 1, 2));
var res = [], Nby2 = N / 2;

for (var k = 0; k < N; k++) {
  var tmpPhase = -2 * Math.PI * k / N;
  var phasor = new Complex(Math.cos(tmpPhase), Math.sin(tmpPhase));
  if (k < Nby2) {
...
```



# <a name="apidoc.module.numbers.generate"></a>[module numbers.generate](#apidoc.module.numbers.generate)

#### <a name="apidoc.element.numbers.generate.collatz"></a>[function <span class="apidocSignatureSpan">numbers.generate.</span>collatz (n, result)](#apidoc.element.numbers.generate.collatz)
- description and source-code
```javascript
collatz = function (n, result) {
  result.push(n);

  if (n === 1) {
    return;
  } else if (n % 2 === 0) {
    generate.collatz(n / 2, result);
  } else {
    generate.collatz(3 * n + 1, result);
  }
}
```
- example usage
```shell
...
 */
generate.collatz = function (n, result) {
  result.push(n);

  if (n === 1) {
    return;
  } else if (n % 2 === 0) {
    generate.collatz(n / 2, result);
  } else {
    generate.collatz(3 * n + 1, result);
  }
};

},{}],8:[function(require,module,exports){
/**
...
```

#### <a name="apidoc.element.numbers.generate.fibonacci"></a>[function <span class="apidocSignatureSpan">numbers.generate.</span>fibonacci (n)](#apidoc.element.numbers.generate.fibonacci)
- description and source-code
```javascript
fibonacci = function (n) {
  // Adapted from
  // http://bosker.wordpress.com/2011/04/29/the-worst-algorithm-in-the-world/

  var bitSystem = function(n) {
    var bit, bits = [];

    while (n > 0) {
      bit = (n < 2) ? n : n % 2;
      n = Math.floor(n / 2);
      bits.push(bit);
    }

    return bits.reverse();
  };

  var a = 1;
  var b = 0;
  var c = 1;
  var system = bitSystem(n);
  var temp;

  for (var i = 0; i < system.length; i++) {
    var bit = system[i];
    if (bit) {
      temp = [(a + c) * b, (b * b) + (c * c)];
      a = temp[0];
      b = temp[1];
    } else {
      temp = [(a * a) + (b * b), (a + c) * b];
      a = temp[0];
      b = temp[1];
    }

    c = a + b;
  }

  return b;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.matrix"></a>[module numbers.matrix](#apidoc.module.numbers.matrix)

#### <a name="apidoc.element.numbers.matrix.GaussJordanEliminate"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>GaussJordanEliminate (m, epsilon)](#apidoc.element.numbers.matrix.GaussJordanEliminate)
- description and source-code
```javascript
GaussJordanEliminate = function (m, epsilon) {
  // Translated from:
  // http://elonen.iki.fi/code/misc-notes/python-gaussj/index.html
  var eps = (typeof epsilon == 'undefined') ? 1e-10 : epsilon;

  var h = m.length;
  var w = m[0].length;
  var y = -1;
  var y2, x, c;

  while (++y < h) {
    // Pivot.
    var maxrow = y;
    y2 = y;
    while (++y2 < h) {
      if(Math.abs(m[y2][y]) > Math.abs(m[maxrow][y]))
        maxrow = y2;
    }
    var tmp = m[y];
    m[y] = m[maxrow];
    m[maxrow] = tmp;

    // Singular
    if(Math.abs(m[y][y]) <= eps) {
      return m;
    }

    // Eliminate column
    y2 = y;
    while (++y2 < h) {
      c = m[y2][y] / m[y][y];
      x = y - 1;
      while (++x < w) {
        m[y2][x] -= m[y][x] * c;
      }
    }
  }

  // Backsubstitute.
  y = h;
  while (--y >= 0) {
    c = m[y][y];
    y2 = -1;
    while (++y2 < y) {
      x = w;
      while (--x >= y) {
        m[y2][x] -=  m[y][x] * m[y2][y] / c;
      }
    }
    m[y][y] /= c;

    // Normalize row
    x = h - 1;
    while (++x < w) {
      m[y][x] /= c;
    }
  }

  return m;
}
```
- example usage
```shell
...
* Alias to Gauss-Jordan Elimination
*
* @param {Array} matrix.
* @param {Number} epsilon.
* @return {Array} RREF matrix.
*/
matrix.rowReduce = function(m, epsilon) {
 return matrix.GaussJordanEliminate(m, epsilon);
};

/**
* nxn matrix inversion
*
* @param {Array} matrix.
* @return {Array} inverted matrix.
...
```

#### <a name="apidoc.element.numbers.matrix._check2DVector"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>_check2DVector (point)](#apidoc.element.numbers.matrix._check2DVector)
- description and source-code
```javascript
_check2DVector = function (point) {
  if (point.length !== 2) {
    throw new Error(ERROR_VECTOR_NOT_2D);
  }
}
```
- example usage
```shell
...
 *
 * @param {Array} point.
 * @param {Number} degree.
 * @param {String} direction - clockwise or counterclockwise.
 * @return {Array} vector.
 */
matrix.rotate = function (point, degree, direction) {
matrix._check2DVector(point);

var negate = direction === 'clockwise' ? -1 : 1;
var radians = degree * (Math.PI / 180);

var transformation = [
  [Math.cos(radians), -1 * negate * Math.sin(radians)],
  [negate * Math.sin(radians), Math.cos(radians)]
...
```

#### <a name="apidoc.element.numbers.matrix.addition"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>addition (arrA, arrB)](#apidoc.element.numbers.matrix.addition)
- description and source-code
```javascript
addition = function (arrA, arrB) {
  if (arrA.length !== arrB.length || arrA[0].length !== arrB[0].length) {
    throw new Error('Matrix mismatch');
  }

  var result = new Array(arrA.length),
      i;

  if (!arrA[0].length) {
    // The arrays are vectors.
    for (i = 0; i < arrA.length; i++) {
      result[i] = arrA[i] + arrB[i];
    }
  } else {
    for (i = 0; i < arrA.length; i++) {
        result[i] = new Array(arrA[i].length);

        for (var j = 0; j < arrA[i].length; j++) {
          result[i][j] = arrA[i][j] + arrB[i][j];
        }
    }
  }

  return result;
}
```
- example usage
```shell
...

We can add two matrices

'''javascript
var array1 = [0, 1, 2];
var array2 = [3, 4, 5];

numbers.matrix.addition(array1, array2);
'''

We can transpose a matrix

'''javascript
numbers.matrix.transpose(array);
'''
...
```

#### <a name="apidoc.element.numbers.matrix.affine"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>affine (point, tx, ty)](#apidoc.element.numbers.matrix.affine)
- description and source-code
```javascript
affine = function (point, tx, ty) {
  matrix._check2DVector(point);
  var transformation = [
    [1, 0, tx],
    [0, 1, ty],
    [0, 0, 1 ]
  ];

  var newpoint = [
    [point[0][0]],
    [point[1][0]],
    [1]
  ];

  var transformed = matrix.multiply(transformation, newpoint);

  return [
    [transformed[0][0]],
    [transformed[1][0]]
  ];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.deepCopy"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>deepCopy (arr)](#apidoc.element.numbers.matrix.deepCopy)
- description and source-code
```javascript
deepCopy = function (arr) {
  if (!Array.isArray(arr)) {
    throw new Error('Input must be a matrix.');
  } else if (arr[0][0] === undefined) {
    throw new Error('Input cannot be a vector.');
  }
  var result = new Array(arr.length);

  for (var i = 0; i < arr.length; i++) {
    result[i] = arr[i].slice();
  }

  return result;
}
```
- example usage
```shell
...
matrix.lupDecomposition = function(arr) {
if (!matrix.isSquare(arr)) {
  throw new Error(ERROR_MATRIX_NOT_SQUARE);
}

var size = arr.length;

var LU = matrix.deepCopy(arr);
var P = matrix.transpose(matrix.identity(size));
var currentRow;
var currentColumn = new Array(size);

this.getL = function(a) {
  var m = a[0].length;
  var L = matrix.identity(m);
...
```

#### <a name="apidoc.element.numbers.matrix.determinant"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>determinant (m)](#apidoc.element.numbers.matrix.determinant)
- description and source-code
```javascript
determinant = function (m) {
  var numRow = m.length;
  var numCol = m[0].length;
  var det = 0;
  var row, col;
  var diagLeft, diagRight;

  if (!matrix.isSquare(m)) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  if (numRow === 1) {
    return m[0][0];
  } else if (numRow === 2) {
    return m[0][0] * m[1][1] - m[0][1] * m[1][0];
  }

  for (col = 0; col < numCol; col++) {
    diagLeft = m[0][col];
    diagRight = m[0][col];

    for( row=1; row < numRow; row++ ) {
      diagRight *= m[row][(((col + row) % numCol) + numCol) % numCol];
      diagLeft *= m[row][(((col - row) % numCol) + numCol) % numCol];
    }

    det += diagRight - diagLeft;
  }

  return det;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.dotproduct"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>dotproduct (vectorA, vectorB)](#apidoc.element.numbers.matrix.dotproduct)
- description and source-code
```javascript
dotproduct = function (vectorA, vectorB) {
  if (vectorA.length !== vectorB.length) {
    throw new Error("Vector mismatch");
  }

  var result = 0;
  for (var i = 0; i < vectorA.length; i++) {
    result += vectorA[i] * vectorB[i];
  }
  return result;
}
```
- example usage
```shell
...
   result[x] = new Array(arrB[0].length);
 }

 var arrB_T = matrix.transpose(arrB);

 for (var i = 0; i < result.length; i++) {
   for (var j = 0; j < result[i].length; j++) {
     result[i][j] = matrix.dotproduct(arrA[i],arrB_T[j]);
   }
 }
 return result;
};

/**
* Evaluate determinate of matrix.  Expect speed
...
```

#### <a name="apidoc.element.numbers.matrix.getCol"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>getCol (M, n)](#apidoc.element.numbers.matrix.getCol)
- description and source-code
```javascript
getCol = function (M, n) {
  var result = new Array(M.length);
  if (n < 0) {
    throw new Error('The specified column must be a positive integer.');
  } else if (n >= M[0].length) {
    throw new Error('The specified column must be between 0 and the number of columns - 1.');
  }
  for (var i=0; i<M.length; i++) {
    result[i] = M[i][n];
  }
  return result;
}
```
- example usage
```shell
...
 }
 for (var i=0; i<L.length; i++) {
   if (L[i] < 0) {
     throw new Error('The desired order of the columns must be positive integers.');
   } else if (L[i] >= L.length) {
     throw new Error('The desired order of the columns must start at 0 and end at the number of columns - 1.');
   } else {
     result.push(matrix.getCol(M, L[i]) );
   }
 }
 return matrix.transpose(result);
};

/**
* Reverse the rows of a matrix.
...
```

#### <a name="apidoc.element.numbers.matrix.identity"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>identity (n)](#apidoc.element.numbers.matrix.identity)
- description and source-code
```javascript
identity = function (n) {
  var result = new Array(n);

  for (var i = 0; i < n ; i++) {
    result[i] = new Array(n);
    for (var j = 0; j < n; j++) {
      result[i][j] = (i === j) ? 1 : 0;
    }
  }

  return result;
}
```
- example usage
```shell
...
if (!matrix.isSquare(arr)) {
  throw new Error(ERROR_MATRIX_NOT_SQUARE);
}

var size = arr.length;

var LU = matrix.deepCopy(arr);
var P = matrix.transpose(matrix.identity(size));
var currentRow;
var currentColumn = new Array(size);

this.getL = function(a) {
  var m = a[0].length;
  var L = matrix.identity(m);
...
```

#### <a name="apidoc.element.numbers.matrix.inverse"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>inverse (m)](#apidoc.element.numbers.matrix.inverse)
- description and source-code
```javascript
inverse = function (m) {
  if (!matrix.isSquare(m)) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  var n = m.length,
      identity = matrix.identity(n),
      i;

  // AI
  for(i=0; i<n; i++) {
    m[i] = m[i].concat(identity[i]);
  }

  // inv(IA)
  m = matrix.GaussJordanEliminate(m);

  // inv(A)
  for(i=0; i<n; i++) {
    m[i] = m[i].slice(n);
  }

  return m;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.isColumnDD"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isColumnDD (M)](#apidoc.element.numbers.matrix.isColumnDD)
- description and source-code
```javascript
isColumnDD = function (M) {
  if (!matrix.isSquare) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  var n = M.length;

  for (var i=0; i<n; i++) {
    var col = matrix.getCol(M,i),
        diag = col[i],
        sum = sumNondiagonalElements(col, i);

    if (Math.abs(diag) < sum) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.isLowerBand"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isLowerBand (M, p)](#apidoc.element.numbers.matrix.isLowerBand)
- description and source-code
```javascript
isLowerBand = function (M, p) {
  if (!Array.isArray(M) || !Array.isArray(M[0]) || M.length < 2) {
    throw new Error('Matrix must be an array of at least dimension 2.');
  } else if (typeof p !== 'number' || p < 0 || (p%1) !== 0) {
    throw new Error('Lower bandwidth must be a nonzero integer.');
  }
  var result = true,
    m = M.length,
    cnt = 0;

  for (var i=p+1; i<m; i++) {
    if (M[i][cnt] !== 0) {
      result = false;
      break;
    }
    cnt++;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.isRowDD"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isRowDD (M)](#apidoc.element.numbers.matrix.isRowDD)
- description and source-code
```javascript
isRowDD = function (M) {
  var n = M.length;
  if (!matrix.isSquare(M)) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  for (var i=0; i<n; i++) {
    var row = M[i],
        diag = row[i],
        sum = sumNondiagonalElements(row, i);

    if (Math.abs(diag) < sum) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.isSquare"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isSquare (arr)](#apidoc.element.numbers.matrix.isSquare)
- description and source-code
```javascript
isSquare = function (arr) {
  if (!Array.isArray(arr)) {
    throw new Error('Input must be a matrix.');
  } else if (arr[0][0] === undefined) {
    throw new Error('Input cannot be a vector.');
  }
  var rows = arr.length;

  for (var i = 0; i < rows; i++) {
    if (arr[i].length !== rows) return false;
  }

  return true;
}
```
- example usage
```shell
...
matrix.determinant = function (m) {
var numRow = m.length;
var numCol = m[0].length;
var det = 0;
var row, col;
var diagLeft, diagRight;

if (!matrix.isSquare(m)) {
  throw new Error(ERROR_MATRIX_NOT_SQUARE);
}

if (numRow === 1) {
  return m[0][0];
} else if (numRow === 2) {
  return m[0][0] * m[1][1] - m[0][1] * m[1][0];
...
```

#### <a name="apidoc.element.numbers.matrix.isStrictlyColumnDD"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isStrictlyColumnDD (M)](#apidoc.element.numbers.matrix.isStrictlyColumnDD)
- description and source-code
```javascript
isStrictlyColumnDD = function (M) {
  if (!matrix.isSquare(M)) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  var n = M.length;

  for (var i=0; i<n; i++) {
    var col = matrix.getCol(M,i),
        diag = col[i],
        sum = sumNondiagonalElements(col, i);

    if (Math.abs(diag) <= sum) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.isStrictlyRowDD"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isStrictlyRowDD (M)](#apidoc.element.numbers.matrix.isStrictlyRowDD)
- description and source-code
```javascript
isStrictlyRowDD = function (M) {
  if (!matrix.isSquare(M)) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  var n = M.length;

  for (var i=0; i<n; i++) {
    var row = M[i],
        diag = row[i],
        sum = sumNondiagonalElements(row, i);

    if (Math.abs(diag) <= sum) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.isUpperBand"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>isUpperBand (M, q)](#apidoc.element.numbers.matrix.isUpperBand)
- description and source-code
```javascript
isUpperBand = function (M, q) {
  if (!Array.isArray(M) || !Array.isArray(M[0]) || M.length < 2) {
    throw new Error('Matrix must be an array of at least dimension 2.');
  } else if (typeof q !== 'number' || q < 0 || (q%1) !== 0) {
    throw new Error('Upper bandwidth must be a nonzero integer.');
  }
  var result = true,
    n = M[0].length,
    cnt = 0;

  for (var i=q+1; i<n; i++) {
    if (M[cnt][i] !== 0) {
      result = false;
      break;
    }
    cnt++;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.lupDecomposition"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>lupDecomposition (arr)](#apidoc.element.numbers.matrix.lupDecomposition)
- description and source-code
```javascript
lupDecomposition = function (arr) {
  if (!matrix.isSquare(arr)) {
    throw new Error(ERROR_MATRIX_NOT_SQUARE);
  }

  var size = arr.length;

  var LU = matrix.deepCopy(arr);
  var P = matrix.transpose(matrix.identity(size));
  var currentRow;
  var currentColumn = new Array(size);

  this.getL = function(a) {
    var m = a[0].length;
    var L = matrix.identity(m);

    for (var i = 0; i < m; i++) {
      for (var j = 0; j < m; j++) {
        if (i > j) {
          L[i][j] = a[i][j];
        }
      }
    }

    return L;
  };

  this.getU = function(a) {
    var m = a[0].length;
    var U = matrix.identity(m);

    for (var i = 0; i < m; i++) {
      for (var j = 0; j < m; j++) {
        if (i <= j) {
          U[i][j] = a[i][j];
        }
      }
    }

    return U;
  };

  for (var j = 0; j < size; j++) {
    var i;
    for (i = 0; i < size; i++) {
      currentColumn[i] = LU[i][j];
    }

    for (i = 0; i < size; i++) {
      currentRow = LU[i];

      var minIndex = Math.min(i,j);
      var s = 0;

      for (var k = 0; k < minIndex; k++) {
        s += currentRow[k]*currentColumn[k];
      }

      currentRow[j] = currentColumn[i] -= s;
    }

    //Find pivot
    var pivot = j;
    for (i = j + 1; i < size; i++) {
      if (Math.abs(currentColumn[i]) > Math.abs(currentColumn[pivot])) {
        pivot = i;
      }
    }

    if (pivot != j) {
      LU = matrix.rowSwitch(LU, pivot, j);
      P = matrix.rowSwitch(P, pivot, j);
    }

    if (j < size && LU[j][j] !== 0) {
      for (i = j + 1; i < size; i++) {
        LU[i][j] /= LU[j][j];
      }
    }
  }

  return [this.getL(LU), this.getU(LU), P];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.matrixNorm"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>matrixNorm (M, p)](#apidoc.element.numbers.matrix.matrixNorm)
- description and source-code
```javascript
matrixNorm = function (M, p) {
  if (!(Array.isArray(M)) || (M.length === 0) || !Array.isArray(M[0])) {
    throw new Error('Matrix must be an array of at least length 1.');
  } else if ((typeof p !== 'undefined') && (typeof p !== 'number') && (p !== null)) {
    throw new Error('Norm order must be a number or null.');
  }

  p = (typeof p === 'undefined') ? null : p;
  var m = M.length, //number of rows
    n = M[0].length, //number of cols
    ans = 0,
    term, i, j;

  switch (p) {

    // the largest value when absolute-ing and summing each row
    case Infinity:
      for (i=0; i<m; i++) {
        term = 0;

        for (j=0; j<n; j++) {
          term += Math.abs(M[i][j]);
        }

        if (term > ans) {
          ans = term;
        }
      }
      break;

    // the smallest value when absolute-ing and summing each row
    case -Infinity:
      ans = Infinity;
      for (i=0; i<m; i++) {
        term = 0;

        for (j=0; j<n; j++) {
          term += Math.abs(M[i][j]);
        }

        if (term < ans) {
          ans = term;
        }
      }
      break;

    // the largest value when absolute-ing and summing each column
    case 1:
      for (i=0; i<n; i++) {
        term = 0;

        for (j=0; j<m; j++) {
          term += Math.abs(M[j][i]);
        }

        if (term > ans) {
          ans = term;
        }
      }
      break;

    // the smallest value when absolute-ing and summing each column
    case -1:
      ans = Infinity;
      for (i=0; i<n; i++) {
        term = 0;

        for (j=0; j<m; j++) {
          term += Math.abs(M[j][i]);
        }

        if (term < ans) {
          ans = term;
        }
      }
      break;

    // the Frobenius norm
    case null:
      for (i=0; i<m; i++) {
        for (j=0; j<n; j++) {
          ans += Math.pow(M[i][j], 2);
        }
      }
      ans = Math.pow(ans, 0.5);
      break;

    // largest singular value
    case 2:
      throw new Error("Singular values are not yet supported in numbers.js.");

    // smallest singular value
    case -2:
      throw new Error("Singular values are not yet supported in numbers.js.");

    // entry-wise norm; analogous to that of the entry-wise vector norm.
    default:
      for (i=0; i<m; i++) {
        for (j=0; j<n; j++) {
          ans += Math.pow(Math.abs(M[i][j]), p);
        }
      }
      ans = Math.pow(ans, 1/p);

  }

  return ans;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.multiply"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>multiply (arrA, arrB)](#apidoc.element.numbers.matrix.multiply)
- description and source-code
```javascript
multiply = function (arrA, arrB) {
  if (arrA[0].length !== arrB.length) {
    throw new Error("Matrix mismatch");
  }

  var result = new Array(arrA.length);

  for (var x = 0; x < arrA.length; x++) {
    result[x] = new Array(arrB[0].length);
  }

  var arrB_T = matrix.transpose(arrB);

  for (var i = 0; i < result.length; i++) {
    for (var j = 0; j < result[i].length; j++) {
      result[i][j] = matrix.dotproduct(arrA[i],arrB_T[j]);
    }
  }
  return result;
}
```
- example usage
```shell
...
*
* @return {Complex} the sine of this complex number.
*/
Complex.prototype.sin = function() {
 var E = new Complex(Math.E, 0);
 var i = new Complex(0, 1);
 var negativeI = new Complex(0, -1);
 var numerator = E.complexPow(i.multiply(this)).subtract(E.complexPow(negativeI.multiply(this)));

 return numerator.divide(new Complex(0, 2));
};

/**
* Returns the cosine of this complex number.
*
...
```

#### <a name="apidoc.element.numbers.matrix.reorderCols"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>reorderCols (M, L)](#apidoc.element.numbers.matrix.reorderCols)
- description and source-code
```javascript
reorderCols = function (M, L) {
  var result = [];
  if (L === undefined) {
    throw new Error('Please enter a desired reordering array.');
  } else if (L.length !== M[0].length) {
    throw new Error('The reordered matrix must have the same number of columns as the original matrix.');
  }
  for (var i=0; i<L.length; i++) {
    if (L[i] < 0) {
      throw new Error('The desired order of the columns must be positive integers.');
    } else if (L[i] >= L.length) {
      throw new Error('The desired order of the columns must start at 0 and end at the number of columns - 1.');
    } else {
      result.push(matrix.getCol(M, L[i]) );
    }
  }
  return matrix.transpose(result);
}
```
- example usage
```shell
...
* @return {Array} reversed matrix
*/
matrix.reverseCols = function(M) {
   var L = [];
   for (var i=M.length-1; i>-1; i--) {
       L.push(i);
   }
   return matrix.reorderCols(M,L);
};

/**
* Create a n x m matrix of zeros.
*
* @param {Int} number of rows
* @param {Int} number of columns
...
```

#### <a name="apidoc.element.numbers.matrix.reorderRows"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>reorderRows (M, L)](#apidoc.element.numbers.matrix.reorderRows)
- description and source-code
```javascript
reorderRows = function (M, L) {
  var result = [];
  if (L === undefined) {
    throw new Error('A reordering array must be entered.');
  } else if (L.length !== M.length) {
    throw new Error ('The reordered matrix must have the same number of rows as the original matrix.');
  }
  for (var i=0; i<L.length; i++) {
    if (L[i] < 0) {
      throw new Error('The desired order of the rows must be positive integers.');
    } else if (L[i] >= L.length) {
      throw new Error('The desired order of the rows must start at 0 and end at the number of rows - 1.');
    } else {
      result.push(M[L[i]]);
    }
  }
  return result;
}
```
- example usage
```shell
...
* @return {Array} reversed matrix
*/
matrix.reverseRows = function(M) {
   var L = [];
   for (var i=M.length-1; i>-1; i--) {
       L.push(i);
   }
   return matrix.reorderRows(M,L);
};

/**
* Reverse the columns of a matrix.
*
* @param {Array} matrix
* @return {Array} reversed matrix
...
```

#### <a name="apidoc.element.numbers.matrix.reverseCols"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>reverseCols (M)](#apidoc.element.numbers.matrix.reverseCols)
- description and source-code
```javascript
reverseCols = function (M) {
    var L = [];
    for (var i=M.length-1; i>-1; i--) {
        L.push(i);
    }
    return matrix.reorderCols(M,L);
}
```
- example usage
```shell
...
};

var BRV = function(M) {//starting at bottom right, moving vertically
  return matrix.transpose(BRH(M));
};

var BLH = function(M) {//starting at bottom left, moving horizontally
  return matrix.reverseCols(BRH(M));
};

var BLV = function(M) {//starting at bottom left, moving vertically
  return matrix.reverseRows(TLV(BLH(M)));
};

var TRH = function(M) {//starting at top right, moving horizontally
...
```

#### <a name="apidoc.element.numbers.matrix.reverseRows"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>reverseRows (M)](#apidoc.element.numbers.matrix.reverseRows)
- description and source-code
```javascript
reverseRows = function (M) {
    var L = [];
    for (var i=M.length-1; i>-1; i--) {
        L.push(i);
    }
    return matrix.reorderRows(M,L);
}
```
- example usage
```shell
...
};

var BLH = function(M) {//starting at bottom left, moving horizontally
  return matrix.reverseCols(BRH(M));
};

var BLV = function(M) {//starting at bottom left, moving vertically
  return matrix.reverseRows(TLV(BLH(M)));
};

var TRH = function(M) {//starting at top right, moving horizontally
  return matrix.reverseRows(BRH(M));
};

var TRV = function(M) {//starting at top right, moving vertically
...
```

#### <a name="apidoc.element.numbers.matrix.rotate"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>rotate (point, degree, direction)](#apidoc.element.numbers.matrix.rotate)
- description and source-code
```javascript
rotate = function (point, degree, direction) {
  matrix._check2DVector(point);

  var negate = direction === 'clockwise' ? -1 : 1;
  var radians = degree * (Math.PI / 180);

  var transformation = [
    [Math.cos(radians), -1 * negate * Math.sin(radians)],
    [negate * Math.sin(radians), Math.cos(radians)]
  ];

  return matrix.multiply(transformation, point);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.rowAddMultiple"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>rowAddMultiple (m, from, to, scale)](#apidoc.element.numbers.matrix.rowAddMultiple)
- description and source-code
```javascript
rowAddMultiple = function (m, from, to, scale){
  var result = new Array(m.length);

  for (var i = 0; i < m.length; i++) {
    result[i] = new Array(m[i].length);

    for (var j = 0; j < m[i].length; j++) {
      if (i === to) {
        result[to][j] = m[to][j] + scale * m[from][j];
      } else {
        result[i][j] = m[i][j];
      }
    }
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.rowReduce"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>rowReduce (m, epsilon)](#apidoc.element.numbers.matrix.rowReduce)
- description and source-code
```javascript
rowReduce = function (m, epsilon) {
  return matrix.GaussJordanEliminate(m, epsilon);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.rowScale"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>rowScale (m, row, scale)](#apidoc.element.numbers.matrix.rowScale)
- description and source-code
```javascript
rowScale = function (m, row, scale) {
  var result = new Array(m.length);

  for (var i = 0; i < m.length; i++) {
    result[i] = new Array(m[i].length);

    for (var j = 0; j < m[i].length; j++) {
      if (i === row) {
        result[i][j] = scale * m[i][j];
      } else {
        result[i][j] = m[i][j];
      }
    }
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.rowSwitch"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>rowSwitch (m, row1, row2)](#apidoc.element.numbers.matrix.rowSwitch)
- description and source-code
```javascript
rowSwitch = function (m, row1, row2) {
  var result = new Array(m.length);

  for (var i = 0; i < m.length; i++) {
    result[i] = new Array(m[i].length);

    for (var j = 0; j < m[i].length; j++) {
      if (i === row1) {
        result[i][j] = m[row2][j];
      } else if (i === row2) {
        result[i][j] = m[row1][j];
      } else {
        result[i][j] = m[i][j];
      }
    }
  }
  return result;
}
```
- example usage
```shell
...
for (i = j + 1; i < size; i++) {
  if (Math.abs(currentColumn[i]) > Math.abs(currentColumn[pivot])) {
    pivot = i;
  }
}

if (pivot != j) {
  LU = matrix.rowSwitch(LU, pivot, j);
  P = matrix.rowSwitch(P, pivot, j);
}

if (j < size && LU[j][j] !== 0) {
  for (i = j + 1; i < size; i++) {
    LU[i][j] /= LU[j][j];
  }
...
```

#### <a name="apidoc.element.numbers.matrix.scalar"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>scalar (arr, val)](#apidoc.element.numbers.matrix.scalar)
- description and source-code
```javascript
scalar = function (arr, val) {
  for (var i = 0; i < arr.length; i++) {
    for (var j = 0; j < arr[i].length; j++) {
      arr[i][j] = val * arr[i][j];
    }
  }

  return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.scale"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>scale (point, sx, sy)](#apidoc.element.numbers.matrix.scale)
- description and source-code
```javascript
scale = function (point, sx, sy) {
  matrix._check2DVector(point);

  var transformation = [
    [sx, 0],
    [0, sy]
  ];

  return matrix.multiply(transformation, point);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.shear"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>shear (point, k, direction)](#apidoc.element.numbers.matrix.shear)
- description and source-code
```javascript
shear = function (point, k, direction) {
  matrix._check2DVector(point);

  var xplaceholder = direction === 'xaxis' ? k : 0;
  var yplaceholder = direction === 'yaxis' ? k : 0;

  var transformation = [
    [1, xplaceholder],
    [yplaceholder, 1]
  ];

  return matrix.multiply(transformation, point);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.subtraction"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>subtraction (arrA, arrB)](#apidoc.element.numbers.matrix.subtraction)
- description and source-code
```javascript
subtraction = function (arrA, arrB) {
  if (arrA.length !== arrB.length || arrA[0].length !== arrB[0].length) {
    throw new Error("Matrix mismatch");
  }

  var result = new Array(arrA.length),
      i;

  if (!arrA[0].length) {
    // The arrays are vectors.
    for (i = 0; i < arrA.length; i++) {
      result[i] = arrA[i] - arrB[i];
    }
  } else {
    for (i = 0; i < arrA.length; i++) {
        result[i] = new Array(arrA[i].length);

        for (var j = 0; j < arrA[i].length; j++) {
          result[i][j] = arrA[i][j] - arrB[i][j];
        }
    }
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.transpose"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>transpose (arr)](#apidoc.element.numbers.matrix.transpose)
- description and source-code
```javascript
transpose = function (arr) {
  var result = new Array(arr[0].length);

  for (var i = 0; i < arr[0].length; i++) {
    result[i] = new Array(arr.length);

    for (var j = 0; j < arr.length; j++) {
      result[i][j] = arr[j][i];
    }
  }

  return result;
}
```
- example usage
```shell
...

numbers.matrix.addition(array1, array2);
'''

We can transpose a matrix

'''javascript
numbers.matrix.transpose(array);
'''

Numbers also includes some basic prime number analysis.  We can check if a number is prime:

'''javascript
// basic check
numbers.prime.simple(number);
...
```

#### <a name="apidoc.element.numbers.matrix.vectorNorm"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>vectorNorm (v, p)](#apidoc.element.numbers.matrix.vectorNorm)
- description and source-code
```javascript
vectorNorm = function (v, p) {
  // calculate the p'th norm of a vector v
  if (!(Array.isArray(v)) || (v.length === 0)) {
    throw new Error('Vector must be an array of at least length 1.');
  } else if ((typeof p !== 'undefined') && (typeof p !== 'number')) {
    throw new Error('Norm order must be a number.');
  }

  p = (typeof p === 'undefined') ? 2 : p;
  var n = v.length,
    ans = 0,
    term, i;

  switch (p) {

    case Infinity:
      for (i=0; i<n; i++) {
        term = Math.abs(v[i]);
        if (term > ans) {
          ans = term;
        }
      }
      break;

    case -Infinity:
      ans = Infinity;
      for (i=0; i<n; i++) {
        term = Math.abs(v[i]);
        if (term < ans) {
          ans = term;
        }
      }
      break;

    default:
      for (i=0; i<n; i++) {
        ans += Math.pow(Math.abs(v[i]), p);
      }
      ans = Math.pow(ans, 1/p);
      break;
  }

  return ans;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.matrix.zeros"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>zeros (n, m)](#apidoc.element.numbers.matrix.zeros)
- description and source-code
```javascript
zeros = function (n, m) {
  var M = new Array(n);
  if (n < 1 || m < 1) {
    throw new Error('The matrix dimensions must be positive integers.');
  }
  n = Math.ceil(n);
  m = Math.ceil(m);
  for (var i=0; i<n; i++) {
    var empty = new Array(m);
    for (var j=0; j<m; j++) {
      empty[j] = 0;
    }
    M[i] = empty;
  }
  return M;
}
```
- example usage
```shell
...
 * @return {Array} zigzag matrix.
 */
matrix.zigzag = function(n, point, dir) {
if (n <= 1) {
  throw new Error('Matrix size must be at least 2x2.');
}
n = Math.ceil(n);
var mat = matrix.zeros(n,n);

//create one kind of permutation - all other permutations can be
//created from this particular permutation through transformations
var BRH = function(M) { //starting at bottom right, moving horizontally
  var jump = false,
      tl = n*n,
      br = 1,
...
```

#### <a name="apidoc.element.numbers.matrix.zigzag"></a>[function <span class="apidocSignatureSpan">numbers.matrix.</span>zigzag (n, point, dir)](#apidoc.element.numbers.matrix.zigzag)
- description and source-code
```javascript
zigzag = function (n, point, dir) {
  if (n <= 1) {
    throw new Error('Matrix size must be at least 2x2.');
  }
  n = Math.ceil(n);
  var mat = matrix.zeros(n,n);

  //create one kind of permutation - all other permutations can be
  //created from this particular permutation through transformations
  var BRH = function(M) { //starting at bottom right, moving horizontally
    var jump = false,
        tl = n*n,
        br = 1,
        inc = 1,
        row, col, val, i, j;
    M[0][0] = tl;
    M[n-1][n-1] = br;

    for (i=1; i<n; i++) {
      //generate top/bottom row
      if (jump) {
        tl -= 4*inc;
        br += 4*inc;
        inc++;
      } else {
        tl--;
        br++;
      }

      M[0][i] = tl;
      M[n-1][n-1-i] = br;
      jump = !jump;
    }

    var dec = true;
    for (i=1; i<n; i++) {
      //iterate diagonally from top row
      row = 0;
      col = i;
      val = M[row][col];

      for (j=1; j<i+1;j++) {
        if (dec) {
          val -= 1;
        } else {
          val += 1;
        }
        row++;
        col--;
        M[row][col] = val;
      }
        dec = !dec;
    }

    if (n%2 === 0) {
      dec = true;
    } else {
      dec = false;
    }
    for (i=1; i<n-1; i++) {
      //iterate diagonally from bottom row
      row = n-1;
      col = i;
      val = M[row][col];

      for (j=1; j<n-i; j++) {
        if (dec) {
          val--;
        } else {
          val++;
        }
        row--;
        col++;
        M[row][col] = val;
      }
      dec = !dec;
    }
    return M;
  };

  var BRV = function(M) {//starting at bottom right, moving vertically
    return matrix.transpose(BRH(M));
  };

  var BLH = function(M) {//starting at bottom left, moving horizontally
    return matrix.reverseCols(BRH(M));
  };

  var BLV = function(M) {//starting at bottom left, moving vertically
    return matrix.reverseRows(TLV(BLH(M)));
  };

  var TRH = function(M) {//starting at top right, moving horizontally
    return matrix.reverseRows(BRH(M));
  };

  var TRV = function(M) {//starting at top right, moving vertically
    return matrix.reverseRows(BRV(M));
  };

  var TLH = function(M) {//starting at top left, moving horizontally
    return matrix.reverseCols(matrix.reverseRows(BRH(M)));
  };

  var TLV = function(M) {//starting at top left, moving vertically
    return matrix.transpose(TLH(M));
  };

  if ((point === 'BR') && (dir === 'H')) {return (BRH(mat));}
  else if ((point === 'BR') && (dir === 'V')) {return (BRV(mat));}
  else if ((point === 'BL') && (dir === 'H')) {return (BLH(mat));}
  else if ((point === 'BL') && (dir === 'V')) {return (BLV(mat));}
  else if ((point === 'TR') && (dir === 'H')) {return (TRH(mat));}
  else if ((point === 'TR') && (dir === 'V')) {return (TRV(mat));}
  else if ((point === 'TL') && (dir === 'H')) {return (TLH(mat));}
  else if ((point === 'TL') && (dir === 'V')) {return (TLV(mat));}
  else {throw new Error('Enter the direction (V,H) and corner (BR,BL,TR,TL) correctly.');}
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.numbers"></a>[module numbers.numbers](#apidoc.module.numbers.numbers)

#### <a name="apidoc.element.numbers.numbers.complex"></a>[function <span class="apidocSignatureSpan">numbers.numbers.</span>complex (re, im)](#apidoc.element.numbers.numbers.complex)
- description and source-code
```javascript
complex = function (re, im) {
  this.re = re;
  this.im = im;
  this.r  = this.magnitude();
  this.t  = this.phase(); // theta = t = arg(z)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.prime"></a>[module numbers.prime](#apidoc.module.numbers.prime)

#### <a name="apidoc.element.numbers.prime.coprime"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>coprime (a, b)](#apidoc.element.numbers.prime.coprime)
- description and source-code
```javascript
coprime = function (a, b) {
  return basic.gcd(a, b) === 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.prime.factorization"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>factorization (num)](#apidoc.element.numbers.prime.factorization)
- description and source-code
```javascript
factorization = function (num) {
  num = Math.floor(num);
  var root;
  var factors = [];
  var x;
  var sqrt = Math.sqrt;
  var doLoop = 1 < num && isFinite(num);

  while (doLoop) {
    root = sqrt(num);
    x = 2;
    if (num % x) {
      x = 3;
      while ((num % x) && ((x += 2) < root)) {}
    }

    x = (root < x) ? num : x;
    factors.push(x);
    doLoop = (x !== num);
    num /= x;
  }

  return factors;
}
```
- example usage
```shell
...
/**
 * Returns the prime factors of a number.
 * More info (http://bateru.com/news/2012/05/code-of-the-day-javascript-prime-factors-of-a-number/)
 * Taken from Ratio.js
 *
 * @param {Number} num
 * @return {Array} an array of numbers
 * @example prime.factorization(20).join(',') === "2,2,5"
 **/
prime.factorization = function (num) {
num = Math.floor(num);
var root;
var factors = [];
var x;
var sqrt = Math.sqrt;
...
```

#### <a name="apidoc.element.numbers.prime.getPerfectPower"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>getPerfectPower (n)](#apidoc.element.numbers.prime.getPerfectPower)
- description and source-code
```javascript
getPerfectPower = function (n) {
  var test = prime.getPrimePower(n);
  if (test && test[1] > 1) return test;
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.prime.getPrimePower"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>getPrimePower (n)](#apidoc.element.numbers.prime.getPrimePower)
- description and source-code
```javascript
getPrimePower = function (n) {
  if (n < 2) return false;
  if (prime.millerRabin(n)) return [n, 1];
  if (n % 2 === 0) return [2, n.toString(2).length - 1];

  var factors = prime.factorization(n);

  if (!factors) return false;

  var len = factors.length;

  for (var i = 0; i < len; i++) {
    var t = 0, p = 0;

    while (t <= n) {
      t = Math.pow(factors[i], p);
      if (t / n === 1) return [factors[i], p];
      p++;
    }
  }

  return false;
}
```
- example usage
```shell
...
* m^k = n
* http://en.wikipedia.org/wiki/Perfect_power
*
* @param {Number} value in question
* @return {Array|Boolean} [m, k] if it is a perfect power, false otherwise
*/
prime.getPerfectPower = function(n) {
 var test = prime.getPrimePower(n);
 if (test && test[1] > 1) return test;
 return false;
};

/**
* Determine if a number is a prime power and return the prime and the power.
* http://en.wikipedia.org/wiki/Prime_power
...
```

#### <a name="apidoc.element.numbers.prime.millerRabin"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>millerRabin (n, k)](#apidoc.element.numbers.prime.millerRabin)
- description and source-code
```javascript
millerRabin = function (n, k) {
  if (arguments.length === 1) k = 20;
  if (n === 2) return true;
  if (!basic.isInt(n) || n <= 1 || n % 2 === 0) return false;

  var s = 0;
  var d = n - 1;

  while (true) {
    var dm = basic.divMod(d, 2);
    var quotient = dm[0];
    var remainder = dm[1];

    if (remainder === 1) break;

    s += 1;
    d = quotient;
  }

  var tryComposite = function (a) {
    if (basic.powerMod(a, d, n) === 1) return false;

    for (var i = 0; i < s; i ++) {
      if (basic.powerMod(a, Math.pow(2, i) * d, n) === n - 1) return false;
    }

    return true;
  };

  for (var i = 0; i < k; i++) {
    var a = 2 + Math.floor(Math.random() * (n - 2 - 2));
    if (tryComposite(a)) return false;
  }

  return true;
}
```
- example usage
```shell
...
Numbers also includes some basic prime number analysis.  We can check if a number is prime:

'''javascript
// basic check
numbers.prime.simple(number);

// Miller-Rabin primality test
numbers.prime.millerRabin(number);
'''

The statistics tools include mean, median, mode, standard deviation, random sample generator, correlation, confidence intervals,
t-test, chi-square, and more.

'''javascript
numbers.statistic.mean(array);
numbers.statistic.median(array);
...
```

#### <a name="apidoc.element.numbers.prime.sieve"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>sieve (n)](#apidoc.element.numbers.prime.sieve)
- description and source-code
```javascript
sieve = function (n) {
  if (n < 2) return [];
  var result = [2];
  for (var i = 3; i <= n; i++) {
    var notMultiple = false;

    for (var j in result) {
      notMultiple = notMultiple || (0 === i % result[j]);
    }

    if (!notMultiple) {
      result.push(i);
    }
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.prime.simple"></a>[function <span class="apidocSignatureSpan">numbers.prime.</span>simple (n)](#apidoc.element.numbers.prime.simple)
- description and source-code
```javascript
simple = function (n) {
    if (isNaN(n) || !isFinite(n) || n % 1 || n < 2) {
        return false;
    }
    if (n % 2 === 0){
        return (n === 2);
    }
    if (n % 3 === 0){
        return (n === 3);
    }
    for (var i = 5, m = Math.sqrt(n); i <= m; i += 6) {
        if ((n % i === 0) || (n % (i + 2) === 0)){
            return false;
        }
    }
    return true;
}
```
- example usage
```shell
...
numbers.matrix.transpose(array);
'''

Numbers also includes some basic prime number analysis.  We can check if a number is prime:

'''javascript
// basic check
numbers.prime.simple(number);

// Miller-Rabin primality test
numbers.prime.millerRabin(number);
'''

The statistics tools include mean, median, mode, standard deviation, random sample generator, correlation, confidence intervals,
t-test, chi-square, and more.
...
```



# <a name="apidoc.module.numbers.random"></a>[module numbers.random](#apidoc.module.numbers.random)

#### <a name="apidoc.element.numbers.random.bates"></a>[function <span class="apidocSignatureSpan">numbers.random.</span>bates (n, b, a)](#apidoc.element.numbers.random.bates)
- description and source-code
```javascript
bates = function (n, b, a) {
  if (arguments.length <= 2) a = 0;
  if (arguments.length === 1) b = 1;
  var sum = 0;
  for (var i = 0; i < n; i++) sum += (b - a)*rGen() + a;
  return sum/n;
}
```
- example usage
```shell
...
random.distribution.bates = function(n, b, a) {
  if (arguments.length <= 2) a = 0;
  if (arguments.length === 1) b = n;

  var results = new Array(n);

  for (var i = 0; i < n; i++) {
    results[i] = random.bates(n, b, a);
  }

  return results;
};

},{"./basic":3}],11:[function(require,module,exports){
/**
...
```

#### <a name="apidoc.element.numbers.random.boxMullerTransform"></a>[function <span class="apidocSignatureSpan">numbers.random.</span>boxMullerTransform (mu, sigma)](#apidoc.element.numbers.random.boxMullerTransform)
- description and source-code
```javascript
boxMullerTransform = function (mu, sigma) {
  if (arguments.length <= 1) sigma = 1;
  if (arguments.length === 0) mu = 0;
  var u = 0,
      v = 0,
      s;

  do {
    u = rGen() * 2 - 1;
    v = rGen() * 2 - 1;
    s = u * u + v * v;
  } while (s === 0 || s > 1);

  var c = Math.sqrt(-2 * Math.log(s)/s),
      x = u * c,
      y = v * c;
  x = mu + x * sigma;
  y = mu + y * sigma;
  return [x, y];
}
```
- example usage
```shell
...
random.distribution.boxMuller = function(n, mu, sigma, rc) {
  if (arguments.length <= 3) rc = false;
  if (arguments.length <= 2) sigma = 1;
  if (arguments.length === 1) mu = 0;
  var results = [];

  for (var i = 0; i < n; i++) {
    var randomBMT = random.boxMullerTransform(mu, sigma);
    results.push((rc) ? randomBMT : randomBMT[0]);
  }

  return results;
};

/**
...
```

#### <a name="apidoc.element.numbers.random.irwinHall"></a>[function <span class="apidocSignatureSpan">numbers.random.</span>irwinHall (n, sub)](#apidoc.element.numbers.random.irwinHall)
- description and source-code
```javascript
irwinHall = function (n, sub) {
  if (arguments.length === 1) sub = 0;
  var sum = 0;
  for (var i = 0; i < n; i++) sum += rGen();
  return sum - sub;
}
```
- example usage
```shell
...
* @return {Array} irwin hall distribution from [a, b]
*/
random.distribution.irwinHall = function(n, m, sub) {
 if (arguments.length <= 2) sub = 0;
 if (arguments.length === 1) m = n;
 var results = new Array(n);
 for (var i = 0; i < n; i++) {
   results[i] = random.irwinHall(m, sub);
 }

 return results;
};

/**
* An approach to create a normal distribution,
...
```

#### <a name="apidoc.element.numbers.random.sample"></a>[function <span class="apidocSignatureSpan">numbers.random.</span>sample (lower, upper, n)](#apidoc.element.numbers.random.sample)
- description and source-code
```javascript
sample = function (lower, upper, n) {
  var sample = [];
  sample.length = n;

  for (var i=0; i<n; i++) {
    sample[i] = lower + (upper - lower) * rGen();
  }
  return sample;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.random.setGenerator"></a>[function <span class="apidocSignatureSpan">numbers.random.</span>setGenerator (fn)](#apidoc.element.numbers.random.setGenerator)
- description and source-code
```javascript
setGenerator = function (fn){
  if(typeof fn !== "function"){
    throw new Error("Must pass a function");
  }
  rGen = fn;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.random.distribution"></a>[module numbers.random.distribution](#apidoc.module.numbers.random.distribution)

#### <a name="apidoc.element.numbers.random.distribution.bates"></a>[function <span class="apidocSignatureSpan">numbers.random.distribution.</span>bates (n, b, a)](#apidoc.element.numbers.random.distribution.bates)
- description and source-code
```javascript
bates = function (n, b, a) {
  if (arguments.length <= 2) a = 0;
  if (arguments.length === 1) b = n;

  var results = new Array(n);

  for (var i = 0; i < n; i++) {
    results[i] = random.bates(n, b, a);
  }

  return results;
}
```
- example usage
```shell
...
random.distribution.bates = function(n, b, a) {
  if (arguments.length <= 2) a = 0;
  if (arguments.length === 1) b = n;

  var results = new Array(n);

  for (var i = 0; i < n; i++) {
    results[i] = random.bates(n, b, a);
  }

  return results;
};

},{"./basic":3}],11:[function(require,module,exports){
/**
...
```

#### <a name="apidoc.element.numbers.random.distribution.boxMuller"></a>[function <span class="apidocSignatureSpan">numbers.random.distribution.</span>boxMuller (n, mu, sigma, rc)](#apidoc.element.numbers.random.distribution.boxMuller)
- description and source-code
```javascript
boxMuller = function (n, mu, sigma, rc) {
  if (arguments.length <= 3) rc = false;
  if (arguments.length <= 2) sigma = 1;
  if (arguments.length === 1) mu = 0;
  var results = [];

  for (var i = 0; i < n; i++) {
    var randomBMT = random.boxMullerTransform(mu, sigma);
    results.push((rc) ? randomBMT : randomBMT[0]);
  }

  return results;
}
```
- example usage
```shell
...
* @param {Number} sigma or standard deviation
* @return {Array} array of size n of a normal distribution
*/
random.distribution.normal = function(n, mu, sigma) {
 if (arguments.length <= 2) sigma = 1;
 if (arguments.length === 1) mu = 0;

 return random.distribution.boxMuller(n, mu, sigma);
};

/**
* Returns an array of size n that is an approximate log normal distribution
*
* @param {Number} n size of returned array
* @param {Number} mu or mean
...
```

#### <a name="apidoc.element.numbers.random.distribution.irwinHall"></a>[function <span class="apidocSignatureSpan">numbers.random.distribution.</span>irwinHall (n, m, sub)](#apidoc.element.numbers.random.distribution.irwinHall)
- description and source-code
```javascript
irwinHall = function (n, m, sub) {
  if (arguments.length <= 2) sub = 0;
  if (arguments.length === 1) m = n;
  var results = new Array(n);
  for (var i = 0; i < n; i++) {
    results[i] = random.irwinHall(m, sub);
  }

  return results;
}
```
- example usage
```shell
...
* @return {Array} irwin hall distribution from [a, b]
*/
random.distribution.irwinHall = function(n, m, sub) {
 if (arguments.length <= 2) sub = 0;
 if (arguments.length === 1) m = n;
 var results = new Array(n);
 for (var i = 0; i < n; i++) {
   results[i] = random.irwinHall(m, sub);
 }

 return results;
};

/**
* An approach to create a normal distribution,
...
```

#### <a name="apidoc.element.numbers.random.distribution.irwinHallNormal"></a>[function <span class="apidocSignatureSpan">numbers.random.distribution.</span>irwinHallNormal (n)](#apidoc.element.numbers.random.distribution.irwinHallNormal)
- description and source-code
```javascript
irwinHallNormal = function (n) {
  return random.distribution.irwinHall(n, 12, 6);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.random.distribution.logNormal"></a>[function <span class="apidocSignatureSpan">numbers.random.distribution.</span>logNormal (n, mu, sigma)](#apidoc.element.numbers.random.distribution.logNormal)
- description and source-code
```javascript
logNormal = function (n, mu, sigma) {
  if (arguments.length <= 2) sigma = 1;
  if (arguments.length === 1) mu = 0;

  var exponential = function(x) {
    return Math.exp(x);
  };

  return random.distribution.boxMuller(n, mu, sigma).map(exponential);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.random.distribution.normal"></a>[function <span class="apidocSignatureSpan">numbers.random.distribution.</span>normal (n, mu, sigma)](#apidoc.element.numbers.random.distribution.normal)
- description and source-code
```javascript
normal = function (n, mu, sigma) {
  if (arguments.length <= 2) sigma = 1;
  if (arguments.length === 1) mu = 0;

  return random.distribution.boxMuller(n, mu, sigma);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.numbers.statistic"></a>[module numbers.statistic](#apidoc.module.numbers.statistic)

#### <a name="apidoc.element.numbers.statistic.correlation"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>correlation (arrX, arrY)](#apidoc.element.numbers.statistic.correlation)
- description and source-code
```javascript
correlation = function (arrX, arrY) {
  if (arrX.length == arrY.length) {
    var covarXY = statistic.covariance(arrX, arrY);
    var stdDevX = statistic.standardDev(arrX);
    var stdDevY = statistic.standardDev(arrY);

    return covarXY / (stdDevX * stdDevY);
  } else {
    throw new Error('Array mismatch');
  }
}
```
- example usage
```shell
...

'''javascript
numbers.statistic.mean(array);
numbers.statistic.median(array);
numbers.statistic.mode(array);
numbers.statistic.standardDev(array);
numbers.statistic.randomSample(lower, upper, n);
numbers.statistic.correlation(array1, array2);
'''
For further documentation, check out [numbersjs.info](http://www.numbersjs.info)

## Test

To execute, run:
...
```

#### <a name="apidoc.element.numbers.statistic.covariance"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>covariance (set1, set2)](#apidoc.element.numbers.statistic.covariance)
- description and source-code
```javascript
covariance = function (set1, set2) {
  if (set1.length == set2.length) {
    var n = set1.length;
    var total = 0;
    var sum1 = basic.sum(set1);
    var sum2 = basic.sum(set2);

    for (var i = 0; i < n; i++) {
      total += set1[i] * set2[i];
    }

    return (total - sum1 * sum2 / n) / n;
  } else {
    throw new Error('Array mismatch');
  }
}
```
- example usage
```shell
...
 * Evaluate the correlation amongst a set of values.
 *
 * @param {Array} set of values.
 * @return {Number} correlation.
 */
statistic.correlation = function (arrX, arrY) {
if (arrX.length == arrY.length) {
  var covarXY = statistic.covariance(arrX, arrY);
  var stdDevX = statistic.standardDev(arrX);
  var stdDevY = statistic.standardDev(arrY);

  return covarXY / (stdDevX * stdDevY);
} else {
  throw new Error('Array mismatch');
}
...
```

#### <a name="apidoc.element.numbers.statistic.exponentialRegression"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>exponentialRegression (arrY)](#apidoc.element.numbers.statistic.exponentialRegression)
- description and source-code
```javascript
exponentialRegression = function (arrY) {
  var n = arrY.length;
  var arrX = basic.range(1,n);

  var xSum = basic.sum(arrX);
  var ySum = basic.sum(arrY);
  var yMean = statistic.mean(arrY);
  var yLog = arrY.map(function (d) { return Math.log(d); });
  var xSquared = arrX.map(function (d) { return d * d; });
  var xSquaredSum = basic.sum(xSquared);
  var yLogSum = basic.sum(yLog);
  var xyLog = arrX.map(function (d, i) { return d * yLog[i]; });
  var xyLogSum = basic.sum(xyLog);

  var a = (yLogSum * xSquaredSum - xSum * xyLogSum) / (n * xSquaredSum - (xSum * xSum));
  var b = (n * xyLogSum - xSum * yLogSum) / (n * xSquaredSum - (xSum * xSum));

  var fn = function(x) {
    if (typeof x === 'number') {
      return Math.exp(a) * Math.exp(b * x);
    } else {
      return x.map(function (d) {
        return Math.exp(a) * Math.exp(b * d);
      });
    }
  };

  fn.rSquared = statistic.rSquared(arrY, arrX.map(fn));

  return fn;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.statistic.linearRegression"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>linearRegression (arrX, arrY)](#apidoc.element.numbers.statistic.linearRegression)
- description and source-code
```javascript
linearRegression = function (arrX, arrY) {
  var n = arrX.length;
  var xSum = basic.sum(arrX);
  var ySum = basic.sum(arrY);
  var xySum = basic.sum(arrX.map(function (d, i) { return d * arrY[i]; }));
  var xSquaredSum = basic.sum(arrX.map(function (d) { return d * d; }));
  var xMean = statistic.mean(arrX);
  var yMean = statistic.mean(arrY);
  var b = (xySum - 1 / n * xSum * ySum) / (xSquaredSum - 1 / n * (xSum * xSum));
  var a = yMean - b * xMean;

  return function(x) {
    if (typeof x === 'number') {
      return a + b * x;
    } else {
      return x.map(function (d) {
        return a + b * d;
      });
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.statistic.mean"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>mean (arr)](#apidoc.element.numbers.statistic.mean)
- description and source-code
```javascript
mean = function (arr) {
  var count = arr.length;
  var sum = basic.sum(arr);
  return sum / count;
}
```
- example usage
```shell
...
// Miller-Rabin primality test
numbers.prime.millerRabin(number);
'''

The statistics tools include mean, median, mode, standard deviation, random sample generator, correlation, confidence intervals,
t-test, chi-square, and more.

'''javascript
numbers.statistic.mean(array);
numbers.statistic.median(array);
numbers.statistic.mode(array);
numbers.statistic.standardDev(array);
numbers.statistic.randomSample(lower, upper, n);
numbers.statistic.correlation(array1, array2);
'''
For further documentation, check out [numbersjs.info](http://www.numbersjs.info)
...
```

#### <a name="apidoc.element.numbers.statistic.median"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>median (arr)](#apidoc.element.numbers.statistic.median)
- description and source-code
```javascript
median = function (arr) {
  return statistic.quantile(arr, 1, 2);
}
```
- example usage
```shell
...
numbers.prime.millerRabin(number);
'''

The statistics tools include mean, median, mode, standard deviation, random sample generator, correlation, confidence intervals,
t-test, chi-square, and more.

'''javascript
numbers.statistic.mean(array);
numbers.statistic.median(array);
numbers.statistic.mode(array);
numbers.statistic.standardDev(array);
numbers.statistic.randomSample(lower, upper, n);
numbers.statistic.correlation(array1, array2);
'''
For further documentation, check out [numbersjs.info](http://www.numbersjs.info)
...
```

#### <a name="apidoc.element.numbers.statistic.mode"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>mode (arr)](#apidoc.element.numbers.statistic.mode)
- description and source-code
```javascript
mode = function (arr) {
  var counts = {};
  for (var i = 0, n = arr.length; i < n; i++) {
    if (counts[arr[i]] === undefined) {
      counts[arr[i]] = 0;
    } else {
      counts[arr[i]]++;
    }
  }

  var highest;

  for (var number in counts) {
    if (counts.hasOwnProperty(number)) {
      if (highest === undefined || counts[number] > counts[highest]) {
        highest = number;
      }
    }
  }

  return Number(highest);
}
```
- example usage
```shell
...
'''

The statistics tools include mean, median, mode, standard deviation, random sample generator, correlation, confidence intervals,
t-test, chi-square, and more.

'''javascript
numbers.statistic.mean(array);
numbers.statistic.median(array);
numbers.statistic.mode(array);
numbers.statistic.standardDev(array);
numbers.statistic.randomSample(lower, upper, n);
numbers.statistic.correlation(array1, array2);
'''
For further documentation, check out [numbersjs.info](http://www.numbersjs.info)

## Test
...
```

#### <a name="apidoc.element.numbers.statistic.quantile"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>quantile (arr, k, q)](#apidoc.element.numbers.statistic.quantile)
- description and source-code
```javascript
quantile = function (arr, k, q) {
  var sorted, count, index;

  if (k === 0) return Math.min.apply(null, arr);

  if (k === q) return Math.max.apply(null, arr);

  sorted = arr.slice(0);
  sorted.sort(function (a, b) { return a - b; });
  count = sorted.length;
  index = count * k / q;

  if (index % 1 === 0) return 0.5 * sorted[index - 1] + 0.5 * sorted[index];

  return sorted[Math.floor(index)];
}
```
- example usage
```shell
...
/**
* Calculate the median value of a set of numbers in array.
*
* @param {Array} set of values.
* @return {Number} median value.
*/
statistic.median = function (arr) {
 return statistic.quantile(arr, 1, 2);
};

/**
* Calculate the mode value of a set of numbers in array.
*
* @param {Array} set of values.
* @return {Number} mode value.
...
```

#### <a name="apidoc.element.numbers.statistic.rSquared"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>rSquared (source, regression)](#apidoc.element.numbers.statistic.rSquared)
- description and source-code
```javascript
rSquared = function (source, regression) {
  var residualSumOfSquares = basic.sum(source.map(function (d,i) {
    return basic.square(d - regression[i]);
  }));

  var totalSumOfSquares = basic.sum(source.map(function (d) {
    return basic.square(d - statistic.mean(source));
  }));

  return 1 - (residualSumOfSquares / totalSumOfSquares);
}
```
- example usage
```shell
...
   } else {
     return x.map(function (d) {
       return Math.exp(a) * Math.exp(b * d);
     });
   }
 };

 fn.rSquared = statistic.rSquared(arrY, arrX.map(fn));

 return fn;
};

/**
* Create a function to calculate the linear regression of a dataset.
*
...
```

#### <a name="apidoc.element.numbers.statistic.report"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>report (array)](#apidoc.element.numbers.statistic.report)
- description and source-code
```javascript
report = function (array) {
  return {
    mean: statistic.mean(array),
    firstQuartile: statistic.quantile(array, 1, 4),
    median: statistic.median(array),
    thirdQuartile: statistic.quantile(array, 3, 4),
    standardDev: statistic.standardDev(array)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.numbers.statistic.standardDev"></a>[function <span class="apidocSignatureSpan">numbers.statistic.</span>standardDev (arr)](#apidoc.element.numbers.statistic.standardDev)
- description and source-code
```javascript
standardDev = function (arr) {
  var count = arr.length;
  var mean = statistic.mean(arr);
  var squaredArr = [];

  for (var i = 0; i < arr.length; i++) {
    squaredArr[i] = Math.pow((arr[i] - mean),2);
  }

  return Math.sqrt((1 / count) * basic.sum(squaredArr));
}
```
- example usage
```shell
...

The statistics tools include mean, median, mode, standard deviation, random sample generator, correlation, confidence intervals,
t-test, chi-square, and more.

'''javascript
numbers.statistic.mean(array);
numbers.statistic.median(array);
numbers.statistic.mode(array);
numbers.statistic.standardDev(array);
numbers.statistic.randomSample(lower, upper, n);
numbers.statistic.correlation(array1, array2);
'''
For further documentation, check out [numbersjs.info](http://www.numbersjs.info)

## Test
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
