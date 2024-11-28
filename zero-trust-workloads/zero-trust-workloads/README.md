# Docker_Node.js-example

A sample node.js app in docker

Just npm install and then run npm start
the app will be running on local host

then you have to install cosign and kyverno

after installing, build and push an image on the docker

after pushing the image, sign the image using cosign

create 2 pods.yaml, one for signed image and other for any unsigned image

then. apply the changes kubectl apply

you'll see that the unsigned pod is not created as it is not SIGNED. 



All demo screenshots are added in the blog

