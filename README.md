JAMTK
=====

Using as submodule :
--------------------

git submodule add -b master  git@github.com:Neekobus/jamtk.git jamtk
git submodule init
git submodule update

TBD : 
-----
 * Entities : Vectors, boxes
 * inputManager (pointer, keyboard)
 * soundManager with options (fadin, out, repeat) + preloader
 * universalPreloader
 * AStarFinder (vector array as response)
 * BresenhamFinder (vector array as response)
 * LevelLoader (with custom levelBuilder)
 * CenteredCanvas (on resize) & fullscreen handler
 * Basic actor (position, move strategy, imageKey) ?
 * menu ? 

Components : ImageManager
-------------------------

 * Use "new JAMTK.ImageManager()" to match images keys with ids in DOM.
 * Use "new JAMTK.ImageManager("sprite", "medias/sprites")" to use the sprite sheet located in "medias/" (sprites.json and medias/sprites.png) 
  
 * When you need the image, simply use the getImage(key, [variant]) method.
 * TODO : allow array for key or variant.

