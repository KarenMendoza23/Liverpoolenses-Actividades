# Comandos de gcloud

## Listar Compute Engine.

[Link](https://cloud.google.com/sdk/gcloud/reference/compute/instances/list)
``` 
gcloud compute instances list [NAME …] [--regexp=REGEXP, -r REGEXP] [--zones=ZONE,[ZONE,…]] [--filter=EXPRESSION] [--limit=LIMIT] [--page-size=PAGE_SIZE] [--sort-by=[FIELD,…]] [--uri] [GCLOUD_WIDE_FLAG …]
```

## Listar IPs en uso, existentes o reservadas.

[Link](https://cloud.google.com/sdk/gcloud/reference/compute/addresses/list)
``` 
gcloud compute addresses list [NAME …] [--regexp=REGEXP, -r REGEXP] [--global     | --regions=[REGION,…]] [--filter=EXPRESSION] [--limit=LIMIT] [--page-size=PAGE_SIZE] [--sort-by=[FIELD,…]] [--uri] [GCLOUD_WIDE_FLAG …]
```

## Listar buckets disponibles.

[Link](https://cloud.google.com/storage/docs/listing-objects?hl=es-419)
``` 
storage.objects.list
```

## Listar Service Accounts existentes en un proyecto.

[Link](https://cloud.google.com/iam/docs/service-accounts-list-edit?hl=es-419#iam-service-accounts-list-gcloud)
``` 
gcloud iam service-accounts list
```

