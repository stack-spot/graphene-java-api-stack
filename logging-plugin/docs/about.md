## Overview
### How Logging Plugin works

This plugin adds a `logback-spring.xml` file to configure the **Logstash Logback Encoder** library, in the `{projectRoot}/src/main/resources` directory.

When you start the app, the logs output will automatically be in JSON format.

For more information about how to customize the logs output, see the [**Logstash Logback Encoder**](https://github.com/logfellow/logstash-logback-encoder).
