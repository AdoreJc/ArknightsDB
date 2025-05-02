# WarningException

**Namespace:** `System.ComponentModel`


## Properties

- `String HelpUrl`

- `String HelpTopic`


## Methods

- `String get_HelpUrl()`

- `String get_HelpTopic()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class WarningException : SystemException
{
	private readonly String <HelpUrl>k__BackingField; // 0x90
	private readonly String <HelpTopic>k__BackingField; // 0x98

	public String HelpUrl { get; }
	public String HelpTopic { get; }

	// RVA: 0x63db04c VA: 0x75989f304c
	public Void .ctor() { }
	// RVA: 0x63db0a0 VA: 0x75989f30a0
	public Void .ctor(String message) { }
	// RVA: 0x63db0ac VA: 0x75989f30ac
	public Void .ctor(String message, String helpUrl) { }
	// RVA: 0x63db0b4 VA: 0x75989f30b4
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x63db05c VA: 0x75989f305c
	public Void .ctor(String message, String helpUrl, String helpTopic) { }
	// RVA: 0x63db0bc VA: 0x75989f30bc
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x63db258 VA: 0x75989f3258
	public String get_HelpUrl() { }
	// RVA: 0x63db260 VA: 0x75989f3260
	public String get_HelpTopic() { }
	// RVA: 0x63db268 VA: 0x75989f3268
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
}
```