# EntityLocateRange

**Namespace:** `Torappu.Battle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EntityLocateRange : Range
{
	private Collider2D[] m_colliders; // 0x20
	private static DelegateBridge __Hotfix0_get_extendable; // 0x0
	private static DelegateBridge __Hotfix0_set_extendable; // 0x8
	private static DelegateBridge __Hotfix0_get_colliders; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_UpdateExtend; // 0x20
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x28
	private static DelegateBridge __Hotfix0_FindTiles; // 0x30
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x38
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override Boolean extendable { get; set; }
	protected Collider2D[] colliders { get; }

	// RVA: 0x1b905f4 VA: 0x75941a85f4
	public override Boolean get_extendable() { }
	// RVA: 0x1b90658 VA: 0x75941a8658
	public override Void set_extendable(Boolean value) { }
	// RVA: 0x1b906d0 VA: 0x75941a86d0
	protected Collider2D[] get_colliders() { }
	// RVA: 0x1b90768 VA: 0x75941a8768
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b907ec VA: 0x75941a87ec
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b9086c VA: 0x75941a886c
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b9091c VA: 0x75941a891c
	public override List`1 FindTiles(Vector2 mapPos, Func`2 validator) { }
	// RVA: 0x1b909ec VA: 0x75941a89ec
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b90d88 VA: 0x75941a8d88
	protected virtual Collider2D[] FetchColliders() { }
	// RVA: 0x1b90e08 VA: 0x75941a8e08
	public Void .ctor() { }
}
```