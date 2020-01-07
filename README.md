# Singularity Registry Server Remote Build Plugin

## Contributors

## What is Singularity Registry Server Remote Build Plugin
Remote Build Plugin add singularity image building support to [Singularity Registry Server](https://singularityhub.github.io/sregistry).
It's provide also API REST endpoints to images management, like push, build...

## Image Included
As plugin of Singularity Registry Server, all Docker images involved in core project are used. One new docker image have been add for build activity:

 - **kamedodji/sregistry-builder**: is an [asgi](https://channels.readthedocs.io/en/latest/asgi.html) application, which extend Django to serve asynchronous application via [channels](https://channels.readthedocs.io/en/latest/) and Websocket Server [Daphne](https://github.com/django/daphne/).

For more information about Singularity Registry Server Remote Build Plugin, please check soon reference at 
[docs](https://singularityhub.github.io/sregistry-builder). If you have any issues, 
please [let me know](https://github.com/singularityhub/sregistry-builder/issues)!

## License

This code is licensed under the MPL 2.0 [LICENSE](LICENSE).
