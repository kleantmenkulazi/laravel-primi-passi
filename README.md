# laravel-primi-passi



Ciao ragazzi,
oggi iniziamo a muovere i primi passi con questo fantastico framework che è Laravel!
Per prima cosa, creiamo un nuovo progetto Laravel 10, utilizzando questo comando:
composer create-project laravel/laravel:^10.0 laravel-primi-passi
oppure
composer create-project laravel/laravel:^10.0 .
Al termine dell'installazione, se abbiamo eseguito il comando specificando anche il nome della nuova cartella (cioè laravel-primi-passi), entriamo nella cartella del progetto
cd laravel-primi-passi
Dopodiché, avviamo l'artisan serve con uno di questi due comandi:
php artisan serve oppure php -S localhost:8000 -t public
A questo punto, iniziamo a prendere confidenza con le rotte e le views: cancelliamo la view welcome.blade.php e creiamo una nostra homepage. Facciamo quindi sì che la rotta / visualizzi home.blade.php
Inizialmente stampiamo un Hello World, poi passiamo dei dati alla view in modo da visualizzarli dinamicamente con Blade