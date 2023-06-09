
# WorldSkills Lyon 2024 Hungarian National Competition Finals - Web Technologies

## Test Project

The test project and marking scheme for all modules can be found in this repo, in the [TestProject folder](https://github.com/ws2024s17hu/ws2024s17hu-r3-tp/blob/master/TestProject).

## Setup

The docker based environment needed to solve test projects can be easily created in a local environment. This requires the creation of a folder structure and three repo clones.

1. Create a folder for the whole working environment with a name of your choice (e.g. ws2024s17hur3)

2. Create three more folders in the folder created in the previous step
	 - www
	 - assets
	 - docker
 3. Enter the folder you created in the first step and clone the [docker repo](https://github.com/ws2024s17hu/ws2024s17hu-r3-docker) with the following command:
	```shell
	git  clone  https://github.com/ws2024s17hu/ws2024s17hu-r3-docker.git  .
	```
4. Enter the www folder and clone the [www repo](https://github.com/ws2024s17hu/ws2024s17hu-r3-www) with the following command:
	```shell
	git  clone  https://github.com/ws2024s17hu/ws2024s17hu-r3-www.git  .
	```
	(Alternatively, you could create a fork of the www repository and clone the forked repository. In this case, the code containing the solution can be stored in the forked repository.)


5. Enter the assets folder and clone the [assets repo](https://github.com/ws2024s17hu/ws2024s17hu-r3-assets) with the following command:
	```shell
	git  clone  https://github.com/ws2024s17hu/ws2024s17hu-r3-assets.git  .
	```
6. Start the docker containers with the `docker-compose` command, which depends on the competitor's choice of developer tools. For a description of the docker-compose commands corresponding to the different options, see the docker repo [`README.md`](https://github.com/ws2024s17hu/ws2024s17hu-r3-docker/blob/main/README.md) file.Before running the docker-compose command, make sure that there are no other services running on the machine that use port 80 or 3306. 

**Important Note:**

In the local environment, addresses ending in `ub2023.hu` and `ub2023-YY.hu` can be replaced with `.localhost`. E.g. `admin.ub2023-01.hu` can be replaced by `admin.localhost`.

If you have any question about the test project or the docker environment, feel free to contact me at 	zoltan.sisak@gmail.com.
