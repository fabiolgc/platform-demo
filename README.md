# WSO2 Platform Demo

## Prerequisites

 * Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), [Docker](https://www.docker.com/get-docker) and [Docker Compose](https://docs.docker.com/compose/install/#install-compose)
   in order to run the steps provided in following Quick start guide. <br><br>
 * In order to use Docker images with WSO2 updates, you need an active WSO2 subscription. If you do not possess an active WSO2
   subscription, you can sign up for a WSO2 Free Trial Subscription from [here](https://wso2.com/free-trial-subscription).
   Otherwise, you can proceed with Docker images which are created using general availability (GA) releases.<br><br>
 * If you wish to run the Docker Compose setup using Docker images built locally, build Docker images using Docker resources available from [here](../../dockerfiles/) and remove the `docker.wso2.com/` prefix from the `image` name in the `docker-compose.yml`. <br><br>
    
## Quick Start Guide

1. Clone this git repository.

    ```
    git clone https://github.com/fabiolgc/platform-demo.git
    ```
    > If you are to try out an already released zip of this repo, please ignore this 1st step. 