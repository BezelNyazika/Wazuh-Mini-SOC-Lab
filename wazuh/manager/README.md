# Wazuh Manager

Ubuntu hosts the Wazuh Manager, Indexer and Dashboard.

Useful checks:

    sudo systemctl status wazuh-manager
    sudo systemctl status wazuh-indexer
    sudo systemctl status wazuh-dashboard
    sudo ss -lntp

Never publish passwords, API credentials, private certificates or other secrets.
