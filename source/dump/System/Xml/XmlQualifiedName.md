# XmlQualifiedName

**Namespace:** `System.Xml`


## Fields

- `String name`

- `String ns`

- `Int32 hash`


## Properties

- `String Namespace`

- `String Name`

- `Boolean IsEmpty`


## Methods

- `String get_Namespace()`

- `String get_Name()`

- `Boolean get_IsEmpty()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlQualifiedName
{
	private static HashCodeOfStringDelegate hashCodeDelegate; // 0x0
	private String name; // 0x10
	private String ns; // 0x18
	private Int32 hash; // 0x20
	public static readonly XmlQualifiedName Empty; // 0x8

	public String Namespace { get; }
	public String Name { get; }
	public Boolean IsEmpty { get; }

	// RVA: 0x62cf03c VA: 0x75988e703c
	public Void .ctor() { }
	// RVA: 0x62cf130 VA: 0x75988e7130
	public Void .ctor(String name) { }
	// RVA: 0x62cf090 VA: 0x75988e7090
	public Void .ctor(String name, String ns) { }
	// RVA: 0x62cf190 VA: 0x75988e7190
	public String get_Namespace() { }
	// RVA: 0x62cf198 VA: 0x75988e7198
	public String get_Name() { }
	// RVA: 0x62cf1a0 VA: 0x75988e71a0
	public override Int32 GetHashCode() { }
	// RVA: 0x62cf3f8 VA: 0x75988e73f8
	public Boolean get_IsEmpty() { }
	// RVA: 0x62cf434 VA: 0x75988e7434
	public override String ToString() { }
	// RVA: 0x62cf4a4 VA: 0x75988e74a4
	public override Boolean Equals(Object other) { }
	// RVA: 0x62cf5f4 VA: 0x75988e75f4
	public static Boolean op_Equality(XmlQualifiedName a, XmlQualifiedName b) { }
	// RVA: 0x62cf584 VA: 0x75988e7584
	public static Boolean op_Inequality(XmlQualifiedName a, XmlQualifiedName b) { }
	// RVA: 0x62cf27c VA: 0x75988e727c
	private static HashCodeOfStringDelegate GetHashCodeDelegate() { }
	// RVA: 0x62cf65c VA: 0x75988e765c
	private static Boolean IsRandomizedHashingDisabled() { }
	// RVA: 0x62cf74c VA: 0x75988e774c
	private static Int32 GetHashCodeOfString(String s, Int32 length, Int64 additionalEntropy) { }
	// RVA: 0x62cf768 VA: 0x75988e7768
	internal Void Init(String name, String ns) { }
	// RVA: 0x62cf7a0 VA: 0x75988e77a0
	internal static XmlQualifiedName Parse(String s, IXmlNamespaceResolver nsmgr, out String prefix) { }
	// RVA: 0x62cf954 VA: 0x75988e7954
	private static Void .cctor() { }
}
```