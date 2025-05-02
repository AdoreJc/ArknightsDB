# Capture

**Namespace:** `System.Text.RegularExpressions`


## Fields

- `Int32 <Index>k__BackingField`

- `Int32 <Length>k__BackingField`

- `String <Text>k__BackingField`


## Properties

- `Int32 Index`

- `Int32 Length`

- `String Value`


## Methods

- `Int32 get_Index()`

- `Int32 get_Length()`

- `String get_Value()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class Capture
{
	private Int32 <Index>k__BackingField; // 0x10
	private Int32 <Length>k__BackingField; // 0x14
	private String <Text>k__BackingField; // 0x18

	public Int32 Index { get; set; }
	public Int32 Length { get; set; }
	internal String Text { get; set; }
	public String Value { get; }

	// RVA: 0x63754ec VA: 0x759898d4ec
	internal Void .ctor(String text, Int32 index, Int32 length) { }
	// RVA: 0x6375534 VA: 0x759898d534
	public Int32 get_Index() { }
	// RVA: 0x637553c VA: 0x759898d53c
	internal Void set_Index(Int32 value) { }
	// RVA: 0x6375544 VA: 0x759898d544
	public Int32 get_Length() { }
	// RVA: 0x637554c VA: 0x759898d54c
	internal Void set_Length(Int32 value) { }
	// RVA: 0x6375554 VA: 0x759898d554
	internal String get_Text() { }
	// RVA: 0x637555c VA: 0x759898d55c
	internal Void set_Text(String value) { }
	// RVA: 0x6375564 VA: 0x759898d564
	public String get_Value() { }
	// RVA: 0x6375588 VA: 0x759898d588
	public override String ToString() { }
	// RVA: 0x637558c VA: 0x759898d58c
	internal ReadOnlySpan`1 GetLeftSubstring() { }
	// RVA: 0x6375614 VA: 0x759898d614
	internal ReadOnlySpan`1 GetRightSubstring() { }
}
```