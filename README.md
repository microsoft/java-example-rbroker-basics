DeployR Java RBroker Framework Basics
=====================================

The following tutorial demonstrates the basic programming model and capabilities of the RBroker Framework. Each example makes concrete the ideas introduced by the [Quick Start Tutorial](https://msdn.microsoft.com/en-us/microsoft-r/deployr-rbroker-framework) for developers using the framework. 

- [About: RBroker Framework](#about-rbroker-framework)
- [Tutorial: Discrete Task Broker](#tutorial-discrete-task-broker)
- [Tutorial: Pooled Task Broker](#tutorial-pooled-task-broker)
- [Tutorial: Background Task Broker](#tutorial-background-task-broker)
- [Tutorial: Running The Examples](#tutorial-running-the-examples)
- [License](#license)

### About: RBroker Framework

The RBroker Framework is the simplest way to integrate DeployR-enabled analytics Web services inside any [Java, JavaScript or .NET](https://msdn.microsoft.com/en-us/microsoft-r/deployr-rbroker-framework) application.

Further information detailing core features of the framework can be found here:

1. [Building Blocks: RBroker, RTask, RTaskResult](https://msdn.microsoft.com/en-us/microsoft-r/deployr-rbroker-framework#basic-building-blocks)
2. [Runtime Options: Discrete, Pooled, Background](https://msdn.microsoft.com/en-us/microsoft-r/deployr-rbroker-framework#rbroker-runtime-options)
3. [Client Application Simulations](https://msdn.microsoft.com/en-us/microsoft-r/deployr-rbroker-framework#client-application-simulations)
4. [Client Application Profiling](https://msdn.microsoft.com/en-us/microsoft-r/deployr-rbroker-framework#client-application-profiling)



### Tutorial: Discrete Task Broker

The Discrete Task Broker runtime is well-suited to all forms of RBroker prototyping as well as for public facing production deployments. If you anticipate anonymous users making use of DeployR analytics Web services, then this runtime is for you.

The examples provided in this tutorial demonstrate a wide range of framework capabilities, including:

1. Blocking for Task results. 
2. Polling for Task results. 
3. Asynchronous callbacks for Task results.
4. Built-in support for Task execution runtime profiling.
5. Built-in support for client application simulations.

### Tutorial: Pooled Task Broker

The Pooled Task Broker runtime is well suited to production deployments where consistent, high-performance runtime semantics are required. If you anticipate a high-volume Task workload, then this runtime is for you. Remember to size the pool in line with expected workload.

The example provided in this tutorial demonstrates a more complete client application simulation that provides a good model for how any client developer might develop a high-performance, **real-time scoring engine** solution using the RBroker Framework.

### Tutorial: Background Task Broker

The Background Task Broker runtime  is well-suited to deployments that require periodic, scheduled or batch processing.

The example provided in this tutorial demonstrates the basic mechanisms when working with and retrieving results from potentially long-running Tasks executed in the background.

### Tutorial: Running The Examples

Use the [DeployR CLI](https://github.com/microsoft/deployr-cli) to download and run the java-example-rbroker-basics examples.

## License ##

Copyright (C) 2010-2016, Microsoft Corporation

This program is licensed to you under the terms of Version 2.0 of the
Apache License. This program is distributed WITHOUT
ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING THOSE OF NON-INFRINGEMENT,
MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. Please refer to the
Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0) for more 
details. 