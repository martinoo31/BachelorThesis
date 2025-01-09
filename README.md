# Analysis of ESA Bundle Protocol and LTP implementations
### Abstract
The advent of the space age demands robust communication infrastructures to support
operations in the harsh interplanetary space environment. The software infrastructure
and network architecture required for space missions have been studied extensively
since the 2000s. This research led to the development of the Delay/Disruption Tolerant
Networking (DTN) architecture, with the Bundle Protocol (BP) at its core, and to
associated new protocols, such as the Licklider Transmission Protocol (LTP). The
current version of the Bundle Protocol is version 7, standardized in RFC 9171 and
currently in the final phases of standardization by the Consultative Committee for
Space Data Systems (CCSDS), an international organization composed of major space
agencies specifically focused on space communication development. The objective of
this thesis was to collaborate with the European Space Agency (ESA) to analyze and
test its new implementations of BP and LTP. This software was made available to us by
ESA developers at thesis start, thus the tests described in this thesis were most likely
the first performed outside ESA. The aim of the analysis was to understand the general
workings of ESA’s implementations and to test their adherence to the standard. The
analysis included and extended a range of interoperability tests with ION, one of the
reference BP implementations; tests were later extended to other BP implementations,
such as Unibo-BP, DTNME and µDTN. The test campaign not only provided ESA
developers with independent feedback, including the discovery of few bugs, but also
revealed some unexpected problems in well-established implementations. This
highlights once more the necessity for independent interoperability testing, crucial to
ensure the resilience required by critical infrastructures such as future space
communication systems.
