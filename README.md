# puppet-petricore
Puppet deployment scripts for petriCORE

## Assumptions
The deployment script for jobs_exporter assumes that most packages used by the `jobs_exporter` are already installed on the machine (as with Magic Castle). For now it only installs `python36-psutil` package from the CC stack's wheels since it's the only package that was actually missing during the testing phase (on Magic Castle). Any further missing packages will be added if the need arises.
