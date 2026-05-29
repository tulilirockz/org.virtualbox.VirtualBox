# VirtualBox Flatpak (unofficial)

Virtualbox packaged as a flatpak! - Uses [KVM support patches](https://github.com/cyberus-technology/virtualbox-kvm) provided by cyberus-technology to run virtual machines.

| x86_64  | [Download URL](https://nightly.link/tulilirockz/org.virtualbox.VirtualBox/workflows/build-flatpak.yaml/main/VirtualBox-x86_64.flatpak.zip) |
|---------|----------------------------------------------------------------------------------------------------------------------------------------|
| aarch64 | [WIP](https://github.com/tulilirockz/org.virtualbox.VirtualBox/issues/2)                                                               |

<img width="1688" height="1429" alt="image" src="https://github.com/user-attachments/assets/98d64ae7-d555-474a-91ba-158d8e0f4d56" />

## Installation

Open up Github actions CI and download the bundle off of the workflows, or click on the [nightly.link](https://nightly.link/
) URL on the table above. 

Install the flatpak bundle file from within the `.zip` folder, then install it with `flatpak install /path/to/virtualboxbundle.flatpak`.
