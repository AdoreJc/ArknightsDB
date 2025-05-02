# BlockedEdge

**Namespace:** `Torappu.Battle`


## Fields

- `Edge _data`

- `SpriteRenderer _sprite`


## Methods

- `Void SetData(Edge)`

- `Void _InitCollider()`

- `Void ClearGraphic()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedEdge : VisualObject, IHotfixable
{
	private Edge _data; // 0x18
	private SpriteRenderer _sprite; // 0x20
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0__InitCollider; // 0x8
	private static DelegateBridge __Hotfix0_ClearGraphic; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x4087738 VA: 0x759669f738
	public Void SetData(Edge data) { }
	// RVA: 0x40878d4 VA: 0x759669f8d4
	private Void _InitCollider() { }
	// RVA: 0x40879b0 VA: 0x759669f9b0
	public Void ClearGraphic() { }
	// RVA: 0x4087a78 VA: 0x759669fa78
	public Void .ctor() { }
}
```