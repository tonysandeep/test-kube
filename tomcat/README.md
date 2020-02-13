docker command to build the image
// --rm remove intermode files created in the process -f points to a file -t tage image . {at last represtent the present current directory}
$$  docker build --rm -f Dockerfile -t dockeruser/image-name .
//then publish the image to docker hub reposistory
// image name should be in snall chars
$$ docker publish dockeruser/image-name

if you extend the image 
pls commit the stage
$$ docker commit CONTAINER_ID new-contianer-tag
