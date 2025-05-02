# fiLayoutHeight

**Namespace:** `FullInspector.LayoutToolkit`


## Fields

- `String _id`

- `Single _height`


## Methods

- `Void SetHeight(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.LayoutToolkit
public class fiLayoutHeight : fiLayout
{
	private String _id; // 0x10
	private Single _height; // 0x18

	public override Single Height { get; }

	// RVA: 0x34d70a4 VA: 0x7595aef0a4
	public Void .ctor(Single height) { }
	// RVA: 0x34d7118 VA: 0x7595aef118
	public Void .ctor(String sectionId, Single height) { }
	// RVA: 0x34d715c VA: 0x7595aef15c
	public override Boolean RespondsTo(String sectionId) { }
	// RVA: 0x34d7168 VA: 0x7595aef168
	public override Rect GetSectionRect(String sectionId, Rect initial) { }
	// RVA: 0x34d719c VA: 0x7595aef19c
	public Void SetHeight(Single height) { }
	// RVA: 0x34d71a4 VA: 0x7595aef1a4
	public override Single get_Height() { }
}
```