# Subtitle

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `Int32 index`

- `String text`

- `Int32 timeStartMs`

- `Int32 timeEndMs`


## Methods

- `Boolean IsBefore(Single)`

- `Boolean IsTime(Single)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class Subtitle
{
	public Int32 index; // 0x10
	public String text; // 0x18
	public Int32 timeStartMs; // 0x20
	public Int32 timeEndMs; // 0x24


	// RVA: 0x6692e6c VA: 0x7598caae6c
	public Boolean IsBefore(Single time) { }
	// RVA: 0x66919cc VA: 0x7598ca99cc
	public Boolean IsTime(Single time) { }
	// RVA: 0x6692e98 VA: 0x7598caae98
	public Void .ctor() { }
}
```