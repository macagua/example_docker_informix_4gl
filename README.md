# IBM Informix 4GL Example

An example of [IBM Informix 4GL](https://www.ibm.com/es-es/products/informix) Developer Edition deployment with Docker.

<img width="720" alt="IBM Informix 4GL" src="https://raw.githubusercontent.com/macagua/example_docker_informix_4gl/refs/heads/main/docs/images/ibm-informix-logo.png">


## Download it

```
git clone https://github.com/macagua/example_docker_informix_4gl.git
cd ./example_docker_informix_4gl
```

## Install it

```
docker-compose up -d
```

## Create the Container

```
docker-compose up -d
```

## Check the Running Container

```
docker ps -a
```

## Check the Connection

Once the container is running, you can connect directly within the container
to test the engine using the classic `dbaccess` utility:

Log in to the container console:

```
docker exec -it informix_dev bash
```

Once you’re in, run the interactive tool:

```
dbaccess
```

From there, you can create your first test database and start practising basic
`SQL` statements.
