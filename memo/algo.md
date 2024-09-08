# 今日勉強したテクニック
f(k) = sum a_{i+k}b_i, i=0,n-k
をk=0,...,n-1, について全部でO(nlogn)で計算するテク
c_i = b_{n-i}
で新たに数列cを定義してaとcのconvolutionで一気に
f(0),...,f(n-1)を計算できる。