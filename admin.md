---
layout: page
title: For Administrators
permalink: /admin/
---
The administrator quickstart is intended for system administrators who want to:

* Install and configure an Owncloud server.
* Enable users to connect to the Owncloud server.
* Add user accounts.

The tasks in this section require that you have administrator privileges.

1. Before you begin:

   1. Read the deployment [considerations](https://doc.owncloud.org/server/10.4/admin_manual/installation/deployment_considerations.html) and [recommendations](https://doc.owncloud.org/server/10.4/admin_manual/installation/deployment_recommendations.html).
   2. Ensure that your system adheres to the [system requirements](https://doc.owncloud.org/server/10.4/admin_manual/installation/system_requirements.html).

2. Follow the installation [instructions](https://doc.owncloud.com/server/admin_manual/installation/manual_installation.html) to install ownCloud Server manually.
   {% include note.html content="If you'd prefer to use the Docker image, refer to [Installing with Docker](https://doc.owncloud.org/server/10.4/admin_manual/installation/docker/) in the ownCloud documentation." %}

3. Configure the system according to your specifications. _It is important that you  configure ownCloud data storage, encryption, and other options before enabling users to connect. Refer to the [ownCloud documentation](https://doc.owncloud.com/server/10.4/admin_manual/configuration/) for more information about ownCloud configuration options._

4. Configure [User Auth LDAP](https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html) to enable users and specify the following values to enable users to connect to port 8080:
  
    Set... | To...
    --- | ---
    **Host** | Your IP address
    **Port** | `8080`

5. Add a user account as described in [User Management](https://doc.owncloud.com/server/admin_manual/configuration/user/user_configuration.html).
