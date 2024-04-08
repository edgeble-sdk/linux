NCM6B-SDK-6.1
=============

Build
-----

- Clone the sdk

  (Check the Ref, for dependencies)

  ::

        git clone --recursive git@github.com:edgeble-sdk/sdk-6.1.git

- Build the sdk
  ::

        cd sdk-6.1
        sdk-6.1# ./build.sh
        Log colors: message notice warning error fatal

        Parsing supported commands...

        Log saved at /tops/edgeble-sdk/sdk-6.1/output/sessions/2024-04-09_00-31-57
        WARN: /tops/edgeble-sdk/sdk-6.1/output/defconfig not exists
        Pick a defconfig:

        1. rockchip_defconfig
        2. rockchip_edgeble_ncm6a_cam1_defconfig
        3. rockchip_rk3588_evb1_lp4_v10_defconfig
        4. rockchip_rk3588_evb7_v11_defconfig
        5. rockchip_rk3588s_evb1_lp4x_v10_defconfig
        Which would you like? [1]: 2

Program
-------


Reference
---------
- docs/en/RK3588/Quick-start/Rockchip_RK3588_Quick_Start_Linux_EN.pdf
- Download the original sdk 'rk3588-linux-6.1-sdk.tar.gz' from

  ::

        https://drive.google.com/drive/folders/1Ebb3mCl1DU8wYj3oFEaEoxVq0MpweOLt?usp=sharing
        mkdir sdk-6.1 && cd sdk-6.1
        tar xvf rk3588-linux-6.1-sdk.tar.gz
        .repo/repo/repo sync -l
