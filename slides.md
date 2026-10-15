---
theme: seriph
title: "Protección de datos personales y hábeas data"
info: |
  Presentación basada en el material proporcionado.
  Marco constitucional argentino, Ley 25.326 y desafíos tecnológicos.
author: " "
lang: es-AR
transition: slide-left
mdc: true
---

# Protección de datos personales y hábeas data

## Marco jurídico argentino, derechos y desafíos tecnológicos

<div class="pt-8 text-sm opacity-70">
Constitución Nacional · Ley 25.326 · Jurisprudencia
</div>

---

# ¿Por qué importa proteger los datos?

<div class="grid grid-cols-2 gap-8 pt-4">
<div>

### Nuestra huella digital

- Navegación y búsquedas
- Compras y operaciones financieras
- Ubicación y dispositivos
- Fotografías y biometría
- Actividad en plataformas

</div>
<div>

### El riesgo

Cuando los datos se combinan, pueden construir perfiles detallados y afectar:

- La intimidad y el honor
- El acceso al crédito o al empleo
- La identidad y la dignidad
- La posibilidad de no ser discriminado

</div>
</div>

<div class="mt-8 rounded-lg bg-blue-500/10 p-4 text-lg">
**Idea central:** no alcanza con que los datos se almacenen; importa quién los usa, para qué y bajo qué garantías.
</div>

---

# Marco constitucional y normativo

<div class="grid grid-cols-2 gap-6 pt-4">
<div class="border rounded-xl p-4">

### Constitución Nacional

**Artículo 43, tercer párrafo**

Permite conocer los datos personales registrados y exigir, cuando corresponda, su supresión, rectificación, confidencialidad o actualización.

</div>
<div class="border rounded-xl p-4">

### Ley 25.326

**Protección de los Datos Personales**

Regula el tratamiento de datos, los derechos de sus titulares, las obligaciones de responsables y usuarios, y la acción de hábeas data.

</div>
</div>

- **Decreto 1558/2001:** reglamenta la ley.
- **AAIP:** autoridad de control del régimen nacional.
- **Artículo 43:** también protege el secreto de las fuentes de información periodística.

<small class="opacity-60">La reforma constitucional de 1994 dio reconocimiento constitucional expreso a esta garantía.</small>

---

# Protección de datos y autodeterminación informativa

<div class="text-xl leading-relaxed pt-3">

La protección de datos reúne principios, derechos y obligaciones para que la información personal se recolecte y utilice de forma **legítima, adecuada, segura y compatible con su finalidad**.

</div>

<div class="grid grid-cols-3 gap-4 pt-6">
<div class="rounded-xl bg-blue-500/10 p-4">

### Conocer

Saber qué información existe y quién la posee.

</div>
<div class="rounded-xl bg-green-500/10 p-4">

### Controlar

Poder corregir, actualizar o suprimir datos cuando corresponda.

</div>
<div class="rounded-xl bg-orange-500/10 p-4">

### Limitar

Evitar usos incompatibles, inseguros o discriminatorios.

</div>
</div>

<small class="opacity-70">La autodeterminación informativa se vincula con la facultad de decidir cuándo y dentro de qué límites se revela información propia.</small>

---

# ¿Qué se considera dato personal?

## Ley 25.326, artículo 2

> Información de cualquier tipo referida a personas físicas o de existencia ideal determinadas o determinables.

<div class="grid grid-cols-2 gap-6 pt-4">
<div>

### Identificación directa

- Nombre y apellido
- DNI o CUIL
- Domicilio y correo
- Razón social o CUIT

</div>
<div>

### Identificación indirecta

- Dirección IP
- Número de legajo
- Identificador del dispositivo
- Patrón de geolocalización

</div>
</div>

<div class="mt-5 border-l-4 border-blue-500 pl-4">

Un dato puede ser personal aunque no identifique por sí solo: basta con que pueda vincularse razonablemente con una persona.

</div>

---

# Datos sensibles: mayor riesgo, mayor cuidado

La Ley 25.326 incluye datos que revelan:

- Origen racial o étnico
- Opiniones políticas
- Convicciones religiosas, filosóficas o morales
- Afiliación sindical
- Salud o vida sexual

<div class="grid grid-cols-2 gap-6 pt-4">
<div class="rounded-xl bg-red-500/10 p-4">

### Riesgos

- Discriminación
- Estigmatización
- Exclusión
- Represalias

</div>
<div class="rounded-xl bg-green-500/10 p-4">

### Regla de protección

Nadie puede ser obligado a proporcionar datos sensibles. Su tratamiento está sujeto a restricciones y excepciones legales específicas.

</div>
</div>

<small class="opacity-70">El material también destaca reglas especiales para datos de salud y antecedentes penales.</small>

---

# El ciclo de vida del dato

```mermaid
flowchart LR
    A[Recolección] --> B[Registro y almacenamiento]
    B --> C[Uso y evaluación]
    C --> D[Comunicación o transferencia]
    D --> E[Actualización o conservación]
    E --> F[Supresión o destrucción]
```

Cada etapa puede constituir **tratamiento de datos personales**.

### Ejemplo: solicitud de un préstamo

1. Se completan datos en un formulario.
2. La entidad los almacena y evalúa el riesgo crediticio.
3. Puede comunicar información a terceros cuando exista una base legal.
4. Debe actualizarla y conservarla solo durante el plazo que corresponda.

---

# Principios que orientan el tratamiento

<div class="grid grid-cols-2 gap-5 pt-3">
<div class="border rounded-xl p-4">

**Licitud y finalidad**

Tratar datos conforme a la ley y para fines compatibles con los informados.

**Calidad**

Datos ciertos, adecuados, pertinentes, exactos y actualizados.

**Información y transparencia**

Explicar qué se recoge, para qué, quién responde y qué derechos existen.

</div>
<div class="border rounded-xl p-4">

**Seguridad y confidencialidad**

Prevenir accesos no autorizados, alteraciones y filtraciones.

**Consentimiento**

Como regla general, libre, expreso e informado; existen excepciones legales.

**Cesión y transferencias**

Sujetos a condiciones, responsabilidades y límites legales.

</div>
</div>

<div class="mt-5 text-lg">
**Consentir no significa autorizar cualquier uso posterior.**
</div>

---

# ¿Quiénes intervienen?

```mermaid
flowchart TD
    T[Titular de los datos] -->|Ejerce derechos| R[Responsable de la base]
    R -->|Puede contratar| E[Encargado del tratamiento]
    R -->|Debe cumplir la ley| N[Principios y obligaciones]
    A[AAIP] -->|Control y fiscalización| R
    T -->|Reclamo o acción judicial| J[Justicia: hábeas data]
```

- **Responsable:** decide la finalidad y los medios del tratamiento.
- **Usuario:** realiza operaciones de tratamiento sobre los datos.
- **Encargado:** procesa datos por cuenta del responsable y no debe utilizarlos para fines ajenos al servicio.
- **AAIP:** ejerce funciones de control del régimen nacional.

Delegar el procesamiento en un tercero no elimina las obligaciones del responsable frente al titular.

---

# Derechos del titular: plazos clave

| Derecho | ¿Qué permite? | Plazo señalado en el material |
|---|---|---|
| Información | Conocer bases, responsables y finalidades | — |
| Acceso | Saber qué datos se registran sobre uno | **10 días** |
| Rectificación, actualización o supresión | Corregir, poner al día o eliminar cuando corresponda | **5 días hábiles** |

<div class="grid grid-cols-2 gap-5 pt-5">
<div class="rounded-xl bg-blue-500/10 p-4">

### Sin cargo

El ejercicio de rectificación, actualización y supresión debe realizarse gratuitamente.

</div>
<div class="rounded-xl bg-orange-500/10 p-4">

### Si no hay respuesta adecuada

Puede acudirse a la autoridad de control y, cuando corresponda, a la vía judicial.

</div>
</div>

<small class="opacity-60">Plazos expuestos según el material proporcionado; la aplicación concreta depende del supuesto legal.</small>

---

# Hábeas data: conocer y controlar

El hábeas data es una **garantía constitucional** que permite conocer la información personal registrada y, cuando corresponda, exigir su corrección o protección.

<div class="grid grid-cols-2 gap-6 pt-4">
<div class="rounded-xl border p-5">

### Dimensión informativa

- Qué datos existen
- Dónde están registrados
- Para qué se utilizan
- Quién los produjo o proporcionó, cuando sea jurídicamente posible

</div>
<div class="rounded-xl border p-5">

### Dimensión de control

- Rectificar datos incorrectos
- Actualizar datos desactualizados
- Suprimir datos cuando corresponda
- Preservar la confidencialidad

</div>
</div>

---

# Modalidades doctrinarias del hábeas data

<div class="grid grid-cols-2 gap-4 pt-3">
<div class="border rounded-xl p-4">

**Informativo**

Conocer qué información posee una base y su finalidad.

**Rectificador**

Corregir información incorrecta.

**Actualizador**

Incorporar información nueva o poner al día la existente.

</div>
<div class="border rounded-xl p-4">

**Supresor**

Eliminar información cuando su conservación o tratamiento sea ilegítimo.

**Confidencial**

Evitar la divulgación ilegítima de información.

</div>
</div>

<small class="opacity-70">La clasificación es doctrinaria: las categorías no aparecen necesariamente con esta denominación exacta en la Ley 25.326. Pueden combinarse.</small>

---

# Procedimiento y límites

<div class="grid grid-cols-2 gap-6 pt-3">
<div>

### Camino general

1. Identificar la base de datos y, si es posible, a su responsable.
2. Ejercer primero los derechos ante el responsable.
3. Si no hay respuesta adecuada, evaluar la vía ante la AAIP y/o judicial.
4. El juez puede ordenar rectificación, actualización, supresión o confidencialidad.

</div>
<div>

### Límites y garantías

- Puede haber excepciones fundadas por defensa, seguridad, orden público o derechos de terceros.
- El juez puede requerir información y documentación relevante.
- En determinadas circunstancias puede ordenarse el bloqueo provisional.
- Debe armonizarse la protección de datos con otros derechos e intereses legítimos.

</div>
</div>

<div class="mt-5 rounded-lg bg-blue-500/10 p-4">
El hábeas data no reemplaza los derechos del titular: ofrece una garantía para hacerlos efectivos cuando no se respetan.
</div>

---

# La jurisprudencia delimita el alcance

<div class="space-y-3 pt-3">
<div class="flex gap-4">
<div class="w-28 shrink-0 text-blue-500 font-bold">Urteaga (1998)</div>
<div>Acceso a información en organismos estatales, sin exigir demostrar previamente que sea falsa o discriminatoria.</div>
</div>
<div class="flex gap-4">
<div class="w-28 shrink-0 text-blue-500 font-bold">Martínez (2005)</div>
<div>Protección frente a información comercial o crediticia inexacta o desactualizada.</div>
</div>
<div class="flex gap-4">
<div class="w-28 shrink-0 text-blue-500 font-bold">Denegri (2022)</div>
<div>Conflicto entre hábeas data supresor, derecho al olvido y libertad de expresión; esta última prevaleció.</div>
</div>
<div class="flex gap-4">
<div class="w-28 shrink-0 text-blue-500 font-bold">Torres Abad (2026)</div>
<div>Según el material, debate sobre uso estatal de datos sin consentimiento e inconstitucionalidad de dos excepciones legales.</div>
</div>
</div>

<small class="opacity-60">Resumen de los precedentes tal como se presentan en el material fuente; no constituye una verificación jurisprudencial independiente.</small>

---

# Nuevos desafíos tecnológicos

<div class="grid grid-cols-2 gap-5 pt-3">
<div class="rounded-xl bg-red-500/10 p-4">

### Riesgos para las personas

- Filtraciones y brechas de seguridad
- Datos desactualizados
- Recolección excesiva
- Perfiles automatizados
- Reconocimiento facial

</div>
<div class="rounded-xl bg-blue-500/10 p-4">

### Preguntas jurídicas

- ¿Qué datos se usan para entrenar una IA?
- ¿Con qué fundamento se procesan?
- ¿Quién recibe o transfiere la información?
- ¿Qué garantías existen en otros países?
- ¿Cómo se corrige una decisión automatizada?

</div>
</div>

<div class="mt-5 text-lg">
La tecnología cambia; los principios de finalidad, calidad, seguridad, consentimiento e información siguen siendo centrales.
</div>

---

# Para debatir

<div class="text-2xl leading-relaxed pt-5">

**¿Cómo equilibrar la innovación tecnológica, el interés público y el derecho de cada persona a controlar su información?**

</div>

<div class="pt-8 opacity-70">
Preguntas · Comentarios · Casos prácticos
</div>
