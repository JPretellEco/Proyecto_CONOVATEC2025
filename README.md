## 📄 Diccionario de Datos

A continuación se describe la estructura del conjunto de datos reportado por la Oficina de Epidemiología de la DIRESA, con el detalle de cada variable incluida.

| Variable        | Descripción                                                                             | Tipo de dato | Tamaño | Recurso relacionado         | Información adicional |
| --------------- | --------------------------------------------------------------------------------------- | ------------ | ------ | --------------------------- | --------------------- |
| `FECHA_CORTE`   | Fecha de corte de información enviada por la Oficina de Epidemiología.                  | Numérico     | 8      |                             | Formato: `aaaammdd`   |
| `FECHA_MUESTRA` | Fecha en la que se recogió la información.                                              | Numérico     | 8      |                             | Formato: `aaaammdd`   |
| `DEPARTAMENTO`  | Departamento donde se ubica el Establecimiento de Salud.                                | Texto        | 50     | Catálogo de UBIGEO del INEI |                       |
| `PROVINCIA`     | Provincia donde se ubica el Establecimiento de Salud.                                   | Texto        | 50     | Catálogo de UBIGEO del INEI |                       |
| `DISTRITO`      | Distrito donde se ubica el Establecimiento de Salud.                                    | Texto        | 50     | Catálogo de UBIGEO del INEI |                       |
| `UBIGEO`        | Código geográfico de ubicación en formato `DDPPDD` (departamento, provincia, distrito). | Alfanumérico | 6      | Fuente: INEI                |                       |
| `ANO`           | Año en que se produjo el caso.                                                          | Numérico     | 4      |                             |                       |
| `SEMANA`        | Semana epidemiológica en la que se iniciaron los síntomas.                              | Numérico     | 1      |                             |                       |
| `E_SALUD`       | Código del Establecimiento de Salud que notifica y realiza la atención.                 | Alfanumérico | 10     |                             |                       |
| `SUB_REG_NT`    | Código de la subregión de salud donde se realiza la atención.                           | Numérico     | 2      |                             |                       |
| `DAA_C1`        | Casos de diarreas acuosas agudas en pacientes menores de 1 año.                         | Numérico     |        |                             |                       |
| `DAA_C1_4`      | Casos de diarreas acuosas agudas en pacientes de 1 a 4 años.                            | Numérico     |        |                             |                       |
| `DAA_C5`        | Casos de diarreas acuosas agudas en pacientes menores de 5 años.                        | Numérico     |        |                             |                       |
| `FECHA_ING`     | Fecha de ingreso del registro en el sistema.                                            | Numérico     | 8      |                             | Formato: `aaaammdd`   |

---
