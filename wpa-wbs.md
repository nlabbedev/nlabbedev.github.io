# Gestión del proyecto | WeProject #

## Requerimiento

Según la reunión del [Lunes, 11 de mayo de 2020](https://nlabbe.atlassian.net/l/c/Nm1mx0bK) se necesita un portal inmobiliario web orientado a ofrecer al usuario recursos y servicios relacionados con el sector inmobiliario, destacando el acceso a la información del mercado a partir de listados de propiedades en venta o alquiler. 

Debe funcionar como punto de encuentro entre la demanda y la oferta inmobiliaria.

Debe financiarse a partir de planes subscritos por el cliente (inmobiliarias, corredoras o particulares).

## Análisis

Considerando los siguientes tres tipos de portales inmobiliarios:

* Portales Inmobiliarios Horizontales.- 1​ Son aquellos en los que los listados o anuncios abarcan todo el mercado inmobiliario y mediante una herramienta denominada buscador permiten orientar la búsqueda a los diferentes tipos de inmuebles.

* Portales Inmobiliarios Verticales.- 2​ Son portales especializados en un tipo de inmueble específico, a diferencia de los "generalistas" portales horizontales, los portales verticales son portales de "nicho"

* Agregadores.- Son portales que carecen de anuncios propios, como su nombre indica agregan anuncios de otros portales y dirigen al usuario a esos portales.
Servicios adicionales de lo

Se define que se requiere un portal de tipo vertical.

## Solución
* Plataforma inmobiliaria web usando arquitectura de microservicios

![alt text](https://www.codeproject.com/KB/aspnet/1276639/image001.png "Arquitectura de microservicios")
--

### Metodología
Se define la metedología ágil scrum para el desarrollo del proyecto.
![alt text](https://d3timt52sxdbq0.cloudfront.net/wp-content/uploads/2017/07/Scrum-framework_en.jpg "Metodología SCRUM")

### Objetivo general
* Plataforma inmobiliaria vertical web

### Objetivos específicos
1. Diseño, desarrollo e implementación de API .Net Core 3.1
2. Seguridad, autenticación y autorización (IdentityServer4)
3. Funcionalidades y caracteristicas asociadas a la vista de mapa/Catálogo
4. Funcionalidades y caracteristicas asociadas a la vista de detalle propiedad
5. Funcionalidades y caracteristicas asociadas a la vista de publicación propiedad
6. Funcionalidades y caracteristicas asociadas a la administración de la plataforma
7. Funcionalidades y caracteristicas asociadas a la administración de usuarios

## Planificación

La capacidad de desarrollo es de **34 horas/semana**.

Según la metodología se definen siete epics:

* Epic	WPA-22	API (1 junio 2020 - 5 junio 2020)
* Epic	WPA-23	Seguridad, autenticación y autorización (1 junio 2020 - 5 junio 2020)
* Epic	WPA-24	Mapa/Catálogo (8 junio 2020 - 19 junio 2020)
* Epic	WPA-25	Detalle propiedad (15 junio 2020 - 26 junio 2020)
* Epic	WPA-26	Publicación propiedad (22 junio 2020 - 3 julio 2020)
* Epic	WPA-27	Administración (29 junio 2020 - 10 junio 2020)
* Epic	WPA-28	Usuarios (6 junio 2020 - 17 junio 2020)

Se estiman **102 stories/tareas** y una duración de **260 horas** distribuidas en **7 semanas**. 

Por lo tanto esto equivale a **7 sprints** de una semana de duración.

### Roadmap 
![alt text](https://i.ibb.co/PtSCXZL/weprojectapp-2020-05-25-05-00pm.png "Roadmap WeProject")
Roadmap por epic.

### Work breakdown structure

* __WPA Sprint 1 (1 junio 2020 - 5 junio 2020) (35 horas)__
	* Story	WPA-99	Publicar API
		* Subtask	WPA-130	Crear diagrama de la arquitectura de la aplicación	
		* Subtask	WPA-131	Crear diagrama de modelo de clases	
		* Subtask	WPA-132	Crear diagrama de modelo de datos	
		* Subtask	WPA-133	Crear repositorios de codigo	
		* Subtask	WPA-134	Configurar infraestructura	
		* Subtask	WPA-135	Crear API	
		* Subtask	WPA-136	Crear interfaces	
		* Subtask	WPA-137	Crear clases abstractas	
		* Subtask	WPA-138	Crear implementaciones	
		* Subtask	WPA-139	Crear contexto de base de datos	
		* Subtask	WPA-140	Registrar el contexto de base de datos	
		* Subtask	WPA-141	Crear repositorio generico	
		* Subtask	WPA-142	Crear unit of work	
		* Subtask	WPA-143	Crear servicios	
		* Subtask	WPA-144	Registrar servicios dependency injection	
		* Subtask	WPA-145	Crear método de creación	
		* Subtask	WPA-146	Crear método de lectura	
		* Subtask	WPA-147	Crear método de actualización	
		* Subtask	WPA-148	Crear método de eliminación	
		* Subtask	WPA-149	Crear otros metodos	
		* Subtask	WPA-150	Publicar API	
	* Story	WPA-100	Implementar Seguridad
		* Subtask	WPA-101	Enforce HTTPS in ASP.NET Core
		* Subtask	WPA-102	ProtectKeysWithAzureKeyVault
		* Subtask	WPA-103	PersistKeysToFileSystem
		* Subtask	WPA-104	ProtectKeysWith*
		* Subtask	WPA-105	UnprotectKeysWithAnyCertificate
		* Subtask	WPA-106	SetDefaultKeyLifetime
		* Subtask	WPA-107	SetApplicationName
		* Subtask	WPA-108	DisableAutomaticKeyGeneration
		* Subtask	WPA-109	Per-application isolation
		* Subtask	WPA-110	Changing algorithms with UseCryptographicAlgorithms
		* Subtask	WPA-111	Implementar autenticación
		* Subtask	WPA-112	Secure user data
		* Subtask	WPA-113	Create owner, manager, and administrator authorization handlers
		* Subtask	WPA-114	Register the authorization handlers
		* Subtask	WPA-115	Implementar Swagger UI
		* Subtask	WPA-116	Adding IdentityServer to an ASP.NET Core application
		* Subtask	WPA-117	Configuring IdentityServer
		* Subtask	WPA-118	Install IdentityServer4 templates
		* Subtask	WPA-119	issuing tokens for various clients
		* Subtask	WPA-120	securing web applications and APIs
		* Subtask	WPA-121	adding support for EntityFramework based configuration
		* Subtask	WPA-122	adding support for ASP.NET Identity
		* Subtask	WPA-123	Setting up the ASP.NET Core application
		* Subtask	WPA-124	Defining an API Resource
		* Subtask	WPA-125	Defining the client
		* Subtask	WPA-126	Adding an API
		* Subtask	WPA-127	Add identity controller
		* Subtask	WPA-128	Adding a Nuget Dependency
		* Subtask	WPA-129	Configuration
* __WPA Sprint 2 (8 junio 2020 - 12 junio 2020) (42.5 horas)__
	* Task	WPA-65	Como Publisher quiero tener una ubicación representativa de la Propiedad
	* Task	WPA-58	Diseñar la vista Mapa/Catálogo
	* Story	WPA-155	Como User quiero una vista de Mapa/Catálogo
	* Story	WPA-154	Como User quiero buscar propiedades por zona seleccionada
	* Story	WPA-59	Como User quiero explorar propiedades en un mapa
	* Story	WPA-60	Como User quiero explorar propiedades en un catálogo
* __WPA Sprint 3 (15 junio 2020 - 19 junio 2020) (47.5 horas)__
	* Story	WPA-61	Como User quiero poder ordenar la lista de propiedades por ciertos criterios
	* Story	WPA-62	Como User quiero poder filtrar la lista de propiedades que se muestran
	* Story	WPA-63	Como User quiero poder ordenar la lista de propiedades por "Ranking de Mejor Información"
	* Story	WPA-64	Como User quiero poder ordenar la lista de propiedades por "Recomendación para el Usuario"
	* Story	WPA-66	Como user quiero tener una "paginación" de la lista de propiedades
	* Task	WPA-74	Diseñar la Vista de Detalle
	* Story	WPA-156	Como User quiero ver una Vista de Detalle
	* Story	WPA-72	Como User quiero ver un portafolio de una propiedad
* __WPA Sprint 4 (22 junio 2020 - 26 julio 2020) (38 horas)__
	* Story	WPA-69	Como User, quiero ver la información de la propiedad
	* Story	WPA-70	Como User quiero ver la ubicación aproximada de la propiedad en un mapa
	* Story	WPA-67	Como User, quiero ver las características del proyecto
	* Story	WPA-68	Como usuario, quiero ver los planos de la propiedad
	* Story	WPA-73	Como user, quiero poder compartir una propiedad
	* Story	WPA-71	Como User quiero poder solicitar la información de contacto al Publisher
	* Task	WPA-76	Definir criterios de cantidad máxima de archivos multimedia por propiedad
	* Task	WPA-77	Definir criterios de tamaño de archivos multimedia
	* Task	WPA-84	Diseñar la Vista de Publicación Propiedad
	* Story	WPA-157	Como User quiero ver una Vista de Publicación de Propiedad
	* Task	WPA-85	Definir criterios de evaluación solicitud de propiedad
	* Story	WPA-83	Como Publisher quiero poder cargar portafolio 
	* Story	WPA-81	Como publisher, quiero poder ingresar información de la propiedad
* __WPA Sprint 5 (29 junio 2020 - 3 julio 2020) (33 horas)__
	* Story	WPA-79	Como publisher, quiero poder ingresar la ubicación de la propiedad
	* Story	WPA-80	Como publisher, quiero poder ingresar los planos de una propiedad
	* Story	WPA-82	Como publisher quiero poder agregar características de la propiedad
	* Task	WPA-88	Diseñar Vista de Administración
	* Story	WPA-158	Como Admin quiero una vista de Administración
	* Story	WPA-86	Como administrador, quiero poder aceptar/rechazar solicitudes de publicación de propiedades
* __WPA Sprint 6 (6 julio 2020 - 10 julio 2020) (31 horas)__
	* Story	WPA-87	Como administrador, quiero poder administrar usuarios
	* Story	WPA-159	Como Administrador quiero poder administrar subscripciones
	* Story	WPA-92	Como user quiero registrar una nueva cuenta en el sistema
* __WPA Sprint 7 (13 julio 2020 - 17 julio 2020) (33 horas)__
	* Story	WPA-91	Como user quiero poder iniciar sesión en el sistema
	* Story	WPA-90	Como user, quiero tener un vista de perfil de usuario
	* Story	WPA-89	Como user, quiero poder ver un wishlist de propiedades
	* Story	WPA-93	Como user quiero recuperar contraseña
	* Story	WPA-98	Como usuario quiero comparar propiedades