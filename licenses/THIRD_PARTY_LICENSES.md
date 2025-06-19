# Third-Party Software Licenses

This project incorporates several third-party software components. Below are the licenses and attributions for each:

## ESP-IDF Framework
**License**: Apache License 2.0  
**Copyright**: Espressif Systems (Shanghai) Co. Ltd.  
**Source**: https://github.com/espressif/esp-idf  
**Usage**: Core ESP32 development framework, WiFi/BLE stack, HTTP server, OTA functionality

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
```

## cJSON Library
**License**: MIT License  
**Copyright**: 2009-2017 Dave Gamble and cJSON contributors  
**Source**: https://github.com/DaveGamble/cJSON  
**Usage**: JSON parsing for WiFi credentials and device information

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

## FreeRTOS
**License**: MIT License  
**Copyright**: Amazon.com, Inc. or its affiliates  
**Source**: https://www.freertos.org/  
**Usage**: Real-time operating system kernel (included with ESP-IDF)

## Unity Test Framework
**License**: MIT License  
**Copyright**: 2007-2017 Mike Karlesky, Mark VanderVoord, Greg Williams  
**Source**: https://github.com/ThrowTheSwitch/Unity  
**Usage**: Unit testing framework (development/testing only)

## Bluetooth Stack Components
**License**: Various (Apache 2.0, BSD)  
**Copyright**: Espressif Systems, various contributors  
**Usage**: Bluetooth Low Energy functionality

---

## License Compliance Notes

1. **Apache 2.0 Components**: No modifications made to ESP-IDF core components
2. **MIT Components**: Original copyright notices preserved
3. **Attribution**: All required notices included in documentation
4. **Source Code**: Available upon request where required by license terms

## Open Source Dependencies

For a complete list of open source dependencies and their licenses, run:
```bash
idf.py show-property COMPONENT_REQUIRES_COMMON
```

---
**Last Updated**: 11/06/2025 
</br>
**Project Version**: 1.0.0