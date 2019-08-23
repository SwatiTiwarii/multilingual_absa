### Please follow following steps to setup the environment, dependencies and run the notebooks present in notebooks folder. ###


* conda create -n fb_laser python=3.6 anaconda 
* conda activate fb_laser
* git clone https://github.com/facebookresearch/LASER.git
* git clone https://github.com/SwatiTiwarii/multilingual_absa.git
* cp -R aspect_capability/. LASER/
* cd LASER/
* export LASER="${HOME}/LASER"
* bash install_models.sh
* bash install_external_tools.sh
* pip install -r requirements.txt
* bash run.sh
* cd notebooks/ 
