# macOS_BigSur_Lenovo_v410z_OpenCore_EFI-
EFI folder contains fully supported to run Bir Sur on AIO Lenovo v410z

CPU: Intel i5 7500 3.4 GHz RAM: 16 GB GFX: Intel Graphics HD 630

Whats not worked:

    WiFi (removed module from M.2, i use Ethernet)
    Audio (disabled in BIOS, i use external USB-audio interface)

#Installation

    extract archive to the EFI partition at macos-drive

    disable Intel SGX

    disable CSM

    enable VM-d/t

    video memory set up to 64 MB, 128 MAX

    reboot and install

