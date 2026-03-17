# onprem + cloud-deployment
Deployed a web app on On-prem &amp; then migrated to cloud

there is a web-app made with html/css/js going to deploy on on-prem then migrate that app to cloud

###### ON-PREM DEPLOYMENT ######
1) Created a ubuntu on-prem server on my local m/c using Vagrant on virtualBox
2) Installed nginx to serve the web app & access via localhost


###### CLOUD DEPLOYMENT ######
step 1) containerize
write a dockerfile
build & test the image locally

step 2) cloud push
push the image to registry

step3) cloud deploy
deploy to ECS, any containerization platform
OPTIONAL: configure domain & SSL cert (good for DNS practice)

PS: I'm trying to configure domanin & ssl cert part but not able to acquire domain name easily, most domains are costly
    Will try to find a way to configure domain & SSL

