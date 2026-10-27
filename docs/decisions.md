# Decision log

## D-001: System of interest is a BESS controller
**Date:** 27.10.2026
**Decision:** Build the project around a container-scale battery energy storage system controller.
**Reasoning:** It sits in the energy sector, where I am targeting roles, and it has safety-critical behaviour (thermal limits, emergency shutdown) and real interfaces (EMS, BMS, inverter). It can be specified entirely from public sources, and it is far enough from my Siemens Energy thesis to avoid any confidentiality overlap.
**Alternative considered:** a rail level-crossing controller, which would suit rail roles better.