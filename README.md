# Installation SASS und Compass mit ruby oder node.js


##Installation mit Ruby
Compass bzw. Sass benötigt Ruby, daher müssen wir zuerst Ruby installieren.  
Bei OSX ist Ruby enthalten, falls nicht bitte folgendes ausführen.

###OSX

evtl. http://brew.sh/ installieren, danach kann ruby einfach installiert werden:  
`$brew install ruby`

###PC

`http://rubyinstaller.org/`  
 
Den Ruby Installer runterladen und schauen das  
<b>Add Ruby executables to your PATH</b> aktiviert ist.   

Wenn Ruby installiert ist kann mit **gem install {*paketname*}**
installiert werden.

##SASS installieren: 

OSX `$sudo gem install sass`  
PC `$gem install sass` 

##Compass installieren:

OSX `$sudo gem install compass`  
PC `$gem install compass`

###*Fehler beheben*

Oftmals hilft es die Ruby Version zu aktualisieren.

`$gem update --system`



##Installation mit node.js

Falls es nicht installiert ist, hier direkt pkg oder msi installieren:

http://nodejs.org/download/

###SASS installieren: *node.js als Alternative*

`$npm install node-sass`

###Compass installieren *node.js als Alternative*

`$npm install node-compass`

<br>
3. September 2014