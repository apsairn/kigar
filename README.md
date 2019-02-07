# Kigar

Kigar is a hackable package manager for Linux and macOS.The most of kigar is written by Rust Programming Language.Developer is developing its first version.

## Download

Kigar is developing,it is not developed.So you can not download Kigar.Wait a week left,The first version will be developed.If you want to download kigar,You can download it next weeek.

## Features

### New concept

1.**Iteration Group**

Kigar is based on Iteration Group.**Iteration Group** is a Abstract concept.Some packages in a group,The group name is Iteration Group.

2.**MicroID Key**

Run Kigar and select a MicroID Key Driving Server,gen a ***MicroID Key***,and storage datas you want to sync to it.If you have other computers or you will work on other computers,you can use your **microid key** to login the server,and Sync your datas.You can share too.

## Install

You can use source code or binary.If you want to install by Source Code :
`git clone github.com/apsairn/kigar.git
 cd kigar
 ./buildr
 tools/skigar task:build kigar
 tools/skigar /builded task:install kigar
 ` as root.
 
 If you want to install by Binary Files:
 `git clone github.com/apsairn/kigar.git
  cd kigar/release
  ./installr
  tools/skigar task:build kigar-installer
  ./kigar-installer
  ` as root.
