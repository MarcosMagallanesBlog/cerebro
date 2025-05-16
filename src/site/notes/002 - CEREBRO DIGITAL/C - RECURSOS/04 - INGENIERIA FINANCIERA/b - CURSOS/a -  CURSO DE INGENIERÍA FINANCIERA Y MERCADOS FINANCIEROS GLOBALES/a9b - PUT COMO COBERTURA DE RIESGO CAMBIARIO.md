---
{"dg-publish":true,"permalink":"/002-cerebro-digital/c-recursos/04-ingenieria-financiera/b-cursos/a-curso-de-ingenieria-financiera-y-mercados-financieros-globales/a9b-put-como-cobertura-de-riesgo-cambiario/"}
---

# PUT COMO COBERTURA DE RIESGO CAMBIARIO
## Contenido
Una opción *put* es un contrato que otorga el derecho (pero no la obligación) de vender dólares a un precio fijo (precio strike), lo cual protege a una empresa exportadora ante la posible caída del tipo de cambio. Este instrumento resulta útil cuando una empresa tiene una cuenta por cobrar en dólares, y existe riesgo de que el dólar baje y por lo tanto reciba menos en moneda local (soles).

La compra de una *put* implica:
- Pagar una **prima** (ejemplo: 0.15 soles).
- Fijar un **precio strike** (ejemplo: 2.80 soles por dólar).
- Ejercer el derecho **sólo si conviene**, es decir, si el tipo de cambio al vencimiento es menor al strike.

Esto permite:
- Asegurar un **mínimo ingreso** (strike menos prima, por ejemplo: 2.65).
- Beneficiarse si el tipo de cambio sube (a diferencia del *forward*).
- Cobertura flexible frente a escenarios inciertos.

### Comparación con el Forward
| Característica     | [[002 - CEREBRO DIGITAL/C - RECURSOS/04 - INGENIERIA FINANCIERA/b - CURSOS/a -  CURSO DE INGENIERÍA FINANCIERA Y MERCADOS FINANCIEROS GLOBALES/a8 - FORWARD\|Forward]] | [[002 - CEREBRO DIGITAL/C - RECURSOS/04 - INGENIERIA FINANCIERA/b - CURSOS/a -  CURSO DE INGENIERÍA FINANCIERA Y MERCADOS FINANCIEROS GLOBALES/a9d - PUT\|Put]]              |
| ------------------ | ------------------------- | ------------------------------- |
| Obligación         | Sí, se ejecuta siempre    | No, se ejecuta solo si conviene |
| Costo inicial      | Cero                      | Pago de prima                   |
| Participa en alza  | No                        | Sí                              |
| Protección mínima  | Fija (precio contratado)  | Strike – prima                  |
| Libertad de acción | Nula                      | Alta                            |

---
## Interpretación Gráfica
![Pasted image 20250508182528.png](/img/user/img/user/900%20-%20ANEXO/Pasted%20image%2020250508182528.png)
(amarillo, una factura por cobrar en usd a un año)
(rojo, put a un año)


## COMPARACIÓN COBERTURA CON VENTA OPCION PUT Y COBERTURA CON VENTA [[002 - CEREBRO DIGITAL/C - RECURSOS/04 - INGENIERIA FINANCIERA/b - CURSOS/a -  CURSO DE INGENIERÍA FINANCIERA Y MERCADOS FINANCIEROS GLOBALES/a8b -FOROWARDS COMO COBERTURA DE RIESGO CAMBIARIO\|FOROWARD]]
## Conclusión
El uso de una *put* como herramienta de cobertura brinda una **protección flexible** ante la caída del dólar, permitiendo a la empresa fijar un mínimo ingreso en moneda local sin renunciar a ganancias potenciales si el tipo de cambio sube. Es especialmente útil cuando hay **incertidumbre sobre el comportamiento del tipo de cambio**.

