# Legion Y730 running macOS Catalina 10.15.6
<p align="justify" >
If you are a windows user and require macOS to learn XCode, then you can transform your windows machine into the Hackintosh machine. Remember, this tutorial is for educational purpose. I will be not responsible for any damage done to your device while installing macOS. Do at your own risk. This tutorial is only for Lenovo legion Y730/Y740. Back up your important files before starting. All files, that you require for macOS installation, are available in my GitHub page. This guide is in <b>chronological order</b>. So, do not miss any steps. Now let's begin.
</p>
<p align="center"><img src="images/macOS.png"></p>


## Make Bootable USB with macOS Catalina or Windows 10:
- Here I will explain the process of making a bootable USB drive. So be patience:
  - Size of the USB drive should be 16GB or more.
  - Use USB 2.0 drive, to avoid error like: 🚫  sign with [dark background](https://github.com/md-siam/Hackintosh-Legion-Y730_Y740/blob/master/images/USB_Disconnected.jpg)
  - Use Unibeast for making a bootable USB, and for that you can should first install macOS into a VirtualBox (assuming u don’t have access to a macOS).
  - You can download the macOS macOS.dmg file from [geekrar.com](https://www.geekrar.com/download-macos-mojave-dmg-file-direct-links/), then open it through VirtualBox.
  - After making a USB bootable device, download "Clover Configurator" inside VirtualBox. Mount the EFI partition using clover configurator, and replace the EFI folder with my EFI folder (unzip EFI.7z before placing it inside EFI partition).
  - Done with bootable USB device.
