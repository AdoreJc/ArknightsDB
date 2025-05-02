# CharEntityEncoderFallback

**Namespace:** `System.Xml`


## Fields

- `CharEntityEncoderFallbackBuffer fallbackBuffer`

- `Int32 endMarkPos`

- `Int32 curMarkPos`

- `Int32 startOffset`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class CharEntityEncoderFallback : EncoderFallback
{
	private CharEntityEncoderFallbackBuffer fallbackBuffer; // 0x10
	private Int32[] textContentMarks; // 0x18
	private Int32 endMarkPos; // 0x20
	private Int32 curMarkPos; // 0x24
	private Int32 startOffset; // 0x28

	public override Int32 MaxCharCount { get; }
	internal Int32 StartOffset { set; }

	// RVA: 0x6272768 VA: 0x759888a768
	internal Void .ctor() { }
	// RVA: 0x6272770 VA: 0x759888a770
	public override EncoderFallbackBuffer CreateFallbackBuffer() { }
	// RVA: 0x6272870 VA: 0x759888a870
	public override Int32 get_MaxCharCount() { }
	// RVA: 0x6272878 VA: 0x759888a878
	internal Void set_StartOffset(Int32 value) { }
	// RVA: 0x6272880 VA: 0x759888a880
	internal Void Reset(Int32[] textContentMarks, Int32 endMarkPos) { }
	// RVA: 0x62728ac VA: 0x759888a8ac
	internal Boolean CanReplaceAt(Int32 index) { }
}
```