# Introduction

The purpose of this APP is to demonstrate, what it takes for a developer to interact with OpenShift Container Storage Object Bucket Claim feature and consume Object Storage as a persistent layer.


# Deployment

- Deploy the App
  - `` oc create -f default-bucket.yaml ``
  - `` oc create -f photo_album_app_on_OCS_OBC.yaml ``


This should create an OBC and other stuff needed for the app itself like POD,SVC,ROUTE. Together with OBC, you will also get new secrets and config maps created. The important resources could be listed as
- `` oc get po,svc,route,obc,secret,cm``

At this point your app is ready to be accessed externally. Grab the URL and browse it

- A simple landing page of the app will appear, click on the "button" to enter





