# Troubleshooting

## Agent Not Appearing

Check Windows-to-Ubuntu connectivity, TCP 1515 during enrollment, TCP 1514 for agent communication, the manager address, the Windows agent service, and Wazuh logs on both systems.

## Dashboard Certificate Warning

A browser warning can occur when a lab dashboard uses a certificate that is not trusted by the browser. Verify the destination is the expected lab IP.

## Network Persistence

The Ubuntu SOC-Lab IP should be configured persistently rather than only with a temporary ip addr add command.
