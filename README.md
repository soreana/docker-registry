to install service :

        1. copy docker-registry.service to /etc/systemd/system/
        
        2. reload services : sudo systemctl daemon-reload
        
        3. activate the launch of the service at boot: sudo systemctl enable docker-registry
        
        4. start service : sudo systemctl start deluge
