### 1891.Cutting-Ribbons

非常套路的二分搜值。猜测长度为len，贪心数一下每一条能割出多少块。大于等于k的话就往小猜（注意此时的len已经是一个可行解），否则就往大猜。