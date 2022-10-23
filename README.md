# Docker scrapy-playwright with windows

This is a docker image for running scrapy with playwright on windows.

1) Pull tihs repo from github
2) Build the docker image
3) Run the docker image with the following command
    ```bash docker run -it -v ${PWD}:/app <YOUR IMAGE NAME>```
4) If you want to run after exiting the container, use the following command
    ```bash docker start <CONTAINER ID>```
    then
    ```bash docker exec -it <CONTAINER ID> bash```