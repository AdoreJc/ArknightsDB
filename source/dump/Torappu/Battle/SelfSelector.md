# SelfSelector

**Namespace:** `Torappu.Battle`


## Properties

- `Int32 maxTargetNum`


## Methods

- `Int32 get_maxTargetNum()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SelfSelector : TargetSelector
{
	private static DelegateBridge __Hotfix0_get_maxTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x8
	private static DelegateBridge __Hotfix0_FindTiles; // 0x10
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected Int32 maxTargetNum { get; }

	// RVA: 0x1bba738 VA: 0x75941d2738
	protected Int32 get_maxTargetNum() { }
	// RVA: 0x1bba7a0 VA: 0x75941d27a0
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bba8d4 VA: 0x75941d28d4
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1bba954 VA: 0x75941d2954
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bbaaa4 VA: 0x75941d2aa4
	public Void .ctor() { }
}
```