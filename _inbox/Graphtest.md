# Probar gráficos

```mermaid

flowchart TD
	A[Start]
	B[Medium]
	C[Finish]
	
	A-- Main path --> B;
	A-. Secondary path .-> C;
	B-- Main path pt. 2 --> C ;
```