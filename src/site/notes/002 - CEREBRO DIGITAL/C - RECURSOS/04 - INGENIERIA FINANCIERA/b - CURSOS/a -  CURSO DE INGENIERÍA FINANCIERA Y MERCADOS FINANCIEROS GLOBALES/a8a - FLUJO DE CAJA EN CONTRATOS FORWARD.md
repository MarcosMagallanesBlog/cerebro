---
{"dg-publish":true,"permalink":"/002-cerebro-digital/c-recursos/04-ingenieria-financiera/b-cursos/a-curso-de-ingenieria-financiera-y-mercados-financieros-globales/a8a-flujo-de-caja-en-contratos-forward/"}
---

# Flujos de caja en contratos Forward

==Los contratos Forward no implican flujos de caja al inicio; solo generan flujo al momento de su **ejecución final**.==

- En **t = 0** (firma):
    - No hay movimiento de dinero. Solo se firma el acuerdo.
- En **t = T** (ejecución):
    - Si el contrato es de **compra** de dólares:
        - Se paga el precio acordado en soles (ej. -2.86 soles)
        - Se recibe la moneda (ej. +1 USD)
    - Si el contrato es de **venta**:
        - Se entrega la moneda (-1 USD)
        - Se recibe el pago (+2.86 soles)
- Este flujo puede variar si se liquida por diferencia (en vez de entrega física).



# Funcionamiento de los Contratos Forward

## 📈 Gráfica: Compra Forward (Posición Larga)

- **Ejes:**
  - X: Tipo de cambio final (Soles/USD)
  - Y: Ganancia o pérdida (Soles/USD)
- **Precio pactado:** 2,82
- **Ganancia:** si el tipo de cambio final > 2,82
- **Pérdida:** si el tipo de cambio final < 2,82
- **Ecuación:**  
  `Ganancia = S_t - 2,82`

![Pasted image 20250423220234.png](/img/user/img/user/900%20-%20ANEXO/Pasted%20image%2020250423220234.png)

---

## 📉 Gráfica: Venta Forward (Posición Corta)

- **Ejes:**
  - X: Tipo de cambio final (Soles/USD)
  - Y: Ganancia o pérdida (Soles/USD)
- **Precio pactado:** 2,82
- **Ganancia:** si el tipo de cambio final < 2,82
- **Pérdida:** si el tipo de cambio final > 2,82
- **Ecuación:**  
  `Ganancia = 2,82 - S_t`

![Pasted image 20250423220240.png](/img/user/img/user/900%20-%20ANEXO/Pasted%20image%2020250423220240.png)

---

## Insights clave

- Se denomina **posición larga** al contrato de compra forward: se espera recibir el activo (divisas).
- Se denomina **posición corta** al contrato de venta forward: se espera entregar el activo.
- Las gráficas son **líneas rectas** que cruzan el eje horizontal en el punto del precio pactado.

