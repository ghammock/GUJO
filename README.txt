GUJO - Gary's Unsigned Java Objects
Author: Gary Hammock, PE

================================================================================
                                DESCRIPTION
================================================================================

This package seeks to implement the unsigned objects that were (in the author's
opinion) wrongly excluded from the Java language.  Unsigned bytes and words are
indispensable when trying to implement cryptographic functions.  Since Java
doesn't include these as primitives, the GUJO package attempts to provide this
functionality.

The objects are extensions of the java.lang.Number class and implements the
Comparable interface so the classes can be used in sortable lists.

As an extension of java.lang.Number, the class definitions must include a
serialVersionUID.  The generated UID for each class is as follows:

    Class UByte serialVersionUID = 1188939977661718941L;

================================================================================
                               IMPLEMENTATION
================================================================================

Unsigned bytes:
    UByte myByte = new UByte();
    
================================================================================
                                 FUTURE WORK
================================================================================

Implementing Unsigned Words/Integers