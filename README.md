# akka-n2j

Akka-N2J wil be a frameworks for Akka and Akka.NET that support routing of messages between actor systems running on both platforms.

Important aspects of the design to be considered:
* Routing
* Serialisation / Deserialisation
  * Mapping message types between CLR and JVM types
  * Connection resillience
  * Interaction with clustering?
