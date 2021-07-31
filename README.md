# ClassRuntime

## Role of ClassRuntime

The major role of the ClassRuntime is to receive requests for an object
instance, execute the request on the object instance, forward requests from the
managed object instances, persist instance states, schedule/manage instances.

## What is an object instance

An object instance consists of two parts: object state and implementation.

### Object state
Object state is simply a JSON data block for easy manipulation.

### Implementation
Implementation of an object is shared between objects of the same class. A class
can also include standard interfaces called traits.