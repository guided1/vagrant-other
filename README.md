Clone this repository into a folder called "vagrant-definition""

Then clone your main project code repositories into a folder called "code"

You're looking to create a structure like

    |-- vagrant-definition
    |   |
    |   +-- Vagrantfile
    |
    -- code
       |-- erp-mainline // main erp codebase
       |    |
       |    +-- ... code
       |
       |-- erp-config // erp configuration
       |    |
       |    +-- ... code
       |
       |-- restoredb-mainline // database import scripts
       |
       |-- fums (not yet included in the vagrant file)
       |
       |-- booking-engine (not yet included in the vagrant file)

You can view the mounts in the vagrant file to see where you will be able to access them in the vm
