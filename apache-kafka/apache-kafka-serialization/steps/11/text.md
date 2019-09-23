From our IDE, run the main method of PlainProcessor
From our IDE, run the main method of PlainProducer
The output on the console consumer for the uptimes topic should be similar to the following:
```
EW05-HV36   33
BO58-SB28   20
DV03-ZT93   46
...
We have said that, when producing data, there are two factors to think about; one is the delivery guarantee, and the other is the partitioning.

When consuming data, we have to think about the following four factors:

The number of consumers to run in parallel (in parallel threads and/or parallel processes)
The amount of data to consume at once (think in terms of memory)
The time to wait to receive messages (throughput and latency)
When to mark a message as processed (committing offset)
If enable.auto.commit is set to true (the default is true), the consumer automatically will commit the offsets in the next call to the poll method.

Note that the whole batch of records is committed; if something fails and the application crashes after processing only some messages, but not all of the batch, the events are not committed and they will be reprocessed by other consumer; this way to process data is called at least once processing. 