# MulleFoundation

This is the Foundation library written for [mulle-objc](//mulle-objc.github.io).

*MulleFoundation* is growing collection of libraries to form a complete and powerful Objective-C
class library for *mulle-objc*. An Objective-C Foundation traditionally contains no graphics code.

The *MulleFoundation* is designed as plug and play system. Optional library components can be 
left out with no bad side-effect. The concept of the *MulleFoundation* is to avoid actual 
linking into a shared library or executable as much as possible. This has the benefit that
an optimizing pass can determine, which parts need to be actually linked and which not.

Library                                                                                 | Description 
----------------------------------------------------------------------------------------|----------------------
[Foundation](//github.com/MulleFoundation/Foundation)                                   | The MulleFoundation plus compatibility code
[MulleFoundation](//github.com/MulleFoundation/MulleFoundation)                         | A convenient wrapper for the  MulleFoundation libraries
[MulleObjCCalendarFoundation](//github.com/MulleFoundation/MulleObjCCalendarFoundation ) | Calendar functionality with NSCalendar
[MulleObjCContainerFoundation](//github.com/MulleFoundation/MulleObjCContainerFoundation ) | Container classes like NSArray, NSSet, NSDictionary
[MulleObjCExpatFoundation](//github.com/MulleFoundation/MulleObjCExpatFoundation)       | XML parser based on MulleObjCStandardFoundation and libexpat 
[MulleObjCInetOSFoundation](//github.com/MulleFoundation/MulleObjCInetOSFoundation)     | OS specific extensions with NSURL 
[MulleObjCKVCFoundation](//github.com/MulleFoundation/MulleObjCKVCFoundation)           | Key-Value-Coding based on MulleObjCFoundation and mulle-objc
[MulleObjCMathFoundation](//github.com/MulleFoundation/MulleObjCMathFoundation)         | NSNumber refines that use the math library  
[MulleObjCOSFoundation](//github.com/MulleFoundation/MulleObjCOSFoundation)             | Platform-dependent classes and categories like NSTask, NSPipe 
[MulleObjCStandardFoundation](//github.com/MulleFoundation/MulleObjCStandardFoundation) | Platform-independent Objective-C classes, like NSString, NSArray, NSNotificationCenter
[MulleObjCValueFoundation ](//github.com/MulleFoundation/MulleObjCValueFoundation  )    | Value classes NSNumber, NSString, NSDate, NSData 
[objc-compat](//github.com/MulleFoundation/objc-compat)                                 | Glue for Objective-C code to support different runtimes

Library                                                                                | Description
---------------------------------------------------------------------------------------|----------------------
[Foundation-startup](//github.com/MulleFoundation/Foundation-startup)                  | Startup code for Foundation-based executables
[MulleFoundation-startup](//github.com/MulleFoundation/MulleFoundation-startup)        | Startup code for MulleFoundation-based executables

*MulleFoundation* is based on [MulleObjC](//MulleObjC.github.io) and [mulle-core](//mulle-core.github.io).
Some constituent libraries bring in outside dependencies such as *expat* for XML parsing.

## mulle-sde support

Library                                                                                | Description
---------------------------------------------------------------------------------------|----------------------
[foundation-developer](//github.com/MulleFoundation/foundation-developer)              | Objective C with mulle-sde and the MulleFoundation
[mulle-foundation-developer](//github.com/MulleFoundation/mulle-foundation-developer)  | MulleFoundation developer kit for mulle-sde 

## Install

See [foundation-developer](//github.com/MulleFoundation/foundation-developer) for install instructions.

