# Authentication Actions Toolbox

[![Quality](https://img.shields.io/badge/quality-demo-red)](https://curity.io/resources/code-examples/status/)
[![Availability](https://img.shields.io/badge/availability-source-blue)](https://curity.io/resources/code-examples/status/)

An example custom authentication workflow that uses actions to operate on user attributes.

## Custom Authentication Workflow

The following example workflow is used, which involves both custom data and custom logic:

![Example Workflow](images/authentication-workflow.png)

## Deploy the System

Get a license for the Curity Identity Server and copy it into the root folder.\
Also ensure that Docker is installed, then deploy the system with the following command:

```bash
./deploy.sh
```

Next login to the Admin UI at `https://localhost:6749/admin` with credentials `admin / Password1`.\
Navigate to the authentication service to view the configuration of authenticators and authentication actions.

## Documentation

See the [Authentication Actions Toolbox](https://curity.io/resources/learn/authentication-actions-toolbox/) tutorial for further details.\
This includes instructions on running an end-to-end setup on your local computer.

## Further Information

Please visit [curity.io](https://curity.io/) for more information about the Curity Identity Server.
