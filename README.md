check_mk-sas2ircu
=================

Check_MK Check for LSI SAS2008, Dell PERC H200 Raid Controller (used in Dell R200, R210, R210II Servers)
using 'sas2ircu' commandline utility which has to be installed to use this plugin.

This is a check (agent plugin and server side check) to monitor the state of
physical disks and volumes connected to a raid controller addressed by 'sas2ircu' cli utility.

The utility 'sas2ircu' debian x64 package can be downloaded from 
http://hwraid.le-vert.net/debian/pool-wheezy/sas2ircu_16.00.00.00-1_amd64.deb and
installed with 'dpkg -i sas2ircu_16.00.00.00-1_amd64.deb'.

Copy the 'agent/pugins/sas2ircu' file to plugin directory of your agent.
Copy the 'check_mk/checks/sas2ircu' file to checks directory of your check_mk installation
(for omd use the '/omd/sites/<yoursite>/local/share/check_mk/checks' directory).
Copy the 'check_mk/checkman/sas2ircu' manpage file to man page directory of your 
check_mk installation (for omd use '/omd/sites/<yoursite>/local/share/check_mk/checkman' directory).

Tested with OMD and check_mk 1.2.2p1.


Copyright 2014 Leo Eibler (http://www.eibler.at)

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
