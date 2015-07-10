#Drupal Boilerplate#
-

Drupal boilerplate não é um módulo. Em vez disso, apenas serve como uma estrutura de diretórios para iniciar um novo site Drupal. A idéia por trás Drupal boilerplate veio de trabalhar em tantos sites diferentes, cada um seguindo suas práticas de desenvolvimento, estrutura de diretórios, diretrizes de implantação, etc ...

Drupal boilerplate tenta simplificar o início de um novo site fornecendo a estrutura de diretórios comum e arquivos já incluídos e configurados.

##Iniciando##
Você pode iniciar [baixando](https://github.com/TallerWebSolutions/drupal-boilerplate/zipball/master)
este projeto. Após baixa-lo cada diretório contem um arquivo readme.md.
Este readme.md file contém uma extensa documentação explicando o que pertence ao diretório específico (Em inglês).

Aqui temos uma descrição de uso de cada directorio/arquivo. Se você deseja saber mais por favor leia o readme dentro do diretório específico.

* [docroot](https://github.com/handrus/drupal-boilerplate/tree/master/docroot)
 * A raiz da sua intalação Drupal.
 * O arquivo settings.php não é ignorado pelo  git, é esperado que se use um arquivo de include, ex.: settings.local.php
   aonde as configurações de ambiente devem estar.
* [drush](https://github.com/handrus/drupal-boilerplate/tree/master/drush)
 * Contém comandos, alias e configurações de drush específicas do projeto.
* [results](https://github.com/handrus/drupal-boilerplate/tree/master/results)
 * Este diretório é usado para exportar o resultado de testes. Um bom exemplo é quando é executado pareview.sh src/modules/custom/ > results/$(date +"%Y%m%d")_code.html. Você pode exportar o resultado de um teste para ser exibido ou parseado por outra ferramenta.
* [scripts](https://github.com/handrus/drupal-boilerplate/tree/master/scripts)
 * Diretório para scripts de automação de processos do projeto.
* [tests](https://github.com/handrus/drupal-boilerplate/tree/master/tests)
 * Diretório para testes externos. Excelente para testes não específicos do Drupal como selenium, qunit, caperjs ou cucumber.
* [databases](https://github.com/handrus/drupal-boilerplate/blob/master/databases)
 * Diretório usado para guardar dumps de bancos de dados como MySQL, MongoDB e outros, usado para o boot inicial de novos ambientes.
* [configs](https://github.com/handrus/drupal-boilerplate/blob/master/configs)
 * Configurações para softwares como Solr, Apache, MySQL etc. Preferencialmente utilizando Ansible, Puppet ou Chef.
* [.gitignore](https://github.com/handrus/drupal-boilerplate/blob/master/.gitignore)
 * Contém a lista de arquivos que normalmente deve ser ignorados pelo versionamento.

Built by Robots&trade;
