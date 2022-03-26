---
title: "Implementing Ask Behavior and OpenPose in the Golem Service Robot"
date: 2020-04-18T12:00:00+06:00
image: "images/portfolio/P6/Golem2.png"
tags: ["Artificial Intelligence","Logic Programming"]
description: "This is meta description."
draft: false
#project_info:
#- name: "Research Stay"
#  icon: "fas fa-user"
#  content: "The Golem Group"
#- name: "Project Link"
#  icon: "fas fa-link"
#  content: "http://golem.iimas.unam.mx/home.php?lang=en&sec=home"
#- name: "Collaborators"
#  icon: "fas fa-users"
#  content: "[Members of the Golem Group](http://golem.iimas.unam.mx/member.php?lang=en&sec=member)"
#- name: "Loop Item"
#  icon: "fas fa-redo"
#  content: "This is in a loop"
---
<div style="text-align: justify">

The Golem-III project is a service robot presented internationally at RoboCup 2016 Leipzig, Germany, where the 6th place was obtained in the category \@Home. It has also participated at RoboCup Nagoya 2017 and the RoboCup German Open 2018 and 2019, where the 3rd and 5th places were obtained respectively.

The Golem Group develops service robots based on Artificial Intelligence and Human-Robot Interaction to assist people in daily life activities. Our group comprises theoretical research, hardware and software development, and the construction of physical robots. In this project, the robots Golem (2002-2008), Golem en Universum (2019-2010), Golem-II+ (2010-2014) and Golem-III (2014 to the date) have been developed. Our robots are regularly presented at Museo de Ciencias Universum and Biblioteca Central of UNAM. The Golem group participates consistently at Torneo Mexicano de Robótica (TMR) and the international RoboCup competition in the category \@Home. Our group has several ongoing projects.

The Golem Group is part of the [Departamento de Ciencias de la Computación](http://turing.iimas.unam.mx/) at [Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas](http://www.iimas.unam.mx/) (IIMAS) including colaborators and students from Centro de Investigaciones en Diseño Industrial (CIDI) at Facultad de Arquitectura, Facultad de Ingeniería and FES Aragón and FES Cuautitlán of the [Universidad Nacional Autónoma de México](http://unam.mx/) (UNAM).

#### Project Details

My participation in this project is mainly divided in three parts. The first one consisted of reviewing the requirements to implement the OpenPose software for the detection of people, as well as for the integration of this system with the other components of the project. This both at the hardware level to use the sensors that has the Kinect that has incorporated the robot and to capture the information with the highest quality and coverage possible. At the software level, it was necessary to review the appropriate conditions for the correct operation of OpenPose with the operating system, development tools and programming languages with which the robot operates. After this review the human detection system was successfully implemented, giving the robot a greater ability to perform tasks involving recognition and interaction with people.  

The second part of my participation in the project consisted of reviewing and coordinating tests for two tasks performed by the robot in the RoboCup@home competition. These are the General Porpuse Service Robot (GPSR) and Extended Enhanced General Porpuse Service Robot (EEGPSR). In these tests, the robot performs general human assistance tasks, such as answering questions or performing relatively simple physical tasks to support the user, such as bringing or carrying things, arranging objects, etc. During these tests, the performance of the robot is measured in several aspects, such as the understanding, processing and response to the user's indications. The accuracy, efficiency and time taken to complete individual tasks and the test as a whole were also important factors in the testing. In the case of simple corrections, they were applied to the robot, but for major changes, the corresponding sub-team was instructed depending on the work to be done for the correction.

The third part of my involvement in the project was the implementation of a general behavior in the robot. This process was a sub-routine that was used in more complex scenarios and routines for the robot to perform its tasks. This is how the 'ASK' behavior was improved. The main objective of this enhancement was to increase Golem-III's ability to have an efficient Human-Robot interaction. Before the enhancement, Golem-III did not have many alternatives for an efficient interaction with the user in several scenarios, especially in cases where the user was not proactive in such interaction. To give a solution to this problem we studied the way of human interaction and some strategies to make the human being proactive and communicative enough when interacting with the robot. The proposed solution included three main aspects of communication: regular mode, cooperative mode and contextualized mode. The three levels are used in different situations depending on the user's attitude towards the robot. Where the highest level of proactivity involves movements and displacements to attract the user's attention.

<!--- Mi participación en este proyecto se divide principalmente en tres partes. La primera consistió en revisar los requerimientos para implementar el software de OpenPose para la detección de personas, así como para la integración de dicho sistema con los demas componentes del proyecto. Esto tanto a nivel de hardware para utilizar los sensores que tiene el Kinect que tiene incorporado el robot y poder capturar la información con la mayor calidad y cobertura posible. A nivel de software se debia de revisar que se tuviesen las condiciones adecuadas para el funcionamiento correcto de OpenPose con el sistema operativo, las herramientas de desarrollo y los lenguajes de programación con las que opera el robot. Después de esta revisión el sistema de detección de personas fue implementado con exito, brindando al robot una mayor capacidad de llevar acabo taréas que involucran el reconocimeinto y la interacción con personas.  

La segunda parte de mi participación en el proyecto consistió en la revisión y coordinación de pruebas para dos tareaa que realiza el robot en la competencia Robo \@home. Estas son las de General Porpuse Service Robot (GPSR) y Extended Enhanced General Porpuse Service Robot (EEGPSR). En estas pruebas el robot realiza tareas generales de sistencia a los humanos, tal como resolver dudas o realizar tareas físicas relativamente sencillas de apoyo al usuario, como traer o llevar cosas, acomodar objetos, etc. Durante estas pruebas se media el desempeño del robot en varios aspectos, como el entendimiento  procesamiento y respuesta emitida ante las indicaciones del usuario. La precision, eficiencia y tiempo en que se completaban las tares individuales y la prueba en su totalidad también eran factores de importancia a la hora de realizar las pruebas. En caso de correcciones sencillas se aplicaban que se tuviesen que hacer al robot, pero para cambios mayores se indicaba al sub-equipo correspondiente dependiendo del trabajo que se tenia que realizar para la corrección.

La tercera parte de mi participación en el proyecto fue la implementación de un comportamiento general en el robot. Este proceso era una sub-rutina que era utilizada en escenarios y rutinas mas complejas para que el robot llevara acabo sus tareas. Así fue como se realizo una mejora a la conducta 'ASK'. El objetivo de esta mejora tenia por objetivo principal el incrementar la capacidad de Golem-III de tener una interacción Humano-Robot eficiente. Antes de ka mejora Golem-III no contaba con muchas alternativas para una eficiente interacción con el usuario en diversos escenarios, especialmente en casos donde el usuario no era proactivo en dicha interacción. Para dar una solución a esta problmatica de estudio la forma de interacción humana y algunas estrategias para buscar que el humano fuera lo suficientemente proactivo y comunicativo a la hora de interactuar con el robot. La solución propuesta incluia tres principales vertientes de comunicación: modo regular, modo cooperatico y modo contextualizado. Los tres niveles se utilizan en diferentes situaciones dependiendo de la actitud del usuario ante el robot. Donde el nivel mas alto de proactividad involucra movimientos y desplazamientos para llamar la atención del usuario. -->

#### Project Requirements & Specifications

This work is a research project, more details of the project can be found on the p[roject website](http://golem.iimas.unam.mx/home.php?lang=en&sec=home) and in [this article](https://scholar.google.nl/scholar?oi=bibs&cluster=16368582091687832750&btnI=1&hl=fr). Details on ask behavior can be found in this article presented at CEIAAIT 2019. </div>
