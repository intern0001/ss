### Kubernetes Resource Updates:

| KIND                             | NAMESPACE     | NAME                                    | API_VERSION                            | REPLACE_WITH (SINCE)               |
|----------------------------------|---------------|-----------------------------------------|----------------------------------------|------------------------------------|
| Ingress                          | <undefined>   | etl-simulator-internal                  | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | etl-hub                                 | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| ClusterRoleBinding               | <undefined>   | eks-admin                               | rbac.authorization.k8s.io/v1beta1      | rbac.authorization.k8s.io/v1 (1.8.0)|
| ValidatingWebhookConfiguration   | <undefined>   | linkerd-sp-validator-webhook-config     | admissionregistration.k8s.io/v1beta1   | admissionregistration.k8s.io/v1 (1.16.0)|
| Ingress                          | <undefined>   | kanaloa-proxy                           | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| MutatingWebhookConfiguration     | <undefined>   | pod-identity-webhook                    | admissionregistration.k8s.io/v1beta1   | admissionregistration.k8s.io/v1 (1.16.0)|
| MutatingWebhookConfiguration     | <undefined>   | linkerd-proxy-injector-webhook-config   | admissionregistration.k8s.io/v1beta1   | admissionregistration.k8s.io/v1 (1.16.0)|
| ClusterRoleBinding               | <undefined>   | codefresh-user                          | rbac.authorization.k8s.io/v1beta1      | rbac.authorization.k8s.io/v1 (1.8.0)|
| Ingress                          | <undefined>   | booking                                 | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | kanaloa                                 | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | etl-simulator                           | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | artifactory                             | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| ClusterRoleBinding               | <undefined>   | santana-user                            | rbac.authorization.k8s.io/v1beta1      | rbac.authorization.k8s.io/v1 (1.8.0)|
| Ingress                          | <undefined>   | booking-internal                        | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | infra         | web-ingress                             | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | floorplan-service-internal              | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| CustomResourceDefinition         | <undefined>   | eniconfigs.crd.k8s.amazonaws.com        | apiextensions.k8s.io/v1beta1           | apiextensions.k8s.io/v1 (1.16.0)   |
| CustomResourceDefinition         | <undefined>   | jaegers.jaegertracing.io                | apiextensions.k8s.io/v1beta1           | apiextensions.k8s.io/v1 (1.16.0)   |
| CustomResourceDefinition         | <undefined>   | trafficsplits.split.smi-spec.io         | apiextensions.k8s.io/v1beta1           | apiextensions.k8s.io/v1 (1.16.0)   |
| CustomResourceDefinition         | <undefined>   | serviceprofiles.linkerd.io              | apiextensions.k8s.io/v1beta1           | apiextensions.k8s.io/v1 (1.16.0)   |
| Ingress                          | <undefined>   | oauth2-proxy-linkerd                    | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | etl-errors-hub                          | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | helios                                  | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | <undefined>   | graphql-schema-registry                 | networking.k8s.io/v1beta1              | networking.k8s.io/v1 (1.19.0)      |
| Ingress                          | infra         | eks-cors                                | networking.k8s.io/v1beta1              |                                      |
