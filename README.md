# OpenShift HAProxy Config

`haproxy-config.template` from https://github.com/openshift/origin/blob/release-3.11/images/router/haproxy/conf/haproxy-config.template.

`haproxy-config.template.patch` only sets the `X-Forwarded-Host` header to `Host` if it's missing.
