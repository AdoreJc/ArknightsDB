# GBuffOverrideBlackboard

**Namespace:** `Torappu.Battle.Roguelike.Internal`


## Methods

- `Void <>xLuaBaseProxy_LatePreprocess(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Internal
public class GBuffOverrideBlackboard : BasicRelic
{
	private static DelegateBridge __Hotfix0_get_relicType; // 0x0
	private static DelegateBridge __Hotfix0_LatePreprocess; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RelicType relicType { get; }

	// RVA: 0x1d54f8c VA: 0x759436cf8c
	public override RelicType get_relicType() { }
	// RVA: 0x1d54ff4 VA: 0x759436cff4
	public override Void LatePreprocess(ref RelicInOut inOut) { }
	// RVA: 0x1d5529c VA: 0x759436d29c
	public Void .ctor() { }
	// RVA: 0x1d5530c VA: 0x759436d30c
	private Void <>xLuaBaseProxy_LatePreprocess(ref RelicInOut P0) { }
}
```