Monitoring Openshift Container Platform

The module will check the resources of the projects; replicaset, buildconfigs, services and other elements of the projects.
The goal for first realease is make the calls to Openshift Rest API and save it after to no-relational database.

For each call of OCP we need to have a token and the role user will be [admin]
The token depends the user, and you can get it run the follow:
 
 oc whoami -t

REST API OCP

/oapi/v1/namespaces/mxcampuspay-pre/buildconfigs 
/oapi/v1/projects
/oapi/v1/namespaces/mxcampuspay-pre/deploymentconfigs
/oapi/v1/namespaces/mxcampuspay-pre/builds
/oapi/v1/namespaces/mxcampuspay-pre/buildconfigs
/api/v1/namespaces/mxcampuspay-pre/services
/oapi/v1/namespaces/mxcampuspay-pre/routes
/api/v1/namespaces/mxcampuspay-pre/secrets
/oapi/v1/namespaces/mxcampuspay-pre/imagestreams
/api/v1/namespaces/mxcampuspay-pre/pods/campuspay-79-mvbn9

#REST API MONITOR
TODO...
