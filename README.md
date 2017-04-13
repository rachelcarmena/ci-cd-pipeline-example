# Pipeline examples

## Requirements

* [Docker](https://docs.docker.com/engine/installation/linux/ubuntu/#install-docker)
* Jenkins
    * User starting Jenkins must be added to the group **docker** (remember to re-login after adding the group)
        ```
        sudo usermod -aG docker $USER
        ```
    * Plugins:
        * Pipeline
