# RectPosition

**Namespace:** `Torappu.UI`


## Fields

- `Vector2 _position`


## Properties

- `Single x`

- `Single y`


## Methods

- `Void SetValue(RectPosition)`

- `Single get_x()`

- `Void set_x(Single)`

- `Single get_y()`

- `Void set_y(Single)`

- `Void ReadPosition(RectTransform)`

- `Void WritePosition(RectTransform)`

- `Void Interpolate(RectPosition, RectPosition, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class RectPosition
{
	private Vector2 _position; // 0x10

	public Single x { get; set; }
	public Single y { get; set; }

	// RVA: 0x21783ac VA: 0x75947903ac
	public Void .ctor() { }
	// RVA: 0x2178a00 VA: 0x7594790a00
	public Void .ctor(RectPosition copy) { }
	// RVA: 0x2177f74 VA: 0x759478ff74
	public Void SetValue(RectPosition val) { }
	// RVA: 0x2178a34 VA: 0x7594790a34
	public Single get_x() { }
	// RVA: 0x2178a44 VA: 0x7594790a44
	public Void set_x(Single value) { }
	// RVA: 0x2178a3c VA: 0x7594790a3c
	public Single get_y() { }
	// RVA: 0x2178a4c VA: 0x7594790a4c
	public Void set_y(Single value) { }
	// RVA: 0x2178a54 VA: 0x7594790a54
	public Void ReadPosition(RectTransform target) { }
	// RVA: 0x2177ec4 VA: 0x759478fec4
	public Void WritePosition(RectTransform target) { }
	// RVA: 0x21781cc VA: 0x75947901cc
	public Void Interpolate(RectPosition from, RectPosition to, Single percent) { }
}
```