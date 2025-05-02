# HandBookV2ColorBlockEdit

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Image _color`

- `ColoringBlockData m_colorBlockData`


## Properties

- `ColoringBlockData colorBlockData`


## Methods

- `ColoringBlockData get_colorBlockData()`

- `Void RemoveThisColor()`

- `Void RenderColorBlock(ColoringBlockData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2ColorBlockEdit : HandBookGroupCommonPosEdit
{
	private Image _color; // 0x28
	private ColoringBlockData m_colorBlockData; // 0x30

	public ColoringBlockData colorBlockData { get; }

	// RVA: 0x2ec5120 VA: 0x75954dd120
	public ColoringBlockData get_colorBlockData() { }
	// RVA: 0x2ec5128 VA: 0x75954dd128
	public override Void ApplyPos(Vector3 vect) { }
	// RVA: 0x2ec5144 VA: 0x75954dd144
	public Void RemoveThisColor() { }
	// RVA: 0x2ec3430 VA: 0x75954db430
	public Void RenderColorBlock(ColoringBlockData colorBlock) { }
	// RVA: 0x2ec52b8 VA: 0x75954dd2b8
	public Void .ctor() { }
}
```