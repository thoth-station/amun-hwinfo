Amun's inspect-hwinfo
---------------------

This repository has an s2i build that is responsible for gathering information
about on nodes where the job execution of the inspection pods is done. This is
usefull if you are targetting some specific hardware requirements in your
application. The output of this application is a simple JSON file that states
CPU flags and memory information of the node.


Installation and Deployment
===========================

This application is part of Amun's deployment present in the
`amun-api repository <https://github.com/thoth-station/amun-api>`_.
