# Larvel Model & Controller
Utilizzando l’ORM di Laravel:
 - creo un nuovo progetto Laravel 10
 - tramite phpMyAdmin creo un nuovo database laravel_model_controller
 - importo nel database la tabella movies
 - inserisco le credenziali per il database nel file .env
 - creo un model Movie <strong>(php artisan make:model Movie)</strong>
 - creo un controller che gestirà la rotta / <strong>(php artisan make:controller HomeController)</strong>
 - all’interno della funzione <strong>__invoke()</strong> del controller, recupero tutti i film dal database e li passo alla view per visualizzarli a schermo tramite delle cards.