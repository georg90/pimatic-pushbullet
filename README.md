pimatic-whatsapp
=======================

A plugin for sending Whatsapp notifications in pimatic.

Configuration
-------------
You can load the backend by editing your `config.json` to include:

    {
      "plugin": "whatsapp",
      "sender_phone": 0162XXXXXXXX,
      "password": "XXX",
      "cc": 49
    }

in the `plugins` section. For all configuration options see
[whatsapp-config-schema](whatsapp-config-schema.coffee)

Currently you can send Whatsapp notifications via action handler within rules.

Example:
--------
    if it is 08:00 send whatsapp message:"Good morning Dave!" to 0176XXXXXXXX

