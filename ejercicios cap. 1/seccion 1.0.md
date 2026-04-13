## Ejercicios
### Ejercicio 1.0.2. Encontrar puntos fijos

$$
\dot{x} = -x+x^{2}\
$$

Se resuelve la ecuación $$\   f(x) = 0   \$$ para obtener:

$$
x = 0 \quad \text{y} \quad x = 1
$$

Verificamos estabilidad con linealización: 

$$
\frac{df}{dx} = f'(x) = -1 + 2x 
$$

Se evalúa cada punto fijo en la derivada. $$\ f'(0) = -1 < 0 $$ . Éste es un atractor asintóticamente estable. $$\ f'(1) = 1 > 0 $$. Éste es un punto fijo inestable, repulsor. 

Analicemos el signo de $$\ f(x) $$ en los intervalos: 

$$ 
\(-∞, 0):    f(x) = x(x-1) > 0  →  x \quad \text{crece} → 0
$$

$$ 
\(0, 1):     f(x) < 0           →  x decrece → 0 
$$
$$
\ (1, +∞):    f(x) > 0           →  x crece → +∞ 
$$



