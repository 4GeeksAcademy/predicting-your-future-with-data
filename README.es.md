<!-- hide -->
# Sistemas de recomendación - Tu Futuro según la Data
<!-- endhide -->

Este proyecto propone construir un modelo de clasificación supervisada que, a partir de datos demográficos y socioeconómicos de una persona adulta (edad, nivel educativo, ocupación, estado civil, país de origen, etc.), prediga si dicha persona ganará más o menos de 50,000 USD al año.

En base a los resultados del modelo, los estudiantes deberán desarrollar un sistema de recomendación interpretativo, capaz de sugerir posibles estrategias o cambios para aumentar la probabilidad de superar ese umbral de ingresos.

### Objetivos

- Explorar los datos del censo.
- Construir perfiles socioeconómicos.
- Explorar la importancia y peso de variables sociales (educación, género, raza, etc.) en predicciones económicas.
- Aplicar técnicas de sistemas de recomendación.
- Visualizar y comunicar hallazgos de forma profesional.


## 🌱 Cómo iniciar este proyecto

Sigue las siguientes instrucciones:

1. Crea un nuevo repositorio basado en el [proyecto de Machine Learning](https://github.com/4GeeksAcademy/machine-learning-python-template) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Abre el repositorio creado recientemente en Codespace usando la [extensión del botón de Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Una vez que el VSCode del Codespace haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.


## 📝 Instrucciones

<!-- ### Predecir el coste del seguro médico de una persona -->

1. Carga del conjunto de datos. Usaremos el dataset [Adult Income Dataset](https://archive.ics.uci.edu/dataset/2/adult), también conocido como **"Census Income"** este información fue recolectada por la Oficina del Censo de EE.UU. y descargada por la academia para guardarla en esta carpeta de proyecto bajo el nombre `adult-census-income.csv` o puedes cargarlo en el código directamente desde el siguente enlace:

    ```text
    https://raw.githubusercontent.com/4GeeksAcademy/predicting-your-future-with-data/main/adult-census-income.csv
    ```

    Este dataset incluye variables como:

    - Edad
    - Nivel educativo
    - Estado civil
    - Ocupación
    - Horas trabajadas por semana
    - Sexo
    - País de origen
    - Ingreso anual (>50K o <=50K)

2. Preprocesamiento de datos. Haz la limpieza de datos nulos o mal codificados, la transformación de variables categóricas, normaliza las variables numéricas.

3. Define el problema de recomendación. Plantea cómo vas a estructurar tu sistema de recomendación:

    - ¿Qué se quiere recomendar?
    - ¿Cuál será el "usuario" en este caso?
    - ¿Qué variables definen el perfil de un usuario?

4. Construye el sistema de recomendación. Usa uno de los siguientes enfoques:

    - **Filtrado basado en contenido.** Representa a cada usuario como un vector y calcula similitudes entre usuarios y recomendaciones.

    - **Filtrado colaborativo.** Simula una matriz de usuarios vs. trayectorias. Aplica k-NN, correlación de Pearson o matrix factorization.

    - **Sistema híbrido.** Combina ambos enfoques.

5. Pruebas con casos simulados. Construye perfiles simulados de usuarios hipotéticos y fijate qué trayectorias (educación, ocupación, etc.) les recomendaría el sistema para mejorar su ingreso estimado.

    ```python
    # Ejemplo: Usuario de 25 años, secundario completo, trabaja medio tiempo
    perfil_usuario = {...}
    ```

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver el caso práctico, asegúrate de confirmar tus cambios, haz push a tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.