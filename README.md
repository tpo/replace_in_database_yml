# replace_in_database_yml

This script has been created to manipulate database.yml or
other __simple__ yaml files from the shell or, respectively
from ansible.

It can only replace the value of a given key in a given section:

    $ replace_in_database_yml --help
    usage: replace_in_database_yml file_name section key value
           replace_in_database_yml --help
    
      Example:
    
        replace_in_database_yml database.yml production username my_rails_app_user

As said: __mind the gap!__ The script will not handle complicated stuff!

Author: Tomas Pospisek <tpo_deb@sourcepole.ch>

Copyright: public domain
