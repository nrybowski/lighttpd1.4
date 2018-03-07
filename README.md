##Our goal

We are trying to improve the support of the MPTCP backup subflows to lighttpd1.4

The main purpose of this feature is to adapt the transmission rate of such a sublfow depending of the existence of non-backup subflow.

i.e. we may have a main MPTCP subflow on WiFi and a second backup subflow on cellular support. In this case, we want to use the second subflow at it's maximum rate only if the WiFi flow is broken.
