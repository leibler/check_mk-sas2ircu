check_mk-sas2ircu
=================

Check_MK Check for SAS2IRCU Raid Controller (used in Dell R200, R210, R210II Server)

This is a free check (agent plugin and server side check) to monitor the state of
disks and volumes connected to a sas2ircu raid controller.

Copy the 'agent/pugins/sas2ircu' file to plugin directory of your agent.
Copy the 'check_mk/checks/sas2ircu' file to checks directory of your check_mk installation.
(for omd use the '/omd/sites/<yoursite>/local/share/check_mk/checks' directory)

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
