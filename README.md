# Settings

The System Settings application for Cutefish Desktop.

![screenshot](screenshots/Screenshot_20211025_150819.png)

## Ubuntu Dependencies

```shell
sudo apt install cmake debhelper extra-cmake-modules libicu-dev libcrypt-dev libfreetype6-dev libfontconfig1-dev libkf5networkmanagerqt-dev libkf5config-dev modemmanager-qt-dev qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev qttools5-dev-tools qml-module-qtquick-controls2 qml-module-qtquick2 qml-module-qtquick-layouts qml-module-qt-labs-platform qml-module-qt-labs-settings qml-module-qtqml qml-module-qtquick-window2 qml-module-qtquick-shapes qml-module-qtquick-dialogs qml-module-qtquick-particles2
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Intall

```shell
sudo make install
```

## Uninstall

```shell
rm /usr/bin/cutefish-settings
rm /usr/share/applications/cutefish-settings.desktop
rm /usr/share/cutefish-settings/translations/ar_AA.qm
rm /usr/share/cutefish-settings/translations/az_AZ.qm
rm /usr/share/cutefish-settings/translations/be_BY.qm
rm /usr/share/cutefish-settings/translations/be_Latn.qm
rm /usr/share/cutefish-settings/translations/bg_BG.qm
rm /usr/share/cutefish-settings/translations/bn_BD.qm
rm /usr/share/cutefish-settings/translations/bs_BA.qm
rm /usr/share/cutefish-settings/translations/cs_CZ.qm
rm /usr/share/cutefish-settings/translations/da_DK.qm
rm /usr/share/cutefish-settings/translations/de_DE.qm
rm /usr/share/cutefish-settings/translations/en_US.qm
rm /usr/share/cutefish-settings/translations/eo_XX.qm
rm /usr/share/cutefish-settings/translations/es_ES.qm
rm /usr/share/cutefish-settings/translations/es_MX.qm
rm /usr/share/cutefish-settings/translations/fa_IR.qm
rm /usr/share/cutefish-settings/translations/fi_FI.qm
rm /usr/share/cutefish-settings/translations/fr_FR.qm
rm /usr/share/cutefish-settings/translations/he_IL.qm
rm /usr/share/cutefish-settings/translations/hi_IN.qm
rm /usr/share/cutefish-settings/translations/hr_HR.qm
rm /usr/share/cutefish-settings/translations/hu_HU.qm
rm /usr/share/cutefish-settings/translations/id_ID.qm
rm /usr/share/cutefish-settings/translations/ie.qm
rm /usr/share/cutefish-settings/translations/it_IT.qm
rm /usr/share/cutefish-settings/translations/ja_JP.qm
rm /usr/share/cutefish-settings/translations/lt_LT.qm
rm /usr/share/cutefish-settings/translations/lv_LV.qm
rm /usr/share/cutefish-settings/translations/mg.qm
rm /usr/share/cutefish-settings/translations/ml_IN.qm
rm /usr/share/cutefish-settings/translations/nb_NO.qm
rm /usr/share/cutefish-settings/translations/ne_NP.qm
rm /usr/share/cutefish-settings/translations/nl_NL.qm
rm /usr/share/cutefish-settings/translations/pl_PL.qm
rm /usr/share/cutefish-settings/translations/pt_BR.qm
rm /usr/share/cutefish-settings/translations/pt_PT.qm
rm /usr/share/cutefish-settings/translations/ro_RO.qm
rm /usr/share/cutefish-settings/translations/ru_RU.qm
rm /usr/share/cutefish-settings/translations/si_LK.qm
rm /usr/share/cutefish-settings/translations/sk_SK.qm
rm /usr/share/cutefish-settings/translations/so.qm
rm /usr/share/cutefish-settings/translations/sr_RS.qm
rm /usr/share/cutefish-settings/translations/sv_SE.qm
rm /usr/share/cutefish-settings/translations/sw.qm
rm /usr/share/cutefish-settings/translations/ta_IN.qm
rm /usr/share/cutefish-settings/translations/tr_TR.qm
rm /usr/share/cutefish-settings/translations/tzm.qm
rm /usr/share/cutefish-settings/translations/uk_UA.qm
rm /usr/share/cutefish-settings/translations/uz_UZ.qm
rm /usr/share/cutefish-settings/translations/vi_VN.qm
rm /usr/share/cutefish-settings/translations/zh_CN.qm
rm /usr/share/cutefish-settings/translations/zh_HK.qm
rm /usr/share/cutefish-settings/translations/zh_TW.qm
```

## License

This project has been licensed by GPLv3.
