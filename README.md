# taxicab

**EN**\
Refers to https://oeis.org/A011541 sequence

**FR**\
Le plus petit nombre a(n) qui est la somme de 2 cubes entiers positifs (x<sub>i</sub> et x'<sub>i</sub>) de n façons, soit a(n) = x<sub>i</sub>^3 + x'<sub>i</sub>^3.\
Ci-dessous, l'ensemble des solutions classées par ordre croissant de valeurs et décroissant de n.

**Remarques**
- Les valeurs x<sub>i</sub> (sauf pour x<sub>1</sub>) ont un rapport de **79** entre a(5) et a(6)
- Les valeurs x<sub>i</sub> (sauf pour x<sub>3</sub>) ont un rapport de **101** entre a(6) et a(7)
- La valeur de x<sub>1</sub> pour a(n+1) est supérieure (ou égale pour a(2)) à celle de x<sub>1</sub> pour a(n)
- Si on multiplie les x<sub>i</sub> de a(5) par **79** ou **139** ou un multiple de 79 ou un multiple de 139, on obtient un multiple de a(6)
- Certains x<sub>i</sub> ont une différence multiple de **11**: {1,12}, {414,436}, {331954,365757}, {27093208,28906206}
  - de même pour: {255,167}, {13322,2421}, {231518,38787}, {26590452,582162}
- Sauf pour a(1), on a un couple de x<sub>i</sub> (espacés de 2 termes) multiples de **3**: {9,12}, {228,423}, {10200,18072}, {221424,336588}, {1766742096,2685635652}

----

a(7) = 24885189317885898975235988544\
x<sub>1</sub> = 58798362 = 2 * 3 * 7 * 83 * 101 * 167\
x<sub>2</sub> = 309481473 = 3 * 7 * 79 * 101 * 1847\
x<sub>3</sub> = 459531128 = 2^3 * 7 * 8205913\
x<sub>4</sub> = 860447381 = 79 * 101 * 107839\
x<sub>5</sub> = 1638024868 = 2^2 * 17 * 79 * 101 * 3019\
x<sub>6</sub> = 1766742096 = 2^4 * 3 * 7 * 79 * 101 * 659\
x<sub>7</sub> = 1847282122 = 2 * 7 * 23 * 79 * 101 * 719\
x'<sub>7</sub> = 2648660966 = 2 * 7 * 79 * 101 * 131 * 181\
x'<sub>6</sub> = 2685635652 = 2^2 * 3 * 7 * 79 * 101 * 4007\
x'<sub>5</sub> = 2736414008 = 2^3 * 79 * 101 * 163 * 263\
x'<sub>4</sub> = 2894406187 = 79 * 101 * 362753\
x'<sub>3</sub> = 2915734948 = 2^2 * 7 * 191 * 457 * 1193\
x'<sub>2</sub> = 2918375103 = 3 * 7 * 79 * 101 * 17417\
x'<sub>1</sub> = 2919526806 = 2 * 3 * 7 * 101 * 311 * 2213

a(6) = 24153319581254312065344\
x<sub>1</sub> = 582162 = 2 * 3 * 7 * 83 * 167\
x<sub>2</sub> = 3064173 = 3 * 7 * 79 * 1847\
x<sub>3</sub> = 8519281 = 79 * 107839\
x<sub>4</sub> = 16218068 = 2^2 * 17 * 79 * 3019\
x<sub>5</sub> = 17492496 = 2^4 * 3 * 7 * 79 * 659\
x<sub>6</sub> = 18289922 = 2 * 7 * 23 * 79 * 719\
x'<sub>6</sub> = 26224366 = 2 * 7 * 79 * 131 * 181\
x'<sub>5</sub> = 26590452 = 2^2 * 3 * 7 * 79 * 4007\
x'<sub>4</sub> = 27093208 = 2^3 * 79 * 163 * 263\
x'<sub>3</sub> = 28657487 = 79 * 362753\
x'<sub>2</sub> = 28894803 = 3 * 7 * 79 * 17417\
x'<sub>1</sub> = 28906206 = 2 * 3 * 7 * 311 * 2213

a(5) = 48988659276962496\
x<sub>1</sub> = 38787 = 3 * 7 * 1847\
x<sub>2</sub> = 107839 = 107839\
x<sub>3</sub> = 205292 = 2^2 * 17 * 3019\
x<sub>4</sub> = 221424 = 2^4 * 3 * 7 * 659\
x<sub>5</sub> = 231518 = 2 * 7 * 23 * 719\
x'<sub>5</sub> = 331954 = 2 * 7 * 131 * 181\
x'<sub>4</sub> = 336588 = 2^2 * 3 * 7 * 4007\
x'<sub>3</sub> = 342952 = 2^3 * 163 * 263\
x'<sub>2</sub> = 362753 = 362753\
x'<sub>1</sub> = 365757 = 3 * 7 * 17417

a(4) = 6963472309248\
x<sub>1</sub> = 2421 = 3^2 * 269\
x<sub>2</sub> = 5436 = 2^2 * 3^2 * 151\
x<sub>3</sub> = 10200 = 2^3 * 3 * 5^2 * 17\
x<sub>4</sub> = 13322 = 2 * 6661\
x'<sub>4</sub> = 16630 = 2 * 5 * 1663\
x'<sub>3</sub> = 18072 = 2^3 * 3^2 * 251\
x'<sub>2</sub> = 18948 = 2^2 * 3 * 1579\
x'<sub>1</sub> = 19083 = 3 * 6361

a(3) = 87539319\
x<sub>1</sub> = 167 = 167\
x<sub>2</sub> = 228 = 2^2 * 3 * 19\
x<sub>3</sub> = 255 = 3 * 5 * 17\
x'<sub>3</sub> = 414 = 2 * 3^2 * 23\
x'<sub>2</sub> = 423 = 3^2 * 47\
x'<sub>1</sub> = 436 = 2^2 * 109

a(2) = 1729\
x<sub>1</sub> = 1\
x<sub>2</sub> = 9 = 3^2\
x'<sub>2</sub> = 10 = 2 * 5\
x'<sub>1</sub> = 12 = 2^2 * 3

a(1) = 2\
x<sub>1</sub> = 1\
x'<sub>1</sub> = 1
