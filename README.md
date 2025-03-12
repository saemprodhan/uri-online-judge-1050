# uri-online-judge-1050
Time limit: 1
ddd_map = {
    61: "Brasilia",
    71: "Salvador",
    11: "Sao Paulo",
    21: "Rio de Janeiro",
    32: "Juiz de Fora",
    19: "Campinas",
    27: "Vitoria",
    31: "Belo Horizonte"
}

# Read input
ddd = int(input())

# Print corresponding city or default message
print(ddd_map.get(ddd, "DDD nao cadastrado"))
