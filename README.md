import matplotlib.pyplot as plt
import numpy as np

# Datos para graficar
x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)

# Crear el gráfico
plt.figure(figsize=(10, 6))

plt.plot(x, y1, 'b-', linewidth=2, label='Seno (sin(x))')
plt.plot(x, y2, 'r--', linewidth=2, label='Coseno (cos(x))')

plt.title('Ejemplo básico de Matplotlib', fontsize=16)
plt.xlabel('Eje X', fontsize=12)
plt.ylabel('Eje Y', fontsize=12)
plt.grid(True, alpha=0.3)
plt.legend(fontsize=12)
plt.axhline(0, color='black', linewidth=0.5)
plt.axvline(0, color='black', linewidth=0.5)

plt.show()   # Muestra el gráfico en pantalla# Usos-b-sico-de-Matplotlib
Pequeño 
