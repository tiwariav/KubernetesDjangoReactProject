#########
# FINAL #
#########

# pull official base image
FROM node:12.18.3-alpine3.9 

# set work directory
WORKDIR /usr/src/app

# install serve - deployment static server suggested by official create-react-app
RUN npm install -g serve

# copy our build files from our builder stage
COPY ./react_app/build ./build