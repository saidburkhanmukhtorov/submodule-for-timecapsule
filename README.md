feat(memory, timeline): Weaving Memories and History with gRPC and Kafka

In the heart of our TimeCapsule, the Memory and Timeline services have awakened, ready to capture life's precious moments and the grand tapestry of history.

We begin by imbuing them with the power of gRPC, enabling swift and efficient communication for retrieving and managing individual memories, media, custom events, and historical records. The proto files now resonate with the echoes of new RPC methods: `GetById`, `Delete`, and `GetAll`, ready to respond to the calls of curious minds.

But memories and history are not static; they flow and evolve like the rivers of time. To embrace this dynamism, we've woven in the magic of Kafka. Go struct models, meticulously crafted for "Create," "Update," and "Patch" operations, now stand ready to carry the whispers of change through the asynchronous streams of Kafka.

These models, adorned with `time.Time` for dates and adorned with JSON/BSON tags, ensure that every detail is preserved, ready to be recalled with crystal clarity. And for those subtle shifts in time, the `Patch...Model` structs, with their pointers and `omitempty` grace, allow for precise and elegant modifications.

With gRPC as our messenger and Kafka as our chronicler, the Memory and Timeline services are now poised to weave a rich and ever-evolving tapestry of life's journey.
