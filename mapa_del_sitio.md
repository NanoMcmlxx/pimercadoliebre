```mermaid
graph LR
A((home))-->B{registrado?}--->|si|C[loguin]-->E[Producto]
C-.->D
B--->|no|D[registro]-->E[Producto]
E[Producto]--->F[Carrito]-->G((exit))
```
