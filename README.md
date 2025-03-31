# informaci-n-personal-
casandra muyolema 
# Crear un diccionario con información ficticia
informacion_personal = {
    "nombre": "Javier barbeco",
    "edad": 29,
    "ciudad": "Quito",
    "profesion": "Ingeniero"
}

# Acceder y modificar el valor de la clave "ciudad"
informacion_personal["ciudad"] = "riobamba"
# Agregar una nueva clave-valor para la profesion
informacion_personal["profesion"] = "Desarrollador de Software"

# Verificar si "telefono" existe, si no, agregarlo
if "telefono" not in informacion_personal:
    informacion_personal["telefono"] = "0987654321"

# Eliminar la clave "edad"
del informacion_personal["edad"]

# Imprimir el diccionario final
print(informacion_personal)
