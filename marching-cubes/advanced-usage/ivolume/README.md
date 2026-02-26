# IVolume

IVolume is the interface you must implement to make your own uniquely implemented [volume.md](../../terminology/volume.md "mention").

IVolume has a property for a [base-volume.md](base-volume.md "mention"). The concrete class that implements IVolume must create it and provide the getter property. It must also dispose of it OnDestroy. This architecture may seem strange, as if direct inheritance might be more suitable, but it makes Networking easier, because it allows the [volume.md](../../terminology/volume.md "mention")to inherit from some other base class, such as one that's Networked. \
\
IVolume methods and properties belong to two different categories. Abstract that must be implemented in the concrete class, and with Default Implementations which can be overridden or extended but do not need to be.&#x20;
