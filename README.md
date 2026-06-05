## Descripción del proyecto

Este proyecto analiza el impacto de eventos recientes (pandemia de COVID-19 y violencia) en la dinámica poblacional del **Estado de México**, la entidad más poblada del país. Mediante la construcción de **tablas de vida**, el cálculo de **indicadores de fecundidad** y la **exclusión de homicidios** como causa de muerte, se evalúan los cambios en la esperanza de vida, la mortalidad por sexo y la capacidad de reemplazo generacional.

El estudio compara los años **2010, 2019 y 2021** para evidenciar el contraste entre un periodo prepandemia y el impacto agudo de la crisis sanitaria.

## Objetivos

- Construir tablas de vida completas para hombres y mujeres del Estado de México (2010, 2019, 2021)
- Calcular y comparar la esperanza de vida al nacer y por edades
- Estimar la Tasa Global de Fecundidad (TGF), Tasa Bruta de Reproducción (TBR) y Tasa Neta de Reproducción (TNR)
- Evaluar el efecto de la exclusión de los homicidios sobre la probabilidad de muerte y la esperanza de vida
- Comparar el perfil de fecundidad del Edomex con el de México y Brasil (2019)

## Fuentes de datos

| Dato | Fuente |
|------|--------|
| Población por edad y sexo | CONAPO (Consejo Nacional de Población) |
| Defunciones por edad, sexo y causa | INEGI (Instituto Nacional de Estadística y Geografía) |
| Nacimientos por sexo y edad de la madre | INEGI |

## Instrucciones de uso

1. Clonar el repositorio
3. Ejecutar el script con conexión a internet
4. Los resultados se guardaran en la raiz del directorio

## Limitaciones

- Los datos de defunciones 2021 reflejan el exceso de mortalidad por COVID-19, pero podrían tener subregistro en causas específicas
- El ajuste de ax con Coale-Demeny es una aproximación estándar
- La exclusión de homicidios supone que el resto de las causas de muerte permanecen sin cambios

## Autores

- Sofía Ángeles Rojo
- Víctor Hugo Sánchez Gayosso

## Licencia

Este material se comparte con fines académicos y de investigación. Las fuentes originales (CONAPO, INEGI) deben ser citadas en cualquier reproducción de los datos.
