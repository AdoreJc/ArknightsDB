# CharEntityEncoderFallbackBuffer

**Namespace:** `System.Xml`


## Fields

- `CharEntityEncoderFallback parent`

- `String charEntity`

- `Int32 charEntityIndex`


## Methods

- `Int32 SurrogateCharToUtf32(Char, Char)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class CharEntityEncoderFallbackBuffer : EncoderFallbackBuffer
{
	private CharEntityEncoderFallback parent; // 0x30
	private String charEntity; // 0x38
	private Int32 charEntityIndex; // 0x40

	public override Int32 Remaining { get; }

	// RVA: 0x62727ec VA: 0x759888a7ec
	internal Void .ctor(CharEntityEncoderFallback parent) { }
	// RVA: 0x6272914 VA: 0x759888a914
	public override Boolean Fallback(Char charUnknown, Int32 index) { }
	// RVA: 0x6272b1c VA: 0x759888ab1c
	public override Boolean Fallback(Char charUnknownHigh, Char charUnknownLow, Int32 index) { }
	// RVA: 0x6272dc4 VA: 0x759888adc4
	public override Char GetNextChar() { }
	// RVA: 0x6272e1c VA: 0x759888ae1c
	public override Boolean MovePrevious() { }
	// RVA: 0x6272e3c VA: 0x759888ae3c
	public override Int32 get_Remaining() { }
	// RVA: 0x6272e70 VA: 0x759888ae70
	public override Void Reset() { }
	// RVA: 0x6272db4 VA: 0x759888adb4
	private Int32 SurrogateCharToUtf32(Char highSurrogate, Char lowSurrogate) { }
}
```