📘 RESUMEN CLAVE – DERIVADAS PARA TAYLOR

---

## 🔹 1️⃣ DERIVADAS BASE (de memoria absoluta)

Estas deben salir automáticas:

$$
\frac{d}{dx}(c) = 0
$$

$$
\frac{d}{dx}(x^n) = nx^{n-1}
$$

$$
\frac{d}{dx}(e^x) = e^x
$$

$$
\frac{d}{dx}(a^x) = a^x \ln a
$$

$$
\frac{d}{dx}(\ln x) = \frac{1}{x}
$$

$$
\frac{d}{dx}(\ln(1+x)) = \frac{1}{1+x}
$$

---

## 🔹 Trigonométricas importantes

$$
\frac{d}{dx}(\sin x) = \cos x
$$

$$
\frac{d}{dx}(\cos x) = -\sin x
$$

$$
\frac{d}{dx}(\tan x) = \sec^2 x
$$

Para Taylor normalmente usamos solo seno y coseno.

---

# 🔹 2️⃣ REGLAS FUNDAMENTALES

---

## 📌 Regla del producto

Si:
$$
f(x)=u(x)v(x)
$$

Entonces:

$$
f'(x)=u'v + uv'
$$

⚠ Error típico: olvidar uno de los dos términos.

---

## 📌 Regla del cociente

Si:
$$
f(x)=\frac{u}{v}
$$

Entonces:

$$
f'(x)=\frac{u'v - uv'}{v^2}
$$

(Solo aparece ocasionalmente en Taylor.)

---

## 📌 Regla de la cadena (MUY IMPORTANTE)

Si:
$$
f(x)=g(h(x))
$$

Entonces:

$$
f'(x)=g'(h(x)) \cdot h'(x)
$$

Ejemplos:

$$
\frac{d}{dx}e^{3x}=3e^{3x}
$$

$$
\frac{d}{dx}\sin(2x)=2\cos(2x)
$$

$$
\frac{d}{dx}\sqrt{1+x}=\frac{1}{2}(1+x)^{-1/2}
$$

⚠ Error típico: olvidar multiplicar por la derivada interna.

---

# 🔹 3️⃣ Derivadas sucesivas (muy importante para Taylor)

Taylor necesita:

- (f(x))
- (f'(x))
- (f''(x))
- a veces (f'''(x))

Ejemplos clave:

---

## 📌 Exponencial

$$
f(x)=e^x
$$

Todas las derivadas son:

$$
f^{(n)}(x)=e^x
$$

---

## 📌 Seno

$$
\sin x
$$

Ciclo cada 4 derivadas:

$$
\sin x \rightarrow \cos x \rightarrow -\sin x \rightarrow -\cos x \rightarrow \sin x
$$

---

## 📌 Coseno

$$
\cos x \rightarrow -\sin x \rightarrow -\cos x \rightarrow \sin x \rightarrow \cos x
$$

---

## 📌 Potencias tipo raíz

$$
(1+x)^\alpha
$$

Derivadas:

$$
\alpha(1+x)^{\alpha-1}
$$

$$
\alpha(\alpha-1)(1+x)^{\alpha-2}
$$

$$
\alpha(\alpha-1)(\alpha-2)(1+x)^{\alpha-3}
$$

Este patrón es muy importante para Taylor.

---

# 🔹 4️⃣ Errores típicos en examen

❌ Olvidar signo en coseno
❌ Olvidar regla del producto
❌ Olvidar regla de la cadena
❌ No usar paréntesis
❌ Desorden algebraico

---

# 🔹 5️⃣ Lo que más importa para Taylor

Cuando construyas:

$$
T_n(x)
$$

Siempre necesitas:

- Evaluar derivadas en un punto
- No cometer errores de signo
- No equivocarte en factoriales
- Orden algebraico limpio

---

# 🎯 En resumen

Para dominar Taylor necesitas:

✔ Derivadas base automáticas
✔ Producto sólido
✔ Cadena sólida
✔ Capacidad de derivar dos veces sin confundirte

---

Si quieres, ahora hacemos un mini-test rápido de 5 preguntas para verificar que quedó claro antes de pasar al Bloque 3.
