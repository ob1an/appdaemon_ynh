Please make sure homeassistant is installed and you have generated a Long-Lived Access Token for AppDaemon.
Follow these instruction to get your token : https://appdaemon.readthedocs.io/en/latest/CONFIGURE.html#authentication

The config folder for AppDaemon is /home/yunohost.app/appdaemon
You can add there your automations and use the web admin to monitor.

You can also provide a git repository containing python apps. The structure should be :
- git repo
    - config
        - apps
            apps.yaml
            hello.py