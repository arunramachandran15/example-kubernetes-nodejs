FROM node:8

ENV PORT 3001

EXPOSE 3001

COPY package.json package.json
RUN npm install

# Add your source files
COPY . .
CMD ["/bin/bash"]
