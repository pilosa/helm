# Pilosa Cluster Helm Chart


## Prerequisites

- helm v2

## Packaging

```
$ helm package pilosa
```

Creates the `pilosa-${VERSION}.tgz` package.

## Install

```
$ helm install --name my-release  --set persistentVolume.enabled=true ./pilosa-0.1.0.tgz
```

## Contact


## License

```
Copyright 2019 Pilosa Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
