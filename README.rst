⚠️ This repository have been **moved to a new project**: `iec870ree <https://github.com/gisce/iec870ree>`_ ⚠️
============================================================================================================

You can see the reasons `here <https://github.com/javierdelapuente/reeprotocol/issues/10>`_


reeprotocol
###########

.. image:: https://travis-ci.com/gisce/reeprotocol.svg?branch=gisce
    :target: https://travis-ci.com/gisce/reeprotocol   

.. image:: https://coveralls.io/repos/github/gisce/reeprotocol/badge.svg?branch=python_27_35
    :target: https://coveralls.io/github/gisce/reeprotocol?branch=python_27_35

	     

IEC-870-5-102 for REE Spanish Electric meters

Based on http://www.ree.es/sites/default/files/01_ACTIVIDADES/Documentos/Documentacion-Simel/protoc_RMCM10042002.pdf
and http://www.ree.es/sites/default/files/01_ACTIVIDADES/Documentos/Documentacion-Simel/AMPLIACION%20DEL%20PROTOCOLO%20Fase%202%202003-02-10.pdf


Installation
============

Just checkout the code, install the requirements and launch the examples with real information from devices.

To use the modem interface you will need a gsm modem. Have a look at http://www.ree.es/sites/default/files/01_ACTIVIDADES/Documentos/Documentacion-Simel/Simel_gsm_v1.0.pdf for more information.


Functions Implemented
=====================

At the moment this project is Work In Progress. I am not sure of all the aspects of the protocol, so I am writing/testing the libraries against real devices. So for now do not except this project to be anything more than a spike/prototype.

However at 20180613, there are working examples to read hourly data from meters both with tcpip and with a gsm connection.  
