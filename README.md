# Reactjs with Stubby 


Stubby makes your development environment act more like your
production environment. 

A local server suite with a declarative project-specific
configuration that helps the project see the host environment
just as it would see production if it were running there.

## Brief of this sample project

This project displays "School Name" and its "Tag Line". User can enter data and retive it back. This uses MongoDB as storage.  

This sample project will not use MongoDB. But the codes for it is all present.

To use our stubby I have overridden some fumctions and used the Stubby urls to GET, POST and DELETE data.
As following will explain you these terms.

## Installation

Install the stubby npm:

    > $ npm install -g stubby

Install the this project:

    > $ npm install
    > $ gulp
    
Gulp will use "gulpfile.js" and bundles all Javascript in './app/dist/main.js'. It also copies required css files in './app/dist/'.

Now start the server.
    > $ npm start
    
Now the server is running on http://localhost:7777

The page will not load as the stubby server is still not live.

So lets start stubby server now.

<strong>Open a new terminal</strong>
From the root use below commands

    > $ cd stubbyTest
    > $ stubby -d fi.yaml

The stubby server is now stared at http://localhost:8882.

Now refresh the page http://localhost:7777, You will be able to get the data from the stubby server.

The Stubby server will act as the api provider and serves the data.

Enjoy to code.