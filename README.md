# SpeedWinter V3
> Sử dụng `Icxtify-v6`

## Model `vx0`-`v0x`
+ Link : [v0x-vx0](https://colab.research.google.com/drive/1RBNEKyoLTWvg_O4PYjM21AlvH6_Ch_Ca?usp=sharing)

## Model `v8a`
+ Link: [v8a](https://console.cloud.google.com/getting-started?pli=1)
+ Actions : `Active Cloud Shell`
+ Steps 1 : Run `docker run -p 6080:80 dorowu/ubuntu-desktop-lxde-vnc`
+ Steps 2 : Click `Web Preview -> Change port -> 6080 -> Change & Preview`

# Model v11c
+ Open github, choose a project
+ Download chrome:
```
mkdir ~/setup-chrome && cd ~/setup-chrome

# Install Google Chrome
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb -y

# Install Chromedriver
CHROME_MAJOR_VERSION=$(google-chrome-stable --version | ruby -e 'puts $stdin.read[/\d+/]')
CHROMEDRIVER_VERSION=$(curl -sS https://chromedriver.storage.googleapis.com/LATEST_RELEASE_${CHROME_MAJOR_VERSION})
wget https://chromedriver.storage.googleapis.com/${CHROMEDRIVER_VERSION}/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
sudo mv chromedriver /usr/local/bin/
```
