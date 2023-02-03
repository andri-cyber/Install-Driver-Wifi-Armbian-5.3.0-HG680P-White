# Install-Driver-Wifi-Armbian-5.3.0-HG680P-White

How to install

    wget https://github.com/andri-cyber/Install-Driver-Wifi-Armbian-5.3.0-HG680P-White/blob/main/rtl8188fu.ko

    sudo cp rtl8188fu.ko /lib/modules/5.3.0-aml-g12/kernel/drivers/net/wireless/

    sudo /sbin/depmod -a

    sudo modprobe rtl8188fu
