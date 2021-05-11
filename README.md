automation-containers
=========

Containers com ferramentas de automação e devops.

Lista de ferramentas
------------

- PostgreSQL versão 13.2  (Dependência do Sonarqube)
- Sonarqube versão 8.9.0-community
- jenkins versão LTS
- Rundeck versão 3.3.10


Script para criar as pastas dos volumes
------------

    ./create_dirs.sh


Script para subir os containers
------------

    ./start.sh


Script para destruir os containers
------------

    ./stop.sh


Script com configurações para o Sonarqube
------------

Antes de subir os containers do Sonarqube, rodar o script (só uma vez na sessão de usuario)

    ./sonar_requirements_session.sh


License
-------

MIT