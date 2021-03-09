# x vektor sa vrednostima visina

x <- c(188,178,193,167,184,202,182,175,172,190)

# y vektor sa idealnim tezinama za date visine

y <- c(81,70,85,55,75,95,74,62,60,80)

# relacija vraca koeficijente (-138.319, 1.158)

relacija <- lm(y~x)

print(relacija)

# predikcija nove vrednosti

nova_visina <- data.frame(x = 185)
rezultat <- predict(relacija, nova_visina)

print(rezultat) # 75.90009 ~ 76kg