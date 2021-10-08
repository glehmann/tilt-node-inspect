#!/usr/bin/env python

docker_build(
    'gcr.io/foo/bar',
    '.'
)
k8s_yaml('k8s.yaml')
k8s_resource('node-inspect', port_forwards=['8080', '9229'])
