This project was done as a part of Google Summer of Code 2009.
It is a plugin to enable annotation of WikiPathways pathways with ontology terms and browse pathways according to those ontology terms. 

For more details on the project, visit the following links:
http://genmapp.cgl.ucsf.edu/wiki/Google_Summer_of_Code_2009
http://socrates2.cgl.ucsf.edu/GenMAPP/wiki/Google_Summer_of_Code_2009/Chetan

Installing this addon:

Add these lines to the file, "localsettings.php" , in the root folder of your Wikipathways installation :

require_once('wpi/extensions/otag/otags_main.php');
require_once('wpi/extensions/ontologyindex/ontologyindex.php');

Replace "wpi/pathwaypage.php" with the attached file.


