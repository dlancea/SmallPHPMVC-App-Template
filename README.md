SmallPHPMVC-App-Template
========================

The folder/file template (and demo) for the SmallPHPMVC library. It includes a git submodule of the SmallPHPMVC library, located here: https://github.com/dlancea/SmallPHPMVC .

What's Included?
----------------

There is a Controller\App class in the app/controller directory, which should be the parent of any controller you might write.

The application layout is already included, and follows framework conventions. The "app" directory contains your application specific code, the include folder contains a few setup settings, and lib contains the mvc classes themselves.

Also included is an index controller, and an index template and layout. The index/index controller/action are the default route when nothing else is specified, so they are provided as an example, and to framework an action right from the get-go.