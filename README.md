Root Actions Service Menu
Root Actions servicemenu provides a convenient way to perform several actions 'as root', from the right-click context menu in KDE filemanagers.

Files: DEBIAN/*
Copyright (C) 2016-2018 Paweł Pijanowski
License: GPL-2

Files: /usr/bin/* and /usr/share/kservices5/ServicesMenu/*
Author: Kubicle <mail.kubicle@gmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
-------------
perl
menu
kde-baseapps-bin
kde-runtime
dolphin
kwrite | kate
ark
krename
xdg-utils

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall
