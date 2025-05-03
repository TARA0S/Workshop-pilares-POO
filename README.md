# Workshop-pilares-POO
# Respuesta teorica:Los cuatro pialres de la programacion orientada a objetos son polimorfismo,encapsulamiento,herencia y abstracion 
# 1)La diferencia entre encapsulamiento y abstracion es que el encapsulamiento oculta datos internos y controla el acceso,mientras que la abstracion oculta complejidad y muestra solo lo importante para el usuario. 
# 2)Polimorfismo

# Codigo corregido
class Dog:
    def __init__(self, name):
        self.name = name  

    def speak(self):
        return "woof"

dog = Dog("Bobby")
print(dog.name)  
