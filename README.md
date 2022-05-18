# CoP-Secrets
CoP for secrets 


|Cost|Support|Prio  |Implementation|Usage|Maintenance|Product maturity   |Current secret solution                     |Security guidelines|Encryption method|Bring your own key        |
|----|-------|------|--------------|-----|-----------|-------------------|--------------------------------------------|-------------------|-----------------|--------------------------|
|Free|None   |Fast time to market|Kubeseal binary for encryption - requires binary on users laptop|Kubeseal|Backup of keys|Actively maintained|Does not integrate with an existing solution|Secret isolation   |AES + RSA X509   |Create cert by itself     |
|Open Source|       |K8s GitOps native|Controller in cluster for decrypting|Offline usage requires public key (optional)|Cluster specific keys|                   |                                            |- Namespace        |                 |Optional to bring own cert|
|    |       |It does not solve long term security|Helm/Kustomize/Yaml|Manual secret rotation|Upgrades through helm/kustomize/Yaml|                   |                                            |- Strict           |                 |                          |
|    |       |      |              |     |Manual certificate rotation|                   |                                            |- Cluster wide     |                 |                          |



|Cost|Support|Prio  |Implementation|Usage|Maintenance|Product maturity   |Current secret solution                     |Security guidelines|Encryption method|Bring your own key        |
|----|-------|------|--------------|-----|-----------|-------------------|--------------------------------------------|-------------------|-----------------|--------------------------|
|Free|None   |Fast time to market|Kubeseal binary for encryption - requires binary on users laptop|Kubeseal|Backup of keys|Actively maintained|Does not integrate with an existing solution|Secret isolation   |AES + RSA X509   |Create cert by itself     |
|Open Source|       |K8s GitOps native|Controller in cluster for decrypting|Offline usage requires public key (optional)|Cluster specific keys|                   |                                            |- Namespace        |                 |Optional to bring own cert|
|    |       |It does not solve long term security|Helm/Kustomize/Yaml|Manual secret rotation|Upgrades through helm/kustomize/Yaml|                   |                                            |- Strict           |                 |                          |
|    |       |      |              |     |Manual certificate rotation|                   |                                            |- Cluster wide     |                 |                          |

