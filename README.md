# LogChainify - The Seamless Log Correlation Toolbox in event driven architecture
LogChainify is an open-source package designed to provide a seamless and efficient solution for managing logs with 
causation IDs and correlation IDs. With LogChainify, you can easily trace and correlate logs across different components
and systems, gaining valuable insights into the flow and relationships of your distributed applications.

# Events in event driven architecture
In Event-Driven Architecture, Event ID, Correlation ID, and Causation ID play a crucial role in tracking and
correlating events across distributed systems.

- **Event ID**: An Event ID is a unique identifier assigned to each event that occurs within the system. 
It serves as a means to uniquely identify and reference an event, enabling systems to keep track of the events
that have taken place.

- **Correlation ID**: A Correlation ID is a value assigned to an event and is propagated through the system as the event
triggers various components or services. It allows for the correlation of related events that are part of the same 
logical flow or transaction, even when they are processed by different services. Correlation IDs enable end-to-end 
tracing and facilitate the understanding of the relationships between events.

- **Causation ID**: A Causation ID represents the cause-and-effect relationship between events. It is used to track
the chain of events that led to the occurrence of a particular event. By associating events with causation IDs,
systems can easily understand the sequence of events that led to a specific outcome or state, aiding in debugging,
troubleshooting, and root cause analysis.

These identification mechanisms, namely Event ID, Correlation ID, and Causation ID, provide the foundation for
event-driven systems to achieve traceability, maintain data integrity, and enable effective monitoring and analysis of 
event flows across distributed architectures.

# Problem
1. Log Data Integration: Integrating log data from diverse sources and formats, ensuring compatibility, 
and extracting relevant information for correlation and visualization. Maybe we should use some log aggregation tools
and create plugins for them.

1. Identifying Log Relationships: Establishing connections and relationships between logs based on Correlation ID and
Causation ID, considering the distributed nature of the system.

1. Data Volume and Performance: Handling high volumes of log data efficiently, ensuring smooth processing, 
and minimizing latency for real-time visualization.

1. Visualization: Visualizing log data in a way that is easy to understand and interpret, enabling users to
identify patterns and trends, and gain valuable insights into the system.


# Contribution
Join us and help building LogChainify. Let's solve the problem of visualisation of correlated events in 
event-driven architecture.

To start contributing or discussing just open GH issue in this repository and write your proposition or question.
