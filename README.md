# ansible-escapace_releases

Configures the Escapace stable RPM repository and imports its signing key on
CentOS Stream and Rocky Linux 9 or later. The `escapace.epel` dependency also
configures EPEL and enables CRB. The role does not manage running services.

Run with gathered facts and root privileges. The managed host needs HTTPS access
to the Escapace and EPEL repositories. The role exposes no caller-settable
variables.
