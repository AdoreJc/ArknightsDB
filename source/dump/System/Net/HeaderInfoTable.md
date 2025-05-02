# HeaderInfoTable

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class HeaderInfoTable
{
	private static Hashtable HeaderHashTable; // 0x0
	private static HeaderInfo UnknownHeaderInfo; // 0x8
	private static HeaderParser SingleParser; // 0x10
	private static HeaderParser MultiParser; // 0x18

	internal HeaderInfo Item { get; }

	// RVA: 0x6430cdc VA: 0x7598a48cdc
	private static String[] ParseSingleValue(String value) { }
	// RVA: 0x6430d78 VA: 0x7598a48d78
	private static String[] ParseMultiValue(String value) { }
	// RVA: 0x6430f70 VA: 0x7598a48f70
	private static Void .cctor() { }
	// RVA: 0x642bec8 VA: 0x7598a43ec8
	internal HeaderInfo get_Item(String name) { }
	// RVA: 0x642e980 VA: 0x7598a46980
	public Void .ctor() { }
}
```