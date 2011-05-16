# RabbitMQ Misultin Plugin

This is a plugin for misultin to be used inside the RabbitMQ broker. It is similar 
to the plugin Alvaro Videla has: https://github.com/videlalvaro/misultin_wrapper 

The difference is that this plugin uses rebar and doesn't require a checkout of the rabbitmq-public-umbrella.

To use this plugin:

    git clone git://github.com/jbrisbin/rabbitmq-misultin.git
    cd rabbmitmq-misultin
    make package
    cp deps/misultin.ez $RABBITMQ_HOME/plugins/

Don't worry about the rabbitmq-misultin.ez plugin file in "dist". That's just there 
to force rebar to handle dependencies.
