# Squid3 Docker Image

``COPY`` configuration files into ``/etc/squid3`` or just mount a volume::

    docker run -v <local_dir>:/etc/squid3:ro squid3

The default configuration file writes logs to::

    /var/log/squid3/
    
And listens on ``localhost:3128``.
