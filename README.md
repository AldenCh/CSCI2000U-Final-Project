# CSCI2000U-Final-Project


**Steps to Run our Jupyter Notebook**
>1. Install [Docker](https://docs.docker.com/engine/install/ubuntu/) and [Docker Compose](https://docs.docker.com/compose/install/) on Ubuntu or WSL<br>
>2. Clone the necessary Docker files using git in your preferred directory:<br>
>&nbsp;&nbsp;&nbsp;&nbsp; - Using HTTPS Authentication with PAT: git clone https://github.com/maakemi/csci2000u-jupyter-notebook<br>
>&nbsp;&nbsp;&nbsp;&nbsp; - Using SSH Authentication: git clone git@github.com:maakemi/csci2000u-jupyter-notebook<br>
>3. Change into the cloned directory<br>
>4. Run the following two commands in your terminal<br>
>&nbsp;&nbsp;&nbsp;&nbsp; - **sudo service docker status**, **NOTE:** If docker is already running then there is no need for the second command<br>
>&nbsp;&nbsp;&nbsp;&nbsp; - **sudo docker service start**<br>
>5. Open up a new Ubuntu or WSL terminal and run **sudo docker run hello-world** to make sure docker works<br>
>6. Start the container with **sudo docker-compose up** to start the Jupyter environment and you will be given URLs which you can use in any browser to access the environment<br>
>7. Upload our Jupyter Notebook to your Jupyter environment and click it to run the notebook in a new tab<br>
>8. Click the two right facing arrows that look like a fast forward button in the toolbar at the top to run the entire notebook<br>
