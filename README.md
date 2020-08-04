# Fibonacci Sequence React app

 > This app was made for practicing CI/CD pipelines with docker , travis CI and github actions

## Requirements

- Docker installed in your machine, for this, you can checkout [here.](https://www.docker.com/products/docker-desktop)
- Node js (optional but recommended in case you'll be making changes to the react app locally)
- travis CI account, you can create one by heading over to [https://travis-ci.org/](https://travis-ci.org/), 
once created, link it to the instantiated repo.
- Github account.

### Setup

- Clone the repo using ``git clone https://github.com/tngeene/fibonacci-sequence-react.git``

- Create a .env file using the provided ``.env.example`` file

- cd into the ``postgres/init`` directory
Run ``chmod u+x db-setup.sh`` to make the db-setup script executable. Once this is done, head back to the root of the project folder.

- Run ``docker-compose up --build`` to build the app.

- If everything works perfectly Visit ``127.0.0.1:8000``  on the your browser and the app should be rendered.
