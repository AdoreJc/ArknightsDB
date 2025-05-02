# XmlException

**Namespace:** `System.Xml`


## Fields

- `String res`

- `Int32 lineNumber`

- `Int32 linePosition`

- `String sourceUri`

- `String message`


## Properties

- `Int32 LineNumber`

- `Int32 LinePosition`


## Methods

- `Int32 get_LineNumber()`

- `Int32 get_LinePosition()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlException : SystemException
{
	private String res; // 0x90
	private String[] args; // 0x98
	private Int32 lineNumber; // 0xa0
	private Int32 linePosition; // 0xa4
	private String sourceUri; // 0xa8
	private String message; // 0xb0

	public Int32 LineNumber { get; }
	public Int32 LinePosition { get; }
	public override String Message { get; }
	internal String ResString { get; }

	// RVA: 0x62cd4c0 VA: 0x75988e54c0
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x62cdbc8 VA: 0x75988e5bc8
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x62cdd38 VA: 0x75988e5d38
	public Void .ctor() { }
	// RVA: 0x62cdd50 VA: 0x75988e5d50
	public Void .ctor(String message) { }
	// RVA: 0x62cdd64 VA: 0x75988e5d64
	public Void .ctor(String message, Exception innerException, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62cdd6c VA: 0x75988e5d6c
	internal Void .ctor(String message, Exception innerException, Int32 lineNumber, Int32 linePosition, String sourceUri) { }
	// RVA: 0x62c339c VA: 0x75988db39c
	internal Void .ctor(String res, String[] args) { }
	// RVA: 0x62c319c VA: 0x75988db19c
	internal Void .ctor(String res, String arg) { }
	// RVA: 0x62ce078 VA: 0x75988e6078
	internal Void .ctor(String res, String arg, String sourceUri) { }
	// RVA: 0x62c94b4 VA: 0x75988e14b4
	internal Void .ctor(String res, String arg, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62ce148 VA: 0x75988e6148
	internal Void .ctor(String res, String arg, Int32 lineNumber, Int32 linePosition, String sourceUri) { }
	// RVA: 0x62c95fc VA: 0x75988e15fc
	internal Void .ctor(String res, String[] args, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62ce228 VA: 0x75988e6228
	internal Void .ctor(String res, String[] args, Int32 lineNumber, Int32 linePosition, String sourceUri) { }
	// RVA: 0x62ce23c VA: 0x75988e623c
	internal Void .ctor(String res, String[] args, Exception innerException, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62cdfd0 VA: 0x75988e5fd0
	internal Void .ctor(String res, String[] args, Exception innerException, Int32 lineNumber, Int32 linePosition, String sourceUri) { }
	// RVA: 0x62cdec8 VA: 0x75988e5ec8
	private static String FormatUserMessage(String message, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62cd900 VA: 0x75988e5900
	private static String CreateMessage(String res, String[] args, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62c3340 VA: 0x75988db340
	internal static String[] BuildCharExceptionArgs(String data, Int32 invCharIndex) { }
	// RVA: 0x62ce244 VA: 0x75988e6244
	internal static String[] BuildCharExceptionArgs(Char[] data, Int32 length, Int32 invCharIndex) { }
	// RVA: 0x62c9b78 VA: 0x75988e1b78
	internal static String[] BuildCharExceptionArgs(Char invChar, Char nextChar) { }
	// RVA: 0x62ce298 VA: 0x75988e6298
	public Int32 get_LineNumber() { }
	// RVA: 0x62ce2a0 VA: 0x75988e62a0
	public Int32 get_LinePosition() { }
	// RVA: 0x62ce2a8 VA: 0x75988e62a8
	public override String get_Message() { }
	// RVA: 0x62ce2c0 VA: 0x75988e62c0
	internal String get_ResString() { }
}
```