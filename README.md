git clone https://github.com/facebookresearch/LASER.git
git clone swatitiwarii/aspect_capability
cp -r aspect_capability/ LASER/
cd LASER/
export LASER="${HOME}/projects/laser"
bash install_models.sh
bash install_external_tools.sh
pip install -r requirements.txt
sh run.sh
