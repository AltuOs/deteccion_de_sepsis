# Home
# Notebook, Video y producto
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AltuOs/deteccion_de_sepsis/blob/main/MODESAFE.ipynb)
# Desafío
**Reto:** Potenciar la detección temprana de sepsis mediante el análisis de series temporales fisiológicas.

El valor de los datos en la investigación en IA y el cuidado de la salud es la posibilidad de aportar nuevas respuestas para el tratamiento, la prevención y la comprensión de la enfermedad y la calidad de vida.

**Retador:** Dr. John Anderson Garcia Henao, Postdoctoral Researcher at ARTORG Center. University of Bern

# Sepsis
La sepsis es una respuesta inflamatoria sistémica grave del cuerpo a una infección. Esta respuesta anormal se desencadena cuando el sistema inmunológico responde de manera exagerada y libera una cascada de mediadores inflamatorios en la sangre. En lugar de controlar y limitar la infección, el cuerpo comienza a dañar sus propios tejidos y órganos. La sepsis puede tener un impacto potencialmente mortal en el cuerpo y requiere atención médica urgente.

## Causas
Las causas de la sepsis son diversas e incluyen infecciones bacterianas, virales, fúngicas o parasitarias. La fuente de la infección puede estar en cualquier parte del cuerpo, desde los pulmones hasta el tracto urinario o incluso una herida en la piel. La sepsis a menudo se desarrolla cuando una infección no se controla o se trata adecuadamente, permitiendo que las bacterias u otros patógenos se propaguen en la sangre.

## Síntomas
La sepsis presenta una variedad de síntomas que pueden variar en gravedad. Estos pueden incluir fiebre alta o hipotermia (temperatura corporal baja), taquicardia (ritmo cardíaco acelerado), taquipnea (respiración rápida), confusión o cambios en el estado mental, hipotensión (presión arterial baja), coloración de la piel anormal (pálida, moteada o cianótica) y signos de disfunción orgánica, como dificultad para respirar o insuficiencia renal.

## Detección y diagnóstico
El diagnóstico de la sepsis implica una evaluación clínica minuciosa por parte del personal médico, análisis de laboratorio y, en algunos casos, estudios de imagen. Los análisis de sangre, como el recuento de glóbulos blancos y los niveles de lactato en sangre, son indicadores comunes de sepsis. También se utilizan sistemas de puntuación, como el SOFA (Sequential Organ Failure Assessment), para evaluar la gravedad de la disfunción orgánica.

## Importancia de la detección temprana
La sepsis puede progresar rápidamente, lo que la convierte en una emergencia médica. La detección temprana es crítica para iniciar el tratamiento adecuado antes de que la condición se deteriore significativamente. Un diagnóstico y tratamiento oportunos aumentan significativamente las posibilidades de supervivencia.

## Tratamiento
El tratamiento de la sepsis implica abordar la infección subyacente con antibióticos específicos y proporcionar apoyo hemodinámico para estabilizar la presión arterial. Además, puede requerir terapia de soporte de órganos, como la administración de líquidos intravenosos o la ventilación mecánica. El tratamiento se adapta a las necesidades específicas de cada paciente.

## Complicaciones
La sepsis puede dañar gravemente los órganos y tejidos, lo que puede resultar en complicaciones a largo plazo. Los órganos más comúnmente afectados incluyen los riñones, el hígado, el corazón y los pulmones. Las complicaciones pueden llevar a insuficiencias crónicas y discapacidades cognitivas en pacientes sobrevivientes.

## Pronóstico
El pronóstico de la sepsis varía según la gravedad de la afección y la prontitud del tratamiento. En casos graves, la sepsis puede ser mortal, pero con tratamiento adecuado y oportuno, muchas personas se recuperan por completo. La recuperación puede llevar tiempo y rehabilitación.

## Prevención
La prevención de la sepsis implica medidas como mantener una buena higiene, administrar vacunas adecuadas, tratar infecciones a tiempo y cuidar heridas correctamente. La educación y la concienciación pública son clave para la prevención.

## Investigación y avances
La investigación en el campo de la sepsis es un componente esencial para mejorar la comprensión y el tratamiento de esta condición. Se están llevando a cabo investigaciones continuas para abordar varios aspectos de la sepsis:

- **Mecanismos subyacentes:** Los científicos están investigando en profundidad los mecanismos biológicos que desencadenan la respuesta inflamatoria sistémica en la sepsis. Comprender mejor estos procesos puede conducir al desarrollo de terapias dirigidas específicamente a estos mecanismos.

- **Identificación de biomarcadores:** Se buscan biomarcadores en la sangre u otros fluidos corporales que puedan indicar la presencia de sepsis de manera temprana y precisa. Estos biomarcadores podrían revolucionar la detección y el diagnóstico de la sepsis.

- **Desarrollo de terapias específicas:** La investigación se centra en el desarrollo de tratamientos más efectivos y específicos para combatir la sepsis. Esto incluye la exploración de nuevos antibióticos, terapias inmunomoduladoras y enfoques para proteger los órganos durante la sepsis.

- **Mejora de los protocolos de tratamiento:** Los estudios clínicos y la investigación en atención crítica buscan optimizar los protocolos de tratamiento para la sepsis. Esto implica determinar las mejores estrategias de administración de medicamentos, apoyo hemodinámico y otros aspectos del cuidado del paciente.

- **Prevención de la sepsis:** Se investiga cómo prevenir la sepsis en situaciones de alto riesgo, como en pacientes hospitalizados o en unidades de cuidados intensivos. Esto incluye la identificación de factores de riesgo y la mejora de las prácticas de higiene y control de infecciones.

- **Avances en tecnología médica:** La tecnología desempeña un papel importante en la detección y el tratamiento de la sepsis. Los investigadores están explorando el uso de algoritmos de inteligencia artificial y sistemas de monitorización avanzados para identificar la sepsis en sus primeras etapas.

## Impacto en la salud pública
La sepsis tiene un impacto significativo en la salud pública. Afecta a un gran número de personas en todo el mundo y representa una carga económica considerable en términos de atención médica y recursos.

## Concienciación y educación
La concienciación pública sobre la sepsis es fundamental para promover la detección temprana y la prevención. La educación sobre los síntomas, factores de riesgo y cómo actuar en caso de sospecha de sepsis es esencial para salvar vidas.

# Métodos de detección de la sepsis
La detección de la sepsis se basa en una combinación de evaluación clínica, análisis de laboratorio y, en algunos casos, estudios de imagen. Los términos SIRS, qSOFA y SOFA son sistemas de puntuación utilizados en el ámbito médico para evaluar la gravedad de la respuesta inflamatoria sistémica y la disfunción orgánica. Cada uno se utiliza en un contexto específico:

## SIRS (Síndrome de Respuesta Inflamatoria Sistémica):
El SIRS es un conjunto de criterios clínicos que se utiliza para identificar la respuesta inflamatoria sistémica en un paciente. Los criterios del SIRS incluyen:
- Fiebre o hipotermia (temperatura corporal alta o baja).
- Taquicardia (frecuencia cardíaca elevada).
- Taquipnea (frecuencia respiratoria elevada).
- Recuento de glóbulos blancos elevado (leucocitosis) o bajo (leucopenia).

## qSOFA (Quick Sequential Organ Failure Assessment):
El qSOFA es una herramienta simplificada para evaluar la gravedad de la sepsis en pacientes fuera de la unidad de cuidados intensivos (UCI). Incluye tres criterios clínicos simples:
- Frecuencia respiratoria igual o superior a 22 respiraciones por minuto.
- Presión arterial sistólica igual o inferior a 100 mm Hg.
- Estado mental alterado (confusión o disminución del nivel de conciencia, con una puntuación de Glasgow menor o igual a 14).

Un puntaje de qSOFA mayor o igual a 2 puntos indica un mayor riesgo de mal pronóstico en pacientes con sospecha de infección. Es una herramienta de evaluación rápida y fácil de aplicar.

## SOFA (Sequential Organ Failure Assessment):
El SOFA es un sistema de puntuación más completo y detallado utilizado para evaluar la gravedad de la disfunción orgánica en pacientes con sepsis o en la UCI. Evalúa seis sistemas orgánicos diferentes:
- Respiratorio.
- Sistema nervioso central.
- Cardiovascular.
- Hepático.
- Coagulación.
- Renal.

Se asigna un puntaje a cada sistema según la gravedad de la disfunción. Un puntaje total más alto en el SOFA indica una disfunción orgánica más grave. El SOFA se utiliza para evaluar la gravedad y el progreso de la sepsis en pacientes críticos.

### Referencias
- Beltran, C. F. T., Ibañez, E. D. V., Orejuela, V. M., & García Henao, J. A. (2022, September). A Machine Learning-Based Missing Data Imputation with FHIR Interoperability Approach in Sepsis Prediction. In Latin American High Performance Computing Conference (pp. 116-130). Cham: Springer International Publishing.
- Reyna, M. A., Josef, C. S., Jeter, R., Shashikumar, S. P., Westover, M. B., Nemati, S., ... & Sharma, A. (2020). Early prediction of sepsis from clinical data: the PhysioNet/Computing in Cardiology Challenge 2019. Critical care medicine, 48(2), 210-217.
# Código

# Sobre nosotros
- **Oscar Altuve:** Soy egresado de la Licenciatura en Física en la Universidad de Los Andes (ULA), participé de la 2da. cohorte de LA-CoNGA physics y actualmente soy estudiante de la Maestría en Física en la Universidad Simón Bolívar (USB) en Venezuela. Mi área de estudio es física de altas energías experimental y ciencia de datos. Tengo habilidades en programación en C++ y Python, reproducibilidad científica, manejo herramientas de edición multimedia y nociones en diseño web. Participé en el hackathon CoAfina 2022, una experiencia maravillosa que me permitió colaborar con otros estudiantes de América Latina para encontrar soluciones innovadoras a retos científicos y educativos usando datos abiertos. Es un placer formar parte de esta nueva edición y espero seguir compartiendo y aprendiendo con todos ustedes. 
Me pueden conseguir en LinkedIn: https://ve.linkedin.com/in/altuos/ 
- **Richard Brito:** Hola, soy Richard Brito, estudiante de física de la Universidad de los Andes, muy entusiasmado de esta oportunidad, de Caicara del Orinoco, Bolívar, Venezuela, pero radicado en Mérida, amante de los gatos, fanático practicante del deporte, sobre todo Taekwondo y Voleibol. Entusiasta de la ciencia de datos y redes neuronales, energías sustentables, vehículos eléctricos, casas ecoamigables y autosustentables ,IAs y linuxero también. Iniciando un emprendimiento para reciclaje de prendas y plásticos para darles una segunda vida, a través de impresión 3D y bricolaje, de todo un poquito, emocionado por aprender mucho en este hackathon y compartir con todos ustedes, espero no se haya hecho larga mi presentación.
- **Daniel Vielma:** Actualmente estudiante de la carrera ciencias matematicas en la Universidad de los andes, me dedico principalmente en el área de ciencia de datos y machine learning. Es mi primera participacion en el hackathon CoAfina, lo cual me parecio una experiencia muy entretenida y retadora.
 Para mas informacion de contacto pueden revisar mi perfil de LinkedIn: https://www.linkedin.com/in/daniel-vielma-10bb42269/
- **Geison Blanco:** Estudiante de Ingeniería de Sistemas de la Universidad Industrial de Santander. Durante mi etapa de estudiante me ha interesado el campo del Aprendizaje de Máquina. Es por esto que cuento con conocimientos sobre implementación de algoritmos de aprendizaje profundo en python, usando librerias de tensorflow y pytorch. También tengo conocimientos en herramientas de tratamiento de datos científicos como numpy y Pandas, así como también en su análisis en forma de gráficas con librerias como matplotlib. Además de manejar muy bien python como lenguaje de programación, también puedo programar en otros lenguajes como Java, C++, Matlab, y en lenguajes de gestión de base de datos como SQL. 
Perfil de LinkedIn: www.linkedin.com/in/geison-alfredo-blanco-rodriguez-861b17249
- **Grendel Lacruz:** Soy Licenciado en Física egresado de la Universidad de Los Andes (ULA - Venezuela). Tengo conocimientos de Python. Quiero dedicarme a la Fusión Nuclear y desarrollarme como científico. Estoy muy interesado en aprender sobre la ciencia de datos y por eso el hackaton ha sido una gran oportunidad.
