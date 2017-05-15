# Network Security Confidence Analysis

This research attempts to evaluate sets of network metrics in order to assign a relative security confidence score to a particular network segment or flow.  This confidence score can then be used to assess the relative security of that segment, before, during and after sensitive data transmission.  While this research is primarily concerned with Software Defined Network(SDN) metrics, traditional network metrics are also used in the evaluation.

Our work is being developed in SDN northbound applications that are primarily SDN controller agnostic.  Today we use OpenDaylight as the primary controller due to it's robust API framework and the availability of SDN southbound applications.
