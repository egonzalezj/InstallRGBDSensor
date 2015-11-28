# InstallRGBDSensor
Install PrimseSense or Kinect Sensor

##Pasos de instalación

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Press enter

Fuente: https://github.com/Homebrew/homebrew

cd /usr/local/library/Formula

curl --insecure -O "https://raw.github.com/totakke/openni-formula/master/openni.rb"

curl --insecure -O "https://raw.github.com/totakke/openni-formula/master/sensor.rb"

curl --insecure -O "https://raw.github.com/totakke/openni-formula/master/sensor-kinect.rb"

curl --insecure -O "https://raw.github.com/totakke/openni-formula/master/nite.rb"

brew install libusb --universal

brew install openni

brew tap homebrew/science

brew tap totakke/openni

brew install openni

*** solo si no se va a usar kinect brew install sensor

*** solo si se usa el kinect brew install sensor-kinect

brew install nite

cd /usr/local/Cellar/openni/1.5.7.10/share/openni/samples/Bin/x64-Release
