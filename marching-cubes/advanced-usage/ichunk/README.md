# IChunk

IChunk is the interface you must implement to make your own uniquely implemented [chunk.md](../../terminology/chunk.md "mention").

IChunk has a property for a [base-chunk.md](base-chunk.md "mention"). The concrete class that implements IChunk must create it and provide the getter property. It must also dispose of it OnDestroy. This architecture may seem strange, as if direct inheritance might be more suitable, but it makes Networking easier, because it allows the [chunk.md](../../terminology/chunk.md "mention")to inherit from some other base class, such as one that's Networked. \
\
IChunk methods and properties belong to two different categories. Abstract that must be implemented in the concrete class, and with Default Implementations which can be overridden or extended but do not need to be.&#x20;
