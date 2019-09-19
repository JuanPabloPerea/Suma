# Suma Juan Pablo Perea Hernandez 20162020074
suma::[Int]->[Int]->[Int]
suma xs [] = []
suma [] ys = []
suma (x:xs) (y:ys) = (x+y) : suma xs ys
