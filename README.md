# <h1>Example Three Tier Application with Ansible with AWX</h1>

## <h2> This playbook provides an example of how you can configure a Three Tier Application with Ansible AWX. It uses an external variables file so that you can substitute values as needed. The tasks are broken down by function and are included using the main.yml file. You can also add/remove tasks to fit as needed. </h2>

### <h3> This playbook does the following: </h3>
        * Username/Passwords can be used. Vault or Sig-based auth is recommended
        * Creates a Tenant - tenant.yml
        * Creates a VRF - vrf.yml
        * Creates a Bridge Domain and BD subnets - bd.yml bd_subnet.yml
        * Creates an Application Profile - ap.yml
        * Creates an EPG - epg.yml
