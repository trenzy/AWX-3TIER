# <h1>Example Three Tier Application with Ansible with AWX</h1>

## <h2> This playbook provides an example of how you can configure a Three Tier Application with Ansible AWX. It uses an external variables file so that you can substitute values as needed. You can also add/remove tasks to fit as needed. </h2>

### <h3> This playbook does the following: </h3>
        * Username/Passwords can be used. Vault or Sig-based auth is recommended
        * Creates a Tenant
        * Creates a VRF
        * Creates a Bridge Domain and BD subnets
        * Creates an Application Profile
        * Creates 3 EPGs - web/app/db (uses loop iteration)
        * Creates contracts
        * Creates filters and filter entries
        * Creates contract subjects and binds them to contracts
        * Binds the EPGs to the contracts
