# Proyecto de Curso Mitocode Java Full Stack "MediappFrontend"

En este proyecto se muestran los cambios realizados de acuerdo a la evaluación sugerida, donde se agrega el componente de Signos Vitales, junto con las funcionalidades solicitadas. En este branch se encuentra la parte correspondiente al Backend en Spring Boot.
Evaluacion Tipo A (Signos Vitales)

Pasos a tener presente:

1) Ejecutar las siguientes sentencias en la base de datos, sí no se cuenta con el menú para los signos vitales:

INSERT INTO menu(id_menu, nombre, icono, url) VALUES (11, 'Signos Vitales', 'local_hospital', '/pages/signo');

INSERT INTO menu_rol (id_menu, id_rol) VALUES (11, 1);

INSERT INTO menu_rol (id_menu, id_rol) VALUES (11, 2);
