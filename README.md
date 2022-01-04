# Reimagined Invention
## Dart playground

Usefull information

### Dockerfile

```
FROM google/dart

RUN apt-get -y update
RUN apt-get -y upgrade

```
### Run container

```
docker run -it -v $(pwd)/src:/src [imageid]
```

### Commands
run dart program

```
dart path-to-file.dart
```

