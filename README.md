# Learn-Three.js-Fourth-edition
Готовность: в работе. 

Книга "Изучите Three.js"(Learn Three.js), четвертое издание, опубликована Packt |
Learn Three.js, Fourth edition, published by Packt


<a href="https://www.packtpub.com/product/learn-three.js-fourth-edition/9781803233871"><img src="https://static.packt-cdn.com/products/9781803233871/cover/smaller" alt="Learn Three.js, Fourth edition" height="256px" align="right"></a>

Это репозиторий кода для книги "Изучите Three.js"(Learn Three.js) [Learn Three.js, Fourth edition](https://www.packtpub.com/product/learn-three.js-fourth-edition/9781803233871), опубликован Packt. |
This is the code repository for [Learn Three.js, Fourth edition](https://www.packtpub.com/product/learn-three.js-fourth-edition/9781803233871), published by Packt.

**Программируйте 3D-анимацию и визуализацию для Интернета с помощью JavaScript и WebGL |
  Program 3D animations and visualizations for the web with JavaScript and WebGL**

## О чем эта книга?  | What is this book about?

Эта книга предназначена для разработчиков JavaScript, желающих научиться использовать библиотеку Three.js. |
This book is for JavaScript developers looking to learn the use of Three.js library.	

Эта книга охватывает следующие интересные возможности: | This book covers the following exciting features:

* Реализуйте различные элементы управления камерой, предоставляемые Three.js, для навигации по 3D-сцене. |
  Implement the different camera controls provided by Three.js to navigate your 3D scene
  
* Узнайте, как работать с вершинами напрямую для создания эффектов снега, дождя и галактики. |
  Discover working with vertices directly to create snow, rain, and galaxy-like effects
  
* Импортируйте и анимируйте модели из внешних форматов, таких как glTF, OBJ, STL и COLLADA. |
  Import and animate models from external formats, such as glTF, OBJ, STL, and COLLADA
   
* Создавайте и запускайте анимации, используя морфинговые цели и анимацию на основе костей. |
  Design and run animations using morph targets and bone-based animation
  
* Создавайте реалистично выглядящие 3D-объекты, используя расширенные текстуры материалов. |
  Create realistic-looking 3D objects using advanced textures on materials
   
* Взаимодействуйте напрямую с WebGL, создавая собственные вершинные и фрагментные шейдеры. |
  Interact directly with WebGL by creating custom vertex and fragment shaders
  
* Создавайте сцены с использованием физического движка Rapier и интегрируйте Three.js с VR и AR. |
   Make scenes using the Rapier physics engine, and integrate Three.js with VR and AR

Если вы чувствуете, что эта книга для вас, получите свою [копию](https://www.amazon.com/dp/1803233877) сегодня!  |
If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1803233877) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Инструкции и навигация  | Instructions and Navigations

Код будет выглядеть следующим образом:   | 
The code will look like the following:

```
const normalMap = new THREE.TextureLoader().load('/assets/textures/red-bricks/red_bricks_04_nor_gl_1k.jpg',(texture) => {
    texture.wrapS = THREE.RepeatWrapping
    texture.wrapT = THREE.RepeatWrapping
    texture.repeat.set(4, 4)
  }
)

```

**Для этой книги вам понадобится следующее: | Following is what you need for this book:**

Three.js стал отраслевым стандартом для создания потрясающего 3D-контента WebGL. В этом выпуске вы узнаете обо всех функциях Three.js и поймете, как интегрировать его с новейшими физическими движками. Вы также научитесь создавать и анимировать захватывающие 3D-сцены непосредственно в браузере, используя весь потенциал WebGL и современных браузеров.
Книга начинается с основных концепций и строительных блоков, используемых в Three.js, и помогает вам подробно изучить эти важные темы с помощью обширных примеров и образцов кода.

С помощью следующего списка программного и аппаратного обеспечения вы можете запустить все файлы кода, представленные в книге (главы 2-9). |

Three.js has become the industry standard for creating stunning 3D WebGL content. In this edition, you’ll learn about all the features of Three.js and understand how to integrate it with the newest physics engines. You'll also develop a strong grip on creating and animating immersive 3D scenes directly in your browser, reaping the full potential of WebGL and modern browsers.
The book starts with the basic concepts and building blocks used in Three.js and helps you explore these essential topics in detail through extensive examples and code samples. 

With the following software and hardware list you can run all code files present in the book (Chapter 2-9).

### Сопутствующие товары <Другие книги, которые могут вам понравиться> | Related products <Other books you may enjoy>

* Идем дальше с Babylon.js [[Packt]](https://www.packtpub.com/product/going-the-distance-with-babylonjs/9781801076586) [[Amazon]](https://www.amazon.com/Going-Distance-Babylon-js-maintainable-browser-based-ebook/dp/B09ZBB2Q1H) |
  Going the Distance with Babylon.js  [[Packt]](https://www.packtpub.com/product/going-the-distance-with-babylonjs/9781801076586) [[Amazon]](https://www.amazon.com/Going-Distance-Babylon-js-maintainable-browser-based-ebook/dp/B09ZBB2Q1H)

* 3D-графика в реальном времени с помощью WebGL 2 [[Packt]] (https://www.packtpub.com/product/real-time-3d-graphics-with-webgl-2- Second-edition/9781788629690) [[Amazon]](https://www.amazon.com/Real-Time-Graphics-WebGL-interactive-applications/dp/1788629698) |
  Real-Time 3D Graphics with WebGL 2 [[Packt]](https://www.packtpub.com/product/real-time-3d-graphics-with-webgl-2-second-edition/9781788629690) [[Amazon]](https://www.amazon.com/Real-Time-Graphics-WebGL-interactive-applications/dp/1788629698)


## Познакомьтесь с автором |Get to Know the Author

**Йос Дирксен(Jos Dirksen)** проработал разработчиком программного обеспечения и архитектором почти два десятилетия. У него большой опыт работы со многими технологиями, начиная от серверных технологий, таких как Java и Scala, и заканчивая разработкой внешнего интерфейса с использованием HTML5, CSS, JavaScript и Typescript. Помимо работы с этими технологиями, Джос регулярно выступает на конференциях и любит писать о новых и интересных технологиях в своем блоге. Ему также нравится экспериментировать с новыми технологиями и смотреть, как их лучше всего использовать для создания красивой визуализации данных. |

**Jos Dirksen** has worked as a software developer and architect for almost two decades. He has a lot of experience in many technologies, ranging from backend technologies, such as Java and Scala, to frontend development using HTML5, CSS, JavaScript, and Typescript. Besides working with these technologies, Jos regularly speaks at conferences and likes to write about new and interesting technologies on his blog. He also likes to experiment with new technologies and see how they can best be used to create beautiful data visualizations.

### Загрузите бесплатный PDF-файл | Download a free PDF
 
<i>Если вы уже приобрели печатную версию этой книги или версию Kindle, вы можете бесплатно получить PDF-версию без DRM.<br>Просто нажмите на ссылку, чтобы получить бесплатный PDF-файл.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781803233871">https://packt.link/free-ebook/9781803233871 </a> </p>
 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781803233871">https://packt.link/free-ebook/9781803233871 </a> </p>


## Ошибки | Errata

- На странице 11: перед запуском команд установки обязательно перейдите в каталог `source`. |
  On page 11: Before running the install commands, make sure to change to the `source` directory.  

- На странице 133: внизу страницы в книге упоминается vertextShader, это должно быть vertexShader. |
  On page 133: at the bottom of the page, the book mentions `vertextShader`, this should be `vertexShader`

