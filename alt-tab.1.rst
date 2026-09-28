..
   SPDX-License-Identifier: AGPL-3.0-or-later

   -------------------------------------------------------
   Copyright © 2024, 2025, 2026
               Pellegrino Prevete

   All rights reserved
   -------------------------------------------------------

   This program is free software: you can redistribute it
   and/or modify it under the terms of the
   GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the
   License, or (at your option) any later version.

   This program is distributed in the hope that it will
   be useful, but WITHOUT ANY WARRANTY; without even the
   implied warranty of MERCHANTABILITY or FITNESS FOR A
   PARTICULAR PURPOSE.
   See the GNU Affero General Public License
   for more details.

   You should have received a copy of the
   GNU Affero General Public License
   along with this program.
   If not, see <https://www.gnu.org/licenses/>.


========================
alt-tab
========================

--------------------------------------------------------------
Switches to a previously focused application.
--------------------------------------------------------------
:Version: alt-tab |version|
:Manual section: 1


Synopsis
========

alt-tab *[options]*


Description
===========

Switches to a previously focused application.


Options
=======

-N windows

  To which previously focused window
  from the current one to go back.
                   

-m method

  Method to perform the switch.
  All require administrative permissions.
  It can be:

  - input

    It performs the action using
    the 'input' command,

  - activity-launch

    It retrieves open windows list
    and runs the corresponding past
    activity. It avoids one to
    concretely press alt+tab but it
    may not work depending on the
    activity.
 

Application options
=====================
                              
-h

  Display help.


-c

  Enable color output


-v

  Enable verbose output


Bugs
====

https://github.com/themartiancompany/android-wm/-/issues


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.


See also
========

* windows-list
* activity-launch
* bbrightnessctl
* displayctl
* powerctl
* sissystemctl
* android-display-dim

.. include:: variables.rst
