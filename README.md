def linea(pendiente, ordenada_origen, x):
    """
    Calcula el valor de y para una ecuación de línea dada una pendiente y ordenada al origen.
    
    Args:
        pendiente (float): La pendiente de la línea.
        ordenada_origen (float): El valor de la ordenada al origen.
        x (float): El valor de x para el cual deseas calcular y.
        
    Returns:
        float: El valor de y calculado.
    """
    y = pendiente * x + ordenada_origen
    return y

# Ejemplo de uso
pendiente = 2
ordenada_origen = 3
x_valor = 5
resultado = linea(pendiente, ordenada_origen, x_valor)
print(f"Para x = {x_valor}, y = {resultado}")
