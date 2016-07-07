---
layout: post
title: Mi experiencia con Android.
tags: [first post, presentacion]
image:
  feature: android.png
comments: true
---


Hace ya unos meses, diciembre del año pasado para ser un poco más preciso, un compañero de la escuela de idiomas donde voy, que también se dedica al desarrollo de software, me hablo para saber si podría ayudarlo con un proyecto. 

Lo primero que le pregunte, fue de que se trataba y entonces me dijo, que era un proyecto para dispositivos Android y iOS. Me explico un poco de que se trata el proyecto y acepte ayudarlo. Ambos, no teníamos una idea sobre programación para móviles. Antes había tenido un ligero acercamiento en programación en Android, sin embargo no había escrito una sola línea de código. Mi experiencia era cero en resumen. Al igual que yo, mi compañero tampoco tenía experiencia en desarrollo para móviles, pero quería echar a andar su proyecto. 
 

### Decidiendo en donde programar.

El tiempo para terminar el proyecto era muy corto, 2 meses máximo, por lo que teníamos que buscar una plataforma que nos ayude a terminar el proyecto en ambos sistemas operativos. Al principio, ya nos habíamos dado a la idea de tener que aprender un nuevo lenguaje, XCode y Java. Mi compañero tenia una Mac para trabajar, por lo que el se quedo con la programación en iOS, creo que ya se imaginan quien se quedo con Android, ¿Verdad?. 
Terminado eso, empezamos a documentarnos lo mas rápido posible. No teníamos mucho tiempo para ello. Mientras nos documentábamos, empezamos a crear algunas funciones y ejemplos para el diseño de la app. 
Mi compañero tenia mas carga de trabajo, ya que el tenia que crear la estructura de la base de datos que utilizariamos. 
Mientras el trabajaba en eso, decidí buscar otro IDEs. Ya que ambos nos especializamos en programación C# y web, empecé a buscar IDEs compatibles con Android y iOS, mientras seguía documentandome en Java (de nuevo). 
Despues de 2 semanas buscando, documentandome y haciendo ejemplos en Android Studio, me tope con un IDE que respondía a nuestras plegarias.

### Xamarin Studio.

<figure>
	<a href=""><img src="https://www.xamarin.com/content/images/pages/branding/assets/xamarin-logo.png" alt=""></a>
	<figcaption></figcaption>
</figure>

Xamarin Studio fue ese IDE que respondía a nuestras plegarias. Xamarin combina tecnología .NET (algo a la que estábamos acostumbrados) con Android y iOS. ¿Qué significa esto? Que podíamos usar código C# para nuestras funciones y metodos, es decir, cross-platform, que lo que codificaramos se convertiría en código nativo para Android y iOS. Una verdadera maravilla, ya que nos ahorraría tiempo en el backend de la aplicación, dejando solamente a cada uno construir la interfaz según los estándares de cada plataforma.

Apenas conocimos el IDE, empezamos a revisarlo haciendo ejemplos y documentandonos para las interfaces de cada plataforma.

### Eventualidades.

Como sabrán, ningún proyecto esta exento de problemas, aunque en este caso, podría decirse que son eventualidades que realentizan el avance del proyecto. 
Como primera eventualidad, nos encontramos que el IDE no es gratuito, o al menos una parte de ello si lo es. El detalle radica en que usando la versión gratuita, pone una marca de agua en la aplicación, además de que solo se puede usar un numero limitado de veces al día, por lo que necesitábamos pagar una cuota al mes para poder usar la versión completa.
Dado que el proyecto, era para un cliente en especifico, se tomo la decisión de pagar dicha cuota, ya despues se le cobraría al cliente, me dijo.
Se compraron 2 licencias, una para Android y otra para iOS. 

Pasado eso, empezamos a construir los metodos y funciones que nos servirían. Mientras tanto, el cliente decidía, junto con otros colaboradores de mi compañero, el diseño de la aplicación. 


### Ahora si, los problemas.

Los metodos y funciones ya están listos, el diseño ya esta validado por el cliente, por lo que ya podíamos proseguir con las interfaces de usuario.
Una de las cosas que mas me tomo tiempo terminar y entender, fue el flujo en que el usuario se manejaría por la aplicación.
¿En que sentido?. Yo ya tenia mis interfaces listas y simplemente tenia que unirlas según el flujo que debía llevar.
Utilice "Fragments" para ello, pero como mencione, no entendía como unirlas a una actividad, o flujo en este caso. En vez de crear varias actividades concatenadas (que consumen mayor recursos y batería) de un flujo, ligar un fragmento de dicho flujo y continuar, de esta forma cuando se termine, termina todo el flujo (actividad).

