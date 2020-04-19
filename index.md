# MulleFoundation

This is the Foundation library written for [mulle-objc](//mulle-objc.github.io).

*MulleFoundation* is collection of libraries to form a complete and powerful Objective-C
class library for *mulle-objc*. An Objective-C Foundation traditionally contains no graphics code.

The *MulleFoundation* is designed as plug and play system. Optional library components can be 
left out with no bad side-effect. The concept of the *MulleFoundation* is to avoid actual 
linking into a shared library or executable as much as possible. This has the benefit that
an optimizing pass can determine, which parts need to be actually linked and which not.

Library                                                                      | Description 
-----------------------------------------------------------------------------|----------------------
[Foundation](//MulleFoundation/Foundation)                                   | The MulleFoundation plus compatibility code
[MulleFoundation](//MulleFoundation/MulleFoundation)                         | A convenient wrapper for the  MulleFoundation libraries
[MulleObjCCalendarFoundation](//MulleFoundation/MulleObjCCalendarFoundation ) | Calendar functionality with NSCalendar
[MulleObjCContainerFoundation](//MulleFoundation/MulleObjCContainerFoundation ) | Container classes like NSArray, NSSet, NSDictionary
[MulleObjCExpatFoundation](//MulleFoundation/MulleObjCExpatFoundation)       | XML parser based on MulleObjCStandardFoundation and libexpat 
[MulleObjCInetOSFoundation](//MulleFoundation/MulleObjCInetOSFoundation)     | OS specific extensions with NSURL 
[MulleObjCKVCFoundation](//MulleFoundation/MulleObjCKVCFoundation)           | Key-Value-Coding based on MulleObjCFoundation and mulle-objc
[MulleObjCMathFoundation](//MulleFoundation/MulleObjCMathFoundation)         | NSNumber refines that use the math library  
[MulleObjCOSFoundation](//MulleFoundation/MulleObjCOSFoundation)             | Platform-dependent classes and categories like NSTask, NSPipe 
[MulleObjCStandardFoundation](//MulleFoundation/MulleObjCStandardFoundation) | Platform-independent Objective-C classes, like NSString, NSArray, NSNotificationCenter
[MulleObjCUnicodeFoundation ](//MulleFoundation/MulleObjCUnicodeFoundation  )| Unicode NSCharacterset and NSString methods
[MulleObjCValueFoundation ](//MulleFoundation/MulleObjCValueFoundation  )    | Value classes NSNumber, NSString, NSDate, NSData 
[objc-compat](//MulleFoundation/objc-compat)                                 | Glue for Objective-C code to support different runtimes

Library                                                                     | Description
----------------------------------------------------------------------------|----------------------
[Foundation-startup](//MulleFoundation/Foundation-startup)                  | Startup code for Foundation-based executables
[MulleFoundation-startup](//MulleFoundation/MulleFoundation-startup)        | Startup code for MulleFoundation-based executables

*MulleFoundation* is based on [MulleObjC](//MulleObjC.github.io) and [mulle-core](//mulle-core.github.io).
Some constituent libraries bring in outside dependencies such as *expat* for XML parsing.

## mulle-sde support

Library                                                                     | Description
----------------------------------------------------------------------------|----------------------
[foundation-developer](//MulleFoundation/foundation-developer)              | Objective C with mulle-sde and the MulleFoundation
[mulle-foundation-developer](//MulleFoundation/mulle-foundation-developer)  | MulleFoundation developer kit for mulle-sde 

## Install

See [foundation-developer](//MulleFoundation/foundation-developer) for install instructions.

