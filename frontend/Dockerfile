# FROM mhart/alpine-node:5.6.0 AS development
# ENV NODE_ENV development
# # Add a work directory
# WORKDIR /app
# EXPOSE 3000  

# CMD ['npm', 'start'] 

# COPY package.json /src 

# COPY package.json .
# RUN npm install 
# COPY . .

# # Cache and Install dependencies

# # COPY yarn.lock .
# # RUN yarn install


# # Copy app files

# # Expose port
# # Start the app

FROM node:10 

WORKDIR /app 

COPY . .

EXPOSE 3000 

CMD ['yarn', 'start', ] 
