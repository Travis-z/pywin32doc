# PyIInitializeWithStream

## PyIInitializeWithStream Object

Interface that initializes a handler capable of reading properties from a stream

#### Methods


  - [Initialize](PyIInitializeWithStream.md#pyiinitializewithstreaminitialize)

    Initializes a property handler with a stream&nbsp;

## [PyIInitializeWithStream](#pyiinitializewithstream).Initialize

 __Initialize( *Stream*  *, Mode* __ )
Initializes a property handler with a stream

#### Parameters


  -  *Stream* :[PyIStream](#pyistream)

    Stream containing the contents from which to extract properties

  -  *Mode* : int

    Indicates if stream is writable, STGM_READ or STGM_READWRITE