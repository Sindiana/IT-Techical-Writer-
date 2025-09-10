# Deret Fibonacci
```
start
  create fungsi f(n)
    if n <= 1
       kembalikan n
    else
       kembalikan f(n-1) + f(n-2)
  ENDIF

  tampilkan "Masukkan jumlah deret Fibonacci: "
  baca n

  tampilkan "Deret Fibonacci hingga n adalah:"

  untuk i = 0 sampai n-1
     tampilkan f(i)
end
