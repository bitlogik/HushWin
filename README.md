HushWin
=======

A Windows command shell script to disable all Windows services and software
about telemetry and tracking.

Many services and software in Microsoft Windows are collecting data about usage
and statistics, and then uploading these data to Microsoft servers in order to
get diagnostics and statistics about their software usage. For example, the
*Customer Experience Improvement Program* collects and uploads in background
many details about the usage and resources of your system. These tracking
systems are not necessary to run Windows and can be deactivated. This is the
purpose of HushWin that provides an easy way to disable these data collection
services. Disabling these services protect your privacy and strengthens your
digital security.

After years of experience in operating system security and digital privacy,
BitLogiK is publicly releasing this script to disable all tracking in one click.
We had scripts for Windows 7, then telemetry removal scripts and procedures for
our employees under Windows 10 since 2017. We feel it worthwhile to craft a
clean and full script for everyone.

We advise you to run this script after each Windows major update.


### Run it

-   Get the script cmd file in your Windows computer

-   Right click on *script.cmd* :

    -   Run as Administrator

-   Yes (accept)

-   Should display after some time : "successfully executed"

-   Hit any key to quit

You can reboot your computer to be sure about the settings enforcement.


**Benefits**

Improve your privacy and your security. Microsoft does not need to know what
happens inside your computer. Your system does not need to save on disk many
detailled logs on what you are doing. In addition, some malicious entities can
take advantage of all these additional information to target your private
information such as trade secrets or your physical security.

With all these services disabled, your Windows will have a little more resources
available : less RAM, less CPU cycles, and less disk space used by the system.
That will slightly speed up the applications, and extend your computer
battery and disk life. Some people are [reporting telemetry is using a considerable
usage of resources a certain times of the
day](https://twitter.com/christitustech/status/1414389086232666112), and this
can [save 5% of
memory usage](https://twitter.com/adamkee97/status/1413796890383052803).


**Drawbacks**

The logging data are limited, can be an issue during an investigation following
a security incident such as a ransomware or a virus infection. The higher the
privacy about logging, the lower the forensic material available.

Some companies can also benefit from the data uploaded to monitor their
computers fleet or police their employees. Disabling all these Windows services
can affect the monitoring quality.

Because of these, if your computer is a part of a company fleet or a supervised
professional domain, we recommend **you ask your IT department about the merits
of running HushWin** on your work computer.


**HushWin disables the following**

-   Diagnostics Tracking Service

-   Device Management Wireless Application Protocol Push message Routing Service

-   Customer Experience Improvement Program

-   AutoLogger event tracing session

-   AutoLogger Diagnostics Tracking Service Listener

-   Diagnostics Hub Standard Collector

-   Telemetry related scheduled tasks

-   Compatibility Telemetry process

-   Client Telemetry

-   Data Collection

-   SQM Logger

-   Application Telemetry

-   Microsoft Assistance Client feedback

-   Nvidia Telemetry Container

-   Office Telemetry Agent

-   Office Logging

-   Office Client Telemetry

-   Office feedback

-   Windows Remote Assistance

-   Windows Media Player usage tracking



### License

HushWin is free software: you can redistribute it and/or modify it under the
terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

HushWin is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
HushWin. If not, see <https://www.gnu.org/licenses/>.

