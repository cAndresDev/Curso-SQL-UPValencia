#### [README](README.md)

<div align="center">
  <h1>Relaciones entre tablas</h1>
</div>

- Las tablas se relacionan entre sí mediante claves.
- Las claves son campos que identifican de forma única a cada registro.
- Las claves pueden ser:
  - **Clave primaria:** campo que identifica de forma única a cada registro.
  - **Clave foránea:** campo que enlaza dos tablas.

---

# Claves primarias y foráneas

- **Clave primaria:** campo que identifica de forma única a cada registro.
- **Clave foránea:** campo que enlaza dos tablas.

___

 ### Clave primaria

- La columna clave primaria identifica de forma única a cada registro/fila.
- No puede haber dos registros/filas con la misma clave primaria.

___

| StrudentID | CursoID | Grado |
|------------|---------|-------|
| Graff      | 001     | A     |
| Smith      | 002     | B-    |
| Brown      | 003     | C     |

La columna `StudentID` y `CursoID` componen la clave primaria.

___


### Clave foránea/Extranjera

- Se utiliza para relacionar dos tablas.
- Es un campo de la tabla que contiene los mismos valores que la clave primaria de otra tabla.

___

**Tabla del curso**

| CursoID | CursoNombre | ProfesorID |
|---------|-------------|------------|
| 001     | Matemáticas | 101        |
| 002     | Historia    | 102        |
| 003     | Ciencias    | 103        |

___

**Tabla del profesor**

| ProfesorID | ProfesorNombre |
|------------|----------------|
| 101        | Mr. Smith      |
| 102        | Ms. Brown      |
| 103        | Dr. Graff      |

___

**Tabla de los estudiantes**

| StudentID | CursoID | Grado |
|-----------|---------|-------|
| Graff     | 001     | A     |
| Smith     | 002     | B-    |
| Brown     | 003     | C     |


---

# Tipos de relaciones

- **Uno a uno:** un registro de una tabla se relaciona con un registro de otra tabla.
- **Uno a muchos:** un registro de una tabla se relaciona con varios registros de otra tabla.
- **Muchos a muchos:** varios registros de una tabla se relacionan con varios registros de otra tabla.

___

| Simbolo | tipo de relación |
|---------|-------------------|
| 1:1     | Uno a uno         |
| 1:M     | Uno a muchos      |
| M:M     | Muchos a muchos   |

Los símbolos que se utilizan para representar las relaciones entre tablas pueden variar dependiendo del autor o la fuente.

___

### Uno a uno 

- Un registro de una tabla se relaciona con un registro de otra tabla.

**Ejemplo:** una persona tiene un solo pasaporte y un pasaporte pertenece a una sola persona.

___

### Uno a muchos

- Un registro de una tabla se relaciona con varios registros de otra tabla.

**Ejemplo:** un profesor puede tener varios estudiantes, pero un estudiante solo puede tener un profesor.

___

### Muchos a muchos

- Varios registros de una tabla se relacionan con varios registros de otra tabla.

**Ejemplo:** un estudiante puede inscribirse en varios cursos y un curso puede tener varios estudiantes.

---

# Coclusión

La relación entre tablas es fundamental en el diseño de bases de datos relacionales, ya que permite establecer conexiones entre los datos facilitando la consulta y manipulación de la información.

---

# Recomendación

- Como recomendación, es importante que busques ejemplos de bases de datos relacionales.

- También es importante que entiendas los conceptos de claves primarias y foráneas, fundamentales en el diseño de bases de datos relacionales.

#### [README](README.md)