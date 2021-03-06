..
  Copyright (C) 2014-2015 Igor Gnatenko

  This copyrighted material is made available to anyone wishing to use,
  modify, copy, or redistribute it subject to the terms and conditions of
  the GNU General Public License v.2, or (at your option) any later version.
  This program is distributed in the hope that it will be useful, but WITHOUT
  ANY WARRANTY expressed or implied, including the implied warranties of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General
  Public License for more details.  You should have received a copy of the
  GNU General Public License along with this program; if not, write to the
  Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA
  02110-1301, USA.  Any Red Hat trademarks that are incorporated in the
  source code or documentation are not subject to the GNU General Public
  License and may only be used or replicated with the express permission of
  Red Hat, Inc.

################################
Extras DNF Plugins Release Notes
################################

.. contents::

====================
 0.0.9 Release Notes
====================

Provides :doc:`show-leaves` and :doc:`versionlock`. Fixed some crashes in :doc:`migrate` and :doc:`repomanage`.

Bugs fixed in 0.0.9:

* :rhbug:`1226607`
* :rhbug:`1225282`
* :rhbug:`1230503`

====================
 0.0.8 Release Notes
====================

Many fixes in :doc:`migrate` plugin. Few cleanups in packagingi, now you can install `dnf-command(migrate)` to get `dnf-plugins-extras-migrare` installed.

Bugs fixed in 0.0.8:

* :rhbug:`1208773`
* :rhbug:`1211596`
* :rhbug:`1214807`
* :rhbug:`1223034`

====================
 0.0.7 Release Notes
====================

Renamed orphans to :doc:`leaves`. Fixed some crashes in :doc:`tracer`, :doc:`migrate` and :doc:`local`. Renamed ``--repoid`` to ``--repo`` in :doc:`repoclosure` and :doc:`repograph`. Old option saved for compatibility.

Bugs fixed in 0.0.7:

* :rhbug:`1208614`
* :rhbug:`1209864`
* :rhbug:`1209043`

====================
 0.0.6 Release Notes
====================

Provides :doc:`migrate` and :doc:`orphans`.

Bugs fixed in 0.0.6:

* :rhbug:`1201471`

====================
 0.0.5 Release Notes
====================

Adapt packaging to install Python 3 version for F23+. Provides: :doc:`debug`

Bugs fixed in 0.0.5:

* :rhbug:`1187763`
* :rhbug:`1192779`

====================
 0.0.4 Release Notes
====================

Fixes in packaging, include man pages for plugins.

====================
 0.0.3 Release Notes
====================

Trivial fixes in packaging, few improvements for plugins, tests for plugins. Provides: :doc:`local`, :doc:`repograph` and :doc:`repoclosure`.

Bugs fixed in 0.0.3:

* :rhbug:`1177631`
* :rhbug:`991014`

====================
 0.0.2 Release Notes
====================

Provides :doc:`repomanage`, :doc:`rpmconf` and :doc:`tracer`.

Bugs fixed in 0.0.2:

* :rhbug:`1048541`

====================
 0.0.1 Release Notes
====================

Provides :doc:`snapper`.
