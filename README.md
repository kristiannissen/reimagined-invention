# Reimagined Invention
## Dart playground

Usefull information

### Dockerfile

```
FROM google/dart

RUN apt-get -y update
RUN apt-get -y upgrade
RUN apt-get -y install vim

COPY .vimrc /root
```

### Commands
run dart program

```
dart path-to-file.dart
```

