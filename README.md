# akka-n2j

Akka-N2J wil be a pair of frameworks for Akka and Akka.NET that support routing of messages between actor systems running on both platforms. It will use Akka I/O (TCP most likely) for communications, with either JSON or protocol buffers for serialisation.

Important aspects of the design to be considered:
* Routing
* Serialisation / Deserialisation
  * Mapping message types between CLR and JVM types
  * Connection resillience
  * Interaction with clustering?
