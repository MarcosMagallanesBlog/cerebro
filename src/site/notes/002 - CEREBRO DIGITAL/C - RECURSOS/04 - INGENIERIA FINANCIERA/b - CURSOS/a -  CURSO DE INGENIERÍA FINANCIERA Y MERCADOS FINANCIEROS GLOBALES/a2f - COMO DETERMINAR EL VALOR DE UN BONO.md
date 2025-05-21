---
{"dg-publish":true,"permalink":"/002-cerebro-digital/c-recursos/04-ingenieria-financiera/b-cursos/a-curso-de-ingenieria-financiera-y-mercados-financieros-globales/a2f-como-determinar-el-valor-de-un-bono/"}
---

# ¿COMO DETERMINAR EL VALOR DE UN BONO?

El valor de un bono se calcula como el ==valor presente de los flujos de caja futuros que el bono generará== (cupones periódicos + devolución del principal). Este valor depende de la tasa del bono (tasa cupón) y de la tasa de mercado (yield o TIR).

# Fórmula general
![Pasted image 20250521112817.png](/img/user/img/user/900%20-%20ANEXO/Pasted%20image%2020250521112817.png)
B = Σ [ C / (1 + r)^t ] + F / (1 + r)^n

Donde:  
- B = Valor del bono (precio hoy)  
- C = Pago periódico (cupón)
- F = Valor facial (principal)
- r = Tasa de descuento por período (yield / número de pagos por año)
- n = Número total de pagos (años × pagos por año)

# Variables claves

| Variable       | Símbolo | Valor | Descripción                            |
| -------------- | ------- | ----- | -------------------------------------- |
| Valor Facial   | F       | 100   | Principal a devolver al final del bono |
| Tasa Cupón     | c       | 2%    | Tasa anual que paga el bono            |
| Yield del Bono | y       | 2%    | Tasa de mercado o exigida              |
| Término (años) | Na      | 3     | Duración total del bono                |
| Pagos por año  | m       | 2     | Frecuencia de pagos anuales            |
| Nº total pagos | n       | 6     | Total de pagos (Na × m)                |

# Flujo de caja
En la hoja Excel se presentan:  
- Cupones semestrales de 1 (porque 2% anual ÷ 2 = 1%)  
- Valor final: 100 al sexto pago  
  
**Cálculo del pago periódico:** 
C = (c × F) / m = (0.02 × 100) / 2 = 1

**Tasa por período:**  
r = y / m = 0.02 / 2 = 0.01 (1% cada 6 meses)

**Resultado:**  
El precio del bono cuando tasa cupón = tasa de mercado → B = 100

# Interpretación

- Si la tasa de mercado sube, el valor presente de los flujos disminuye → el bono vale menos que 100 (descuento).  
- Si la tasa de mercado baja, los flujos se valorizan más → el bono vale más que 100 (prima).

[[002 - CEREBRO DIGITAL/C - RECURSOS/04 - INGENIERIA FINANCIERA/b - CURSOS/a -  CURSO DE INGENIERÍA FINANCIERA Y MERCADOS FINANCIEROS GLOBALES/a2fa - RELACIÓN YIELD - VALOR DEL BONO\|a2fa - RELACIÓN YIELD - VALOR DEL BONO]]