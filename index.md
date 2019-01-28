# MulleFoundation

The MulleFoundation library collection is written for [mulle-objc](//mulle-objc.github.io).
It is based on [MulleObjC](//MulleObjC.github.io) and [mulle-core](//mulle-core.github.io).
Some constituent libraries may bring in outside depedencies such as *expat* for XML parsing.

This is growing collection of libraries to form a complete and powerful Objective-C
class library for *mulle-objc*. A Foundation traditionally contains no graphics code.

The MulleFoundation is designed as plug and play system. Optional library components can be 
left out with no bad side-effect. The concept of the MulleFoundation is to avoid actual 
linking into a shared library or executable as much as possible. This has the benefit that
an optimizing pass can determine, which parts to link and which not.

Library                                                                                 | Description 
----------------------------------------------------------------------------------------|----------------------
[Foundation](//github.com/MulleFoundation/Foundation)                                   | The Foundation library for mulle-objc
[MulleFoundation](//github.com/MulleFoundation/MulleFoundation)                         | Convenient wrapper for the MulleFoundation 
[MulleObjCExpatFoundation](//github.com/MulleFoundation/MulleObjCExpatFoundation)       | XML parser based on MulleObjCStandardFoundation and libexpat 
[MulleObjCKVCFoundation](//github.com/MulleFoundation/MulleObjCKVCFoundation)           | Key-Value-Coding based on MulleObjCFoundation and mulle-objc
[MulleObjCInetFoundation](//github.com/MulleFoundation/MulleObjCInetFoundation)         | Internet-related classes like NSHost and NSURL 
[MulleObjCStandardFoundation](//github.com/MulleFoundation/MulleObjCStandardFoundation) | Platform-independent Objective-C classes, like NSString, NSArray, NSNotificationCenter
[MulleObjCOSFoundation](//github.com/MulleFoundation/MulleObjCOSFoundation)             | Platform-dependent classes and categories like NSTask, NSPipe 
[objc-compat](//github.com/MulleFoundation/objc-compat)                                 | Glue for Objective-C code to support different runtimes

## mulle-sde support

Library                                                                                | Description
---------------------------------------------------------------------------------------|----------------------
[foundation-developer](//github.com/MulleFoundation/foundation-developer)              | Objective C with mulle-sde and the MulleFoundation
[mulle-foundation-developer](//github.com/MulleFoundation/mulle-foundation-developer)  | MulleFoundation developer kit for mulle-sde 

## Install

See [foundation-developer](//github.com/MulleFoundation/foundation-developer) for install instructions.

