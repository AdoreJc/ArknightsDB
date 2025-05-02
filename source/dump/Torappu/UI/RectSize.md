# RectSize

**Namespace:** `Torappu.UI`


## Fields

- `Vector2 _size`


## Properties

- `Single width`

- `Single height`


## Methods

- `Void SetValue(RectSize)`

- `Single get_width()`

- `Void set_width(Single)`

- `Single get_height()`

- `Void set_height(Single)`

- `Void ReadSize(RectTransform)`

- `Void WriteSize(RectTransform)`

- `Void Interpolate(RectSize, RectSize, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class RectSize
{
	private Vector2 _size; // 0x10

	public Single width { get; set; }
	public Single height { get; set; }

	// RVA: 0x21789e4 VA: 0x75947909e4
	public Void .ctor() { }
	// RVA: 0x2178a7c VA: 0x7594790a7c
	public Void .ctor(RectSize copy) { }
	// RVA: 0x217858c VA: 0x759479058c
	public Void SetValue(RectSize val) { }
	// RVA: 0x2178ab0 VA: 0x7594790ab0
	public Single get_width() { }
	// RVA: 0x2178ac0 VA: 0x7594790ac0
	public Void set_width(Single value) { }
	// RVA: 0x2178ab8 VA: 0x7594790ab8
	public Single get_height() { }
	// RVA: 0x2178ac8 VA: 0x7594790ac8
	public Void set_height(Single value) { }
	// RVA: 0x21784d4 VA: 0x75947904d4
	public Void ReadSize(RectTransform target) { }
	// RVA: 0x2178830 VA: 0x7594790830
	public Void WriteSize(RectTransform target) { }
	// RVA: 0x21787e4 VA: 0x75947907e4
	public Void Interpolate(RectSize from, RectSize to, Single percent) { }
}
```