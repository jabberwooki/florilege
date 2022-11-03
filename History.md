  * Ajout du slogan du site.
  * DDEV config : nginx remplacé par apache.
  * Installation du theme contrib bootstrap5 et création du sous-thème florilege_b5.
  * Ajout de la langue anglaise. La langue française reste la langue par défaut.
  * Installation et activation des modules contrib suivants : admin_toolbar, admin_toolbar_tools, pathauto, metatag, xmlsitemap, redirect, paragraphs et twig_tweak.
  * Installation des modules devel, devel_php et devel_kint_extras. Leur activation et paramétrage n'est pas exporté par déclaration dans settings.local.php (voir variable ['config_exclude_modules']).
  * Activation des modules multilingues config_translation et content_translation.
  * Premier commit après réinstall du projet avec Posgresql à la place de MySQL.
  * Install et activation des modules contrib suivants : admin_toolbar, admin_toolbar_tools, pathauto, metatag, xmlsitemap, redirect, field_group, paragraphs et twig_tweak.
  * Install des modules de dev : devel, devel_php, devel_kint_extras. Mais config non exportée.
  * Export de la config initiale, après install de Drupal, paramétrage des fichiers settings.php et settings.local.php, et activation des modules multilingues du noyau.
  * Initial commit