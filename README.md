Document Convertor
==================

Document Convertor provides the facility of converting almost all office documents into image which make documents viewable without the need of any office suite.

Installation
------------

Assuming you are on debian/ubuntu and node and npm or yarn is already installed.

``` bash

sudo apt-get install imagemagick ghostscript poppler-utils unoconv

npm install # or yarn install

```


Running the application
-------

By Default the application will run on port 3000

``` bash

npm start

```


Docker
------

``` bash

docker pull registry.gitlab.com/chellem/odc:latest
docker run -p 3000:3000 registry.gitlab.com/chellem/odc:latest

```
