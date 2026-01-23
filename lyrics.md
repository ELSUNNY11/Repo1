# Información sobre la canción "La Flaca" de Jarabe de Palo

cancion = {
    "titulo": "La Flaca",
    "autor_compositor": "Pau Donés",
    "banda": "Jarabe de Palo",
    "anio_grabacion": 1996,
    "album": "La Flaca",
    "discografica": "Virgin Records",
    "genero": ["Pop Rock", "Latin Rock"],
    "duracion": "4:10",
    "productor": "Joe Dworniak",
    "impacto": "Sencillo que catapultó a Jarabe de Palo a la fama internacional",
    "inspiracion": "Modelo cubana Alsoris Guzmán, conocida en La Habana"
}

# Fragmento representativo de la letra (no completo por derechos de autor)
letra_fragmento = """
En la vida conocí
Mujer igual a la flaca
Coral negro de La Habana
Tremendísima mulata
"""

# Mostrar información
print("=== Datos de la canción ===")
for clave, valor in cancion.items():
    print(f"{clave}: {valor}")

print("\n=== Fragmento de la letra ===")
print(letra_fragmento)

