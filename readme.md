NOT FINISH -- IN PROGRESS

TODO
----

1. Finir le docker-compose
	- Faire l'instance de PHP-FPM avec l'extention php_mapscript (5.6 puis 7 quand la compatibilité mapscript sera ok)
	- Override l'instance web (nginx) avec la gestion de mapserver
	- Voir si Mapserver sera dans l'instance web ou dans une autre séparé
	- Augmenter la Stack Optimisation (Ex : Varnish)
	- Augmenter la Stack ElasticSearch (Ex : Kibana, Logstash)
	- Ajouter la vue d'ensemble des containers avec le système proposé par Docker (voir site officiel)

2. Rédiger le README
	- Explication & parametrage du dossier "usr"