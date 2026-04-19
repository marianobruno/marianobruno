Diseño sistemas donde la IA no asiste — opera.
 
---
 
La mayoría usa IA para escribir código más rápido. Yo la uso para reemplazar operaciones enteras: desde la evaluación de una idea de negocio hasta la ejecución automatizada de procesos que antes requerían equipos.
 
No es ciencia ficción. Es un cambio de arquitectura: en vez de personas ejecutando tareas con herramientas, son **agentes autónomos ejecutando procesos dentro de reglas que un humano diseñó**. La intervención humana pasa de operación a dirección.
 
Estoy construyendo en esa dirección. Esto es lo que hago y cómo pienso.
 
---
 
## Qué construyo
 
**Frameworks para el ciclo completo: idea → validación → arquitectura → build**
Antes de escribir una línea de código, la IA me ayuda a destruir la idea. Si sobrevive, recién ahí construyo. Esto no es "vibe coding" — es un proceso de diseño donde la IA actúa como un segundo cerebro crítico.
 
**Infraestructura propia para correr IA de forma autónoma**
VPS propio con Ollama, n8n para orquestación, PostgreSQL como fuente de verdad. Sin dependencia de plataformas que mañana cambian sus precios o sus términos. Control total.
 
**Sistemas de acceso y gestión para ecosistemas internos**
Cuando experimentás rápido, el desorden escala igual de rápido. Construyo las capas de orden que permiten seguir experimentando sin perder visibilidad.
 
---
 
## Proyectos
 
### [Gatekeeper Hub](https://github.com/marianobruno)
Capa de acceso centralizada para PoCs y herramientas internas. Nace de un problema concreto: cuando tenés 5, 10, 15 experimentos corriendo, necesitás un punto de entrada único que no agregue fricción. Eso es Gatekeeper.
 
### Paperclip — referencia de paradigma
[paperclip.ing](https://paperclip.ing/) explora la idea de organizaciones donde los agentes sostienen la operación con mínima intervención humana. No es mi proyecto, pero es la mejor referencia pública de hacia dónde va esto. Lo sigo de cerca y construyo en la misma línea.
 
---
 
## Cómo pienso
 
**Si es complejo, no está terminado.** La complejidad no es señal de sofisticación — es señal de que todavía no entendí bien el problema.
 
**Lo que no se puede operar, no sirve.** Todo lo que construyo tiene que poder ser mantenido por alguien que no lo construyó.
 
**Evaluar antes de construir.** La línea de código más cara es la que no debería haberse escrito. Cada proyecto pasa por viabilidad técnica y de negocio antes de existir.
 
**Documentar es parte del sistema, no un extra.** Si no tiene contexto, no es mantenible. Si no es mantenible, no escala.
 
---
 
## Stack
 
Node.js · PostgreSQL · Docker · Nginx · Ollama · n8n · Google OAuth · JWT
 
Infra: VPS propio · Ollama (llama3.2) · n8n como orquestador · PostgreSQL como fuente de verdad


