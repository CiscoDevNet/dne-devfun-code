## Cisco DevNet Learning Labs: Developer Fundamentals Sample Code

This repository contains the sample code to go along with [Developer Fundamentals for DevNet Express](https://developer.cisco.com/docs/devfun-devnet-express/) exercises. During the hands-on exercises, you will clone this repository in the development environment.

## About this Sample Code

Contributions are welcome, and we are glad to review changes through pull requests. See [contributing.md](contributing.md) for details.

Once approved, Cisco DevNet reviewers then create a release to publish through our Learning Labs system.

The goal of these learning labs is to ensure a 'hands-on' learning approach rather than theory or instructions.

## About this code
Within this repository are several files and folders covering different topics and Labs.  This table provides details on what each is used for, and which labs they correspond to.  

|  File / Folder  |  Description  | 
|  ---  |  ---  | 
|  [`env_lab.py`](env_lab.py)  |  A Python file containing lab infrastructure details for routers, switches and appliances leveraged in the different labs.  This file provides a centralized  Python `import` that is used in  other code samples to retrieve IPs, usernames, and passwords for connections  | 
|  [`env_user.template`](env_user.template)  |  Similar to `env_lab.py`, this is a template for end users to copy within their own code repo as `env_user.py` where they can provide unique details for their own accounts.  For example, their Webex Teams (formerly Cisco Spark) authentication token.  Not all labs require this file, if one does it will be specified in setup.  | 
|  [`requirements.txt`](requirements.txt)  |  Global Python requirements file containing the requirements for **all** labs within this repository.  Each folder also contains a local `requirements.txt` file.  | 
| [`intro-python`](intro-python) | Files for the Python hands-on Labs. |
| [`rest-api`](rest-api) | Files for the REST API hands-on Labs. |
| [`postman`](postman) | Files for the Generating code with Postman Labs. |

## Contributing

These Learning Labs are for public consumption, so you must ensure that you have the rights to any content that you contribute.

## Getting Involved

* If you'd like to contribute to an existing lab, refer to [contributing.md](contributing.md).
* If you're interested in creating a new Cisco DevNet Learning Lab, please contact a DevNet administrator for guidance.

