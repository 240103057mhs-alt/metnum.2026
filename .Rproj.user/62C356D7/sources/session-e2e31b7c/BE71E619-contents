# implementasi satu panel
f <- function (x) x^2

a <- 0
b <- 2

garistengah <- (b - a) * f((a + b) / 2)

trapesium <- (b - a) / 2 * (f(a) + f(b))

h <- (b - a) / 2
simpson13 <- h / 3 * (f(a) + 4*f((a + b) / 2) + f(b))

c(garistengah = garistengah,
  trapesium = trapesium,
  simpson13 = simpson13)