# Teams-people service

DRF project for managing teams, tasks, employees.

## Installation

```shell
# Clone the repository
git clone https://github.com/b3v3kt0r/teams-people.git

# Set up .env file
You have create .env using .env.sample. like example

# Build docker-compose container
docker-compose build

# Run docker compose
docker-compose up

# Go into docker-container
docker exec -it <container id> sh

# Create super user
python managhe.py createsuperuser

# Check it out
http://localhost:8001/user/token/
```

## Features

* JWT authenticated.
* Admin panel.
* CRUD implementation for teams, task, employees(users) service.
* Filtering for teams.
* Pagination


## Contact
For contact me:
* Fullname: Stanislav Sudakov
* Email: stanislav.v.sudakov@gmail.com
* Telegram: @sssvvvff
