# simple-persistence-test with NSCoder

The Keyed Archiver can store the following types as a root object: NSArray, NSDictionary, NSDate, NSNumber, NSString, and NSData.

In the Master-Detail app, we persisted an object graph: our root object was an NSArray, and it was full of NSDates.

It's also possible for our root object to be a more basic type, such as a string, number, or date, which would lead to a relatively simple object graph.

On the other hand, dictionaries, as a root object, are fairly interesting. It is easy to imagine a complex graph rooted in a dictionary, or maybe even a dictionary full of other dictionaries.
