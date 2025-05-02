# SortKey

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class SortKey
{
	private readonly String source; // 0x10
	private readonly Byte[] key; // 0x18
	private readonly CompareOptions options; // 0x20
	private readonly Int32 lcid; // 0x24

	public virtual String OriginalString { get; }
	public virtual Byte[] KeyData { get; }

	// RVA: 0x6064efc VA: 0x759867cefc
	public static Int32 Compare(SortKey sortkey1, SortKey sortkey2) { }
	// RVA: 0x6065070 VA: 0x759867d070
	internal Void .ctor(Int32 lcid, String source, CompareOptions opt) { }
	// RVA: 0x6065160 VA: 0x759867d160
	internal Void .ctor(Int32 lcid, String source, Byte[] buffer, CompareOptions opt, Int32 lv1Length, Int32 lv2Length, Int32 lv3Length, Int32 kanaSmallLength, Int32 markTypeLength, Int32 katakanaLength, Int32 kanaWidthLength, Int32 identLength) { }
	// RVA: 0x60651c0 VA: 0x759867d1c0
	internal Void .ctor(String localeName, String str, CompareOptions options, Byte[] keyData) { }
	// RVA: 0x6065208 VA: 0x759867d208
	public virtual String get_OriginalString() { }
	// RVA: 0x6065210 VA: 0x759867d210
	public virtual Byte[] get_KeyData() { }
	// RVA: 0x6065218 VA: 0x759867d218
	public override Boolean Equals(Object value) { }
	// RVA: 0x60652c8 VA: 0x759867d2c8
	public override Int32 GetHashCode() { }
	// RVA: 0x6065330 VA: 0x759867d330
	public override String ToString() { }
	// RVA: 0x6065598 VA: 0x759867d598
	internal Void .ctor() { }
}
```