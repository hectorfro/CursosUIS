# 📋 GUÍA DE TRABAJO COLABORATIVO 

## Para Estudiantes de Laboratorio de Física II

---

## ⚠️ REGLA DE ORO

**TODOS LOS INTEGRANTES DEBEN TRABAJAR EN EL MISMO ARCHIVO DE COLAB.**

❌ **NO** trabajen en copias separadas  
❌ **NO** se pasen el archivo por WhatsApp  
❌ **NO** hagan "merge" manual al final  

✅ **SÍ** trabajen en un único cuaderno compartido en Google Drive  
✅ **SÍ** usen los permisos de edición de Colab  
✅ **SÍ** coordínense para no editar la misma celda simultáneamente  

---

## 📝 PASO A PASO DETALLADO

### **PASO 1: APERTURA INICIAL DEL NOTEBOOK** (Solo 1 estudiante del grupo)

**Responsable:** Cualquier integrante del equipo (recomendado: Estudiante C - Analista)

**Acciones:**

1. Ingresa a Google Classroom
2. Abre la tarea asignada por el profesor
3. Haz clic en el enlace del archivo `.ipynb` (plantilla del laboratorio)
4. **IMPORTANTE:** Colab abrirá el archivo en modo **"Solo lectura"** o **"Vista previa"**
5. Ve al menú: **Archivo → Guardar una copia en Drive**
6. Se creará una copia en tu carpeta "Colab Notebooks" de Google Drive
7. **Renombra el archivo** según las instrucciones del profesor:
   - Formato: `GXX_Practica00.ipynb`
   - Ejemplo: `G04_Practica00.ipynb` (Grupo 04)

✅ **Verificación:** El archivo debe aparecer en tu Google Drive con el nombre correcto.

---

### **PASO 2: COMPARTIR CON EL EQUIPO** (El mismo estudiante del Paso 1)

**⚠️ ESTE ES EL PASO MÁS CRÍTICO**

**Acciones:**

1. Con el archivo abierto en Colab, busca el botón azul **"Compartir"** (esquina superior derecha)
2. Haz clic en **"Compartir"**
3. En la ventana emergente, agrega los correos  de tus 2 compañeros:
   - `estudiante2@gmail.com`
   - `estudiante3@gmail.com`
4. **MUY IMPORTANTE:** En el menú desplegable al lado de cada correo, selecciona **"Editor"** (NO "Lector" ni "Comentarista")
5. Desmarca la opción **"Notificar a las personas"** si no quieres enviar correos
6. Haz clic en **"Enviar"** o **"Listo"**
7. **Copia el enlace del archivo** y envíalo al grupo de WhatsApp en caso de tenerlo

**Formato del mensaje sugerido:**
```
🔗 Enlace del Lab 1 - Péndulo Simple:
[pegar enlace aquí]

⚠️ Todos debemos trabajar en ESTE archivo.
No hagan copias. 

Roles asignados:
- Estudiante A (Modelador): [Nombre]
- Estudiante B (Programador): [Nombre]  
- Estudiante C (Analista): [Nombre]
```

✅ **Verificación:** Los otros 2 compañeros deben poder abrir el enlace y ver el notebook completo en modo edición.

---

### **PASO 3: CONFIRMACIÓN DE ACCESO** (Los otros 2 estudiantes)

**Responsables:** Estudiantes que NO crearon el archivo

**Acciones:**

1. Abre el enlace compartido en WhatsApp
2. Si Google Drive te pide iniciar sesión, usa tu **correo**
3. El archivo debe abrirse en Colab en modo **edición** (no "solo lectura")
4. **Prueba de escritura:** Ve a la celda de la portada y escribe tu nombre en el rol asignado
5. Presiona `Ctrl + S` o ve a **Archivo → Guardar** para guardar los cambios
6. Confirma en el grupo que ya tienes acceso

✅ **Verificación:** Si puedes escribir y guardar, el acceso está correcto.

❌ **Problema común:** Si dice "Solo lectura", pide al compañero que te dio el enlace que verifique que te dio permisos de "Editor", no de "Lector".

---

### **PASO 4: ASIGNACIÓN Y REGISTRO DE ROLES** (Los 3 estudiantes juntos)

**Responsables:** Todo el equipo

**Acciones:**

1. **ANTES de escribir cualquier cosa técnica**, completen la portada del notebook
2. Vayan a la celda Markdown de la portada (primera celda del documento)
3. Completen la información:

```markdown
**Grupo:** 04

**Integrantes:**
1. **Estudiante A (Modelador):** Juan Pérez Gómez
2. **Estudiante B (Programador):** María López Díaz
3. **Estudiante C (Analista):** Carlos Ruiz Sánchez

**Fecha:** 15/02/2026
```

4. Guarden los cambios (`Ctrl + S`)

✅ **Verificación:** La portada debe tener los 3 nombres completos y los roles asignados.

---

### **PASO 5: DESARROLLO COLABORATIVO** (Los 3 estudiantes)

**Responsables:** Cada estudiante en su sección asignada

**Reglas de Oro:**

1. **Cada estudiante trabaja solo en las secciones de su rol:**
   - **Estudiante A:** Secciones 1-4 (Resumen, Objetivos, Introducción, Metodología)
   - **Estudiante B:** Secciones 5-6 (Datos, Análisis, Código, Tablas, Figuras)
   - **Estudiante C:** Secciones 7-9 (Discusión, Conclusiones, Referencias)

2. **Coordinación en tiempo real:**
   - Usen el chat de comentarios de Colab (icono de bocadillo 💬)
   - Si necesitan algo de un compañero: `@NombreCompañero, ¿ya terminaste la ecuación?`
   - **NO editen la misma celda al mismo tiempo** (Colab puede sobrescribir cambios)

3. **Guardado frecuente:**
   - Presionen `Ctrl + S` cada vez que terminen una celda
   - Colab guarda automáticamente, pero es mejor asegurarse

4. **Revisión cruzada:**
   - Cuando termines tu sección, avisa al grupo
   - Otro compañero debe leerla y dar OK antes de continuar

**Ejemplo de flujo de trabajo:**

```
[Día 1]
Estudiante A: Redacta Introducción y Marco Teórico
Estudiante B: Espera a que A termine las ecuaciones
Estudiante C: Lee la guía de incertidumbres

[Día 2]
Estudiante A: Completa Metodología
Estudiante B: Ingresa datos experimentales y ejecuta código
Estudiante C: Observa resultados preliminares

[Día 3]
Estudiante A: Revisa redacción general
Estudiante B: Genera Tabla 1 y Figura 1
Estudiante C: Escribe Discusión basándose en resultados

[Día 4]
Estudiante C: Escribe Conclusiones y verifica Referencias
Todo el equipo: Revisión final
```

✅ **Verificación:** Cada sección debe estar completa según el rol asignado.

---

### **PASO 6: VERIFICACIÓN FINAL** (Todo el equipo)

**Responsable principal:** Estudiante C (Analista)

**Checklist antes de entregar:**

**📋 Contenido:**
- [ ] Portada con nombres completos y roles asignados
- [ ] Todas las secciones 1-9 completas
- [ ] Ecuaciones en LaTeX renderizadas correctamente
- [ ] Datos experimentales ingresados 
- [ ] Tablas generadas y visible
- [ ] Figuras generadas y visible
- [ ] Referencias citadas como [1], [2], [3]... en el texto
- [ ] Sin celdas con errores de ejecución

**🔢 Código:**
- [ ] Todas las celdas de código ejecutadas en orden
- [ ] Sin mensajes de error en las salidas
- [ ] Los resultados numéricos tienen sentido físico

**✍️ Redacción:**
- [ ] Sin errores ortográficos evidentes
- [ ] Redacción clara y coherente
- [ ] Los valores tienen unidades correctas

✅ **Verificación:** Si todo está marcado, pueden proceder a la entrega.

---

### **PASO 7: GENERACIÓN DEL PDF** (Estudiante C)

**Responsable:** Estudiante C (Analista)

**Acciones:**

1. Asegúrate de que todas las celdas estén ejecutadas (la recomendación es ir a **Edit-> Clear all outputs** y luego **Run-> Restart session and run all**. Aquí nos aseguramos que todo el Notebook se ejecuta correctamente.
2. Ve al menú: **Archivo → Imprimir**
3. En la ventana de impresión:
   - Destino: **Guardar como PDF**
   - Diseño: **Vertical**
   - Márgenes: **Predeterminado**
4. Haz clic en **Guardar**
5. Nombra el archivo según instrucciones del profesor:
   - Formato: `GXX_Practica00.pdf`
   - Ejemplo: `G04_Practica00.pdf`
6. Guarda el PDF en tu carpeta de descargas

**⚠️ Problemas comunes al generar PDF:**

**Problema:** Las ecuaciones LaTeX no se ven bien en el PDF
**Solución:** Espera 2-3 segundos antes de imprimir para que se rendericen

**Problema:** El PDF sale cortado o con formato raro
**Solución:** Usa Chrome o Edge. Firefox a veces da problemas.

**Problema:** Las gráficas no aparecen en el PDF
**Solución:** Vuelve a ejecutar la celda de la gráfica, espera que se muestre, luego imprime.

✅ **Verificación:** Abre el PDF y verifica que TODO se vea bien (texto, ecuaciones, tabla, figura).

---

### **PASO 8: ENTREGA EN LA PLATAFORMA** (Estudiante C principalmente)

**Responsable principal:** Estudiante C (Analista)  
**Responsables secundarios:** Todos deben marcar como "Entregado"

**Acciones:**

1. **Estudiante C:**
   - Ingresa a Google Classroom
   - Busca la tarea correspondiente
   - Haz clic en **"Agregar o crear"** → **"Archivo"**
   - Selecciona el PDF generado: `GXX_Practica01_Pendulo.pdf`
   - Haz clic en **"Entregar"**
   - Confirma la entrega

2. **Estudiantes A y B:**
   - Ingresan a Classroom
   - Ven la tarea y verifican que el archivo PDF ya está adjunto
   - Hacen clic en **"Marcar como completado"** o **"Entregar"**
   - Confirman

**⚠️ IMPORTANTE:**
- Los 3 estudiantes deben aparecer como "Entregado" en Classroom
- Solo se sube 1 PDF (el del Estudiante C), pero todos marcan la tarea
- No suban el archivo `.ipynb` a menos que el profesor lo solicite

✅ **Verificación:** En Classroom debe aparecer:
- Estado: **Entregado**
- Archivo adjunto: **GXX_Practica00.pdf**
- Los 3 nombres marcados como entregado

---

## ❌ ERRORES COMUNES A EVITAR

### Error 1: Trabajar en copias separadas
**Síntoma:** Cada estudiante tiene su propia versión del archivo  
**Consecuencia:** Al final hay 3 notebooks diferentes y deben hacer "merge" manual (pesadilla)  
**Solución:** TODOS trabajan en el mismo enlace desde el Paso 2

### Error 2: Olvidar dar permisos de "Editor"
**Síntoma:** Los compañeros ven el archivo en "Solo lectura"  
**Consecuencia:** No pueden escribir nada  
**Solución:** El dueño del archivo debe ir a "Compartir" y cambiar de "Lector" a "Editor"

### Error 3: Editar la misma celda simultáneamente
**Síntoma:** Los cambios de uno sobrescriben los del otro  
**Consecuencia:** Se pierde trabajo  
**Solución:** Coordínense por WhatsApp. Si dos necesitan editar, uno espera

### Error 4: No ejecutar las celdas de código
**Síntoma:** El PDF sale sin resultados, tablas ni figuras  
**Consecuencia:** Informe incompleto  
**Solución:** Antes de generar PDF, ve a **Entorno de ejecución → Ejecutar todas**

### Error 5: Entregar con datos de ejemplo
**Síntoma:** El informe tiene los datos que venían en la plantilla  
**Consecuencia:** Calificación muy baja  
**Solución:** Estudiante B debe reemplazar los arrays de datos con los valores reales del experimento

### Error 6: No verificar el PDF antes de entregar
**Síntoma:** El PDF se ve mal (ecuaciones rotas, figuras cortadas)  
**Consecuencia:** Mala presentación, puntos perdidos  
**Solución:** Siempre abrir y revisar el PDF completo antes de subirlo

---

## 📞 ¿NECESITAS AYUDA?

**Si tienes problemas técnicos:**

1. **Problemas de acceso:** Verifica que estás usando tu correo que corresponde
2. **Problemas de edición:** Pide al dueño del archivo que revise los permisos
3. **Problemas de código:** Revisa que ejecutaste todas las celdas en orden
4. **Problemas de PDF:** Intenta con otro navegador (Chrome recomendado)

**Si nada funciona:**
- Consulta con el profesor en horario de atención
- Escribe al foro del curso en Classroom
- Pregunta a compañeros de otros grupos

---

## ✅ RESUMEN RÁPIDO

**Para el estudiante que crea el archivo:**
1. Guardar copia en Drive
2. Renombrar según formato
3. Compartir con permisos de "Editor" a los 2 compañeros

**Para todos los estudiantes:**
4. Llenar portada con nombres y roles
5. Trabajar en las secciones asignadas
6. Coordinar por chat de Colab
7. Guardar versiones importantes (hitos)

**Para el Analista (Estudiante C):**
8. Verificar que todo esté completo
9. Generar PDF y revisarlo
10. Subir a Classroom
11. Confirmar que todos marcaron "Entregado"

---

**¡Éxito en su laboratorio!** 🔬📊✅
