# fiCenterVertical

**Namespace:** `FullInspector.LayoutToolkit`


## Fields

- `String _id`

- `fiLayout _centered`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.LayoutToolkit
public class fiCenterVertical : fiLayout
{
	private String _id; // 0x10
	private fiLayout _centered; // 0x18

	public override Single Height { get; }

	// RVA: 0x34d7344 VA: 0x7595aef344
	public Void .ctor(String id, fiLayout centered) { }
	// RVA: 0x34d7388 VA: 0x7595aef388
	public Void .ctor(fiLayout centered) { }
	// RVA: 0x34d73e8 VA: 0x7595aef3e8
	public override Boolean RespondsTo(String sectionId) { }
	// RVA: 0x34d743c VA: 0x7595aef43c
	public override Rect GetSectionRect(String sectionId, Rect initial) { }
	// RVA: 0x34d74fc VA: 0x7595aef4fc
	public override Single get_Height() { }
}
```