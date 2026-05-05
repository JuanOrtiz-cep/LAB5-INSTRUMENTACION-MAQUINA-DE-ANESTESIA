# LAB5-INSTRUMENTACION-MAQUINA-DE-ANESTESIA

Práctica de Laboratorio: Máquina de Anestesia WATO EX-20
Descripción

Esta práctica se desarrolló con base en el manual de operación y servicio de la máquina de anestesia WATO EX-20 (Mindray). El objetivo fue comprender su funcionamiento, identificar sus subsistemas, analizar fallas comunes y documentar el proceso mediante una herramienta colaborativa.

PARTE A – Fundamento Teórico
a. Tipos de anestesia

Los tipos de anestesia comúnmente utilizados son:

Anestesia general: Produce pérdida total de la conciencia. En el contexto de la WATO EX-20, se administra mediante agentes inhalatorios controlados por el sistema de respiración.
Anestesia regional: Bloquea la sensibilidad en una región específica del cuerpo. Puede requerir soporte ventilatorio proporcionado por la máquina.
Anestesia local: Actúa en una zona específica sin afectar la conciencia. Su relación con la máquina es limitada.

En la práctica con la WATO EX-20, el enfoque principal es la anestesia general inhalatoria.

b. Gases utilizados

La máquina WATO EX-20 trabaja con los siguientes gases:

Oxígeno (O₂): indispensable para la respiración del paciente.
Óxido nitroso (N₂O): proporciona efecto analgésico y anestésico.
Aire medicinal: permite ajustar la mezcla de gases de forma segura.

Los gases de oxígeno y óxido nitroso pueden suministrarse mediante cilindros de alta presión, los cuales están conectados a manómetros que permiten monitorear su estado.

c. Sistema de respiración

El sistema de respiración está compuesto por válvulas inspiratorias y espiratorias, sensores, circuito respiratorio, absorbedor de CO₂ y el fuelle del ventilador.

Sus funciones principales son:

Suministrar la mezcla de gases anestésicos al paciente.
Eliminar el dióxido de carbono del aire exhalado.
Permitir ventilación controlada o asistida.

Los componentes que pueden esterilizarse en autoclave incluyen el circuito respiratorio, la bolsa manual y algunos tubos, según indicaciones del fabricante.

d. Modos del ventilador

De acuerdo con el manual de la WATO EX-20, los modos principales son:

VCV (Ventilación controlada por volumen)
PCV (Ventilación controlada por presión)
Modo manual

El equipo no maneja submenús como tal, sino modos configurables desde el panel de control.

La función de pausa inspiratoria no se presenta como una opción independiente explícita, sino que depende de la configuración del ventilador en los modos mecánicos.

PARTE B – Identificación de Componentes
1. Componentes principales
a. Vaporizador

Permite la vaporización controlada de agentes anestésicos como sevoflurano, isoflurano y desflurano. El sistema incluye un mecanismo de interbloqueo que impide la activación simultánea de más de un vaporizador.

b. Válvula APL

La válvula de límite de presión ajustable regula la presión del sistema respiratorio durante la ventilación manual, liberando el exceso de gas cuando se supera el valor establecido.

c. Recipiente absorbente de CO₂

Contiene cal sodada, la cual elimina el dióxido de carbono del aire exhalado, permitiendo la recirculación de gases dentro del sistema.

d. Fuelle

Es el componente mecánico del ventilador que se expande y contrae para generar el flujo de aire necesario para la ventilación del paciente.

2. Mensaje “batería en uso”

Cuando el equipo muestra este mensaje, indica que está funcionando con su batería interna.

La acción recomendada es verificar la conexión a la red eléctrica, garantizar la continuidad del soporte ventilatorio sin desconectar al paciente y preparar una fuente de respaldo.

3. Reemplazo del absorbente de CO₂

El reemplazo del absorbente debe realizarse cuando se detecte un aumento en los niveles de CO₂ inspirado o espirado, o cuando el material indique saturación. El manual no establece un tiempo fijo, ya que depende del uso clínico.

4. Verificación de fugas en el cilindro de alta presión

El procedimiento consiste en:

Abrir la válvula del cilindro.
Observar la presión en el manómetro.
Cerrar la válvula.
Verificar si existe una caída de presión, lo cual indicaría una fuga.
5. Sensor de oxígeno

El sensor de O₂ permite medir la concentración real de oxígeno en la mezcla suministrada al paciente.

Su presencia mejora la seguridad del sistema, ya que permite detectar errores en la mezcla de gases. Sin el sensor, el equipo solo controla el flujo, pero no verifica la concentración real.

6. Sistema de presión negativa

El sistema de evacuación de gases anestésicos evita la acumulación de gases en el entorno clínico, protegiendo al personal médico de la exposición a agentes anestésicos.

PARTE C – Procedimiento
Pasos realizados
Revisión del manual de operación de la WATO EX-20.
Identificación de los componentes principales del equipo.
Encendido y configuración inicial.
Ajuste de los gases y selección del agente anestésico.
Configuración del modo ventilatorio.
Realización de pruebas funcionales:
Prueba de fugas
Prueba de flujo
Verificación del sistema de oxígeno
Observación de alarmas y monitoreo de parámetros.
Documentación del proceso en GitHub.
Resultados

Al finalizar la práctica se logró:

Identificar los módulos principales de la máquina de anestesia.
Comprender los modos de ventilación disponibles.
Ejecutar pruebas de funcionamiento basadas en el manual.
Reconocer alarmas y su significado.
Documentar adecuadamente el proceso mediante una plataforma colaborativa.
Análisis de Resultados
Análisis 1: Fallas comunes

Las fallas más frecuentes incluyen:

Fugas en el sistema de gases.
Fallas en el vaporizador.
Problemas en el sensor de oxígeno.
Saturación del absorbente de CO₂.
Fallas eléctricas.
Análisis 2: Subsistemas con mayor número de fallas

Ordenados de mayor a menor:

Sistema de gases
Sistema respiratorio
Vaporizador
Sistema electrónico
Conclusiones

Las fallas más comunes en la máquina de anestesia están relacionadas con el sistema de gases y la presencia de fugas, lo cual puede comprometer la seguridad del paciente.

El sensor de oxígeno es un componente crítico para garantizar una adecuada administración de la mezcla gaseosa. Asimismo, el mantenimiento preventivo y la correcta ejecución de pruebas antes de su uso son fundamentales para evitar eventos adversos.

Preguntas para la Discusión
1. Tipos de anestésicos más usados

Los anestésicos más utilizados en cirugía incluyen sevoflurano, isoflurano y desflurano, debido a su control y rápida acción.

2. Diferencias entre WATO EX-20 y EX-35

El modelo EX-35 presenta mejoras en:

Mayor número de modos ventilatorios.
Interfaz más avanzada.
Mejor monitoreo y automatización.
Bibliografía (Formato IEEE)

[1] Mindray, WATO EX-20/30 Operation Manual, 2009.
[2] Mindray, WATO EX-20/30/35 Service Manual, 2013.
[3] M. P. Dosch, The Anesthesia Machine, Elsevier, 2005.
[4] M. A. Sherwin and J. B. Eisenkraft, “Anesthesia hazards: What is the role of the anesthesia machine?”, International Anesthesiology Clinics, vol. 58, no. 1, pp. 27–31, 2020.
