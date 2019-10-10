<div align="center">
  <img alt="Mística Logo" src="https://i.imgur.com/3H975vE.png">
</div>
<h1 align="center">Mística Design Libraries</h1> <br>

<p align="center">
  <a href="#gettingStarted">Getting Started</a> •
  <a href="#installation">Installation</a> •
  <a href="#updating">Updating</a> •
  <a href="#features">Features</a> •
  <a href="#binds">Binds</a> •
  <a href="#wiki">Wiki</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#author">Author</a> •
  <a href="#support">Support</a> •
  <a href="#donate">Donate</a> •
  <a href="#license">License</a>
</p>



# Getting Started <a name="gettingStarted"></a>

### :computer: Project Setup  <a name="installation"></a>

1. Download and install latest version of [Kactus](http://kactus.io)
2. Clone repo in **Kactus**:
   >File > Clone repository > URL > `https://github.com/tef-novum/mistica-design-libraries.git`  
3. Generate Sketch files
    + Click in **Regenerate Sketch File** in each files in Kactus
      ![Kactus Regenerate File](https://i.imgur.com/8WHdEmf.png)

## Release Workflow in Kactus
La rama Máster siempre será la versión que está en producción. Asegurate de seleccionar la rama con la versión en la que quieras trabajar (desarrollo) porque no podrás hacer commit de tus cambios en la versión de producción y probablemente perderás tus cambios. Para saber qué versión de producción tienes que usar, mira arriba de este documento.

Cada viernes (si existen cambios sustanciales) se hará un merge de la branch activa de desarrollo a la máster.  **No dejes nada sin hacer commit o no saldrán en la release.**

Master branch always be a production version of Mística Design System Libraries. Ensure before of select a branch of the version that you want to work, you always have to work in Development branch, if you don't do that all of your changes will be lost. To know what version of development have to choose, see the first lines of this document.

#### POC Branches (Esto no debería ocurrir habitualmente)
Se puede dar el caso de que quieras hacer pruebas con nuevas features de Sketch o cualquier otra cosa que pueda entenderse como experimentación y que pueda romper cosas en la librería y además quieras mantenerlo guardado en Kactus para una futura integración.

Para referirnos a esto le hemos llamado *customBranch*
Una custom branch debe seguir una estructura en el nombre a la hora de crear la branch.
`SIGLAS-descripcion-corta`

For example  
Proof of concept  
`POC-autolayout-list`  

**Al crear la rama, no la publiques automáticamente, trabaja sobre ella y si consideras que es importante, publícala.**

**When you make a new branch, don't publish immediately, work on this branch and publish it when you consider that your work is substantial.**

## Danger Zone in Kactus
Cuando metas en Sketch las librerías de Kactus, ten siempre presente que si cambias de branch, las librerías de tu Sketch también cambiarán. Esto puede ser peligroso si alguien con una versión de esas librerías en Sketch abriera las librerías de Dropbox (lo cual no debería porque está terminantemente prohibido) y le diese a actualizar las librerías de Dropbox.

If you will go to use Kactus, when you download libraries in your computer, install the libraries from Kactus to Sketch (just drag and drop libraries sketch files to the Sketch > Preferences > Libraries). Be careful because if you change the branch in Kactus, libraries will change. Obviously, right?.

**Be careful updating library updates, make sure that you know what are you doing*

## Must to know
* **Branch**  
It is a copy from Master or other branch. You can work new things in this copy and when you finish, you can merge in Master.
* **Merge**  
The union of one branch and another.
* **Master**  
Main branch in the repository. In our case, production branch.
* **Repositorio**  
The place where all the files are located.
* **Commit**  
It is a confirmation to save and upload all your changes in a branch.
* **Fetch**  
Just a refresh action to know if there are something new in the repository. (new commits, new branches, etc.)
* **Pull**  
Download new updates to your files.
* **Push**  
Upload your work to the branch. When you make push, all of the people on the repository will get a Pull.


## Problem with Kactus
1. First time when you will sync Mistica repository you will not see sketch files, to generate this files click in "Regenerate sketch file" in each files in Kactus.

2. If Kactus fetching time is longer, better restart Kactus app.
