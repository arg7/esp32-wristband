Install Visual Code
Install ESP-IDF extension
Create a blank ESP-IDF project

from IDF Terminal:

mkdir -p components && \
cd components && \
git clone https://github.com/espressif/arduino-esp32.git arduino && \
cd arduino && \
git submodule update --init --recursive && \
cd ../.. && \
idf.py menuconfig


see: https://espressif-docs.readthedocs-hosted.com/projects/arduino-esp32/en/latest/esp-idf_component.html