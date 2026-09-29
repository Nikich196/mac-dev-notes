# Xcode 27: поды ниже iOS 15 не собираются

Ошибка «IPHONEOS_DEPLOYMENT_TARGET is set to 12.0, but the range of supported deployment target versions is 15.0 to 27.0» — старые библиотеки CocoaPods. Лечится в post_install Podfile: поднять IPHONEOS_DEPLOYMENT_TARGET подов до минимальной версии приложения. В Expo — через config plugin, иначе правка пропадёт при prebuild.
