# Crear la colección de productos
db.createCollection("productos")

# Insertar productos en la colección
db.productos.insertMany([
  { nombre: "Camiseta", precio: 20, categoria: "Ropa" },
  { nombre: "Laptop", precio: 1200, categoria: "Electrónica" },
  { nombre: "Taza", precio: 5, categoria: "Hogar" }
])

# Obtener los datos de la coleccion
db.getCollection('productos').find({});