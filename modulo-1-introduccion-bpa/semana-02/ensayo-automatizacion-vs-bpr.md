Ensayo: Automatización vs. BPR — Caso BIXO

Empresa (hipotética): BIXO, mi tienda e-commerce de pixel art (prototipo con Node.js/Express y frontend HTML/JS).

El proceso: cobro y factura al cerrar una compra
Antes de automatizarlo. Así funcionaría un negocio chico como BIXO si arrancara sin sistema: alguien (yo, en este caso) arma la factura a mano, calcula el total y coordina el pago aparte, por transferencia, WhatsApp o lo que sea. Funciona, pero depende de que esa persona esté disponible justo en ese momento, y entre más pedidos entran, más se traba todo.
Después de automatizarlo. Con el checkout de BIXO, el sistema genera la factura en PDF automáticamente con jsPDF, usando los datos reales del pedido, y el cliente paga ahí mismo con un QR de Yappy integrado al flujo. Nadie tiene que revisar nada: el pedido queda facturado y cobrado en el mismo momento en que se cierra la compra.

¿Automatización incremental o BPR?

Para mí esto es automatización incremental, no BPR. El proceso en el fondo sigue siendo el mismo: el cliente compra, se genera una factura y se cobra. Lo que cambió es quién lo hace (antes una persona, ahora el sistema), y eso lo hace más rápido y con menos margen de error. Pero no rediseñé la lógica del proceso desde cero, no eliminé pasos y no cambié el modelo de negocio; solo automaticé una tarea que antes era manual.
Si en vez de eso hubiera descartado el checkout tradicional y armado, por ejemplo, un modelo de suscripción o un chatbot que negocia el precio con el cliente, ahí sí hablaríamos de BPR, porque se estaría repensando el proceso completo y no solo agilizando un paso puntual.

Declaración de uso de IA
Para este entregable utilicé las siguientes herramientas de IA:
Claude (Anthropic): apoyo para organizar las ideas y redactar el borrador del ensayo a partir de la información de mi proyecto BIXO.
Google NotebookLM: herramienta de apoyo para el estudio y consulta del material.
El caso (BIXO) corresponde a un proyecto propio, y el contenido final fue revisado por mí antes de entregarlo.