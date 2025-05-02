# DomainNameHelper

**Namespace:** `System`


## Dump
```C#
// Dll : System.dll
// Namespace : System
internal class DomainNameHelper
{


	// RVA: 0x6373188 VA: 0x759898b188
	internal static String ParseCanonicalName(String str, Int32 start, Int32 end, ref Boolean loopback) { }
	// RVA: 0x6373328 VA: 0x759898b328
	internal static Boolean IsValid(Char* name, UInt16 pos, ref Int32 returnedEnd, ref Boolean notCanonical, Boolean notImplicitFile) { }
	// RVA: 0x6373554 VA: 0x759898b554
	internal static Boolean IsValidByIri(Char* name, UInt16 pos, ref Int32 returnedEnd, ref Boolean notCanonical, Boolean notImplicitFile) { }
	// RVA: 0x637373c VA: 0x759898b73c
	internal static String IdnEquivalent(Char* hostname, Int32 start, Int32 end, ref Boolean allAscii, ref Boolean atLeastOneValidIdn) { }
	// RVA: 0x63739b8 VA: 0x759898b9b8
	internal static String IdnEquivalent(Char* hostname, Int32 start, Int32 end, ref Boolean allAscii, ref String bidiStrippedHost) { }
	// RVA: 0x6373c04 VA: 0x759898bc04
	private static Boolean IsIdnAce(String input, Int32 index) { }
	// RVA: 0x6373bb8 VA: 0x759898bbb8
	private static Boolean IsIdnAce(Char* input, Int32 index) { }
	// RVA: 0x6373c9c VA: 0x759898bc9c
	internal static String UnicodeEquivalent(String idnHost, Char* hostname, Int32 start, Int32 end) { }
	// RVA: 0x6373db8 VA: 0x759898bdb8
	internal static String UnicodeEquivalent(Char* hostname, Int32 start, Int32 end, ref Boolean allAscii, ref Boolean atLeastOneValidIdn) { }
	// RVA: 0x63734a4 VA: 0x759898b4a4
	private static Boolean IsASCIILetterOrDigit(Char character, ref Boolean notCanonical) { }
	// RVA: 0x63734f0 VA: 0x759898b4f0
	private static Boolean IsValidDomainLabelCharacter(Char character, ref Boolean notCanonical) { }
}
```