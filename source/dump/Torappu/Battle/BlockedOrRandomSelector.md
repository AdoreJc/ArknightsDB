# BlockedOrRandomSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Character m_character`


## Methods

- `Boolean _ValidateWithTargetFree(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedOrRandomSelector : RandomSelector
{
	private Character m_character; // 0xc0


	// RVA: 0x1ba41b0 VA: 0x75941bc1b0
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ba4288 VA: 0x75941bc288
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba4924 VA: 0x75941bc924
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba4964 VA: 0x75941bc964
	private Boolean _ValidateWithTargetFree(Entity target) { }
	// RVA: 0x1ba4a18 VA: 0x75941bca18
	public Void .ctor() { }
}
```