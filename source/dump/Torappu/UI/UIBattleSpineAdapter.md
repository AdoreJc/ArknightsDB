# UIBattleSpineAdapter

**Namespace:** `Torappu.UI`


## Fields

- `BattleSpineInput m_cachedInput`


## Methods

- `Void UpdateParam(BattleSpineInput)`

- `TRS <>xLuaBaseProxy_GetTransformParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBattleSpineAdapter : Adapter, IHotfixable
{
	private BattleSpineInput m_cachedInput; // 0x48
	private static DelegateBridge __Hotfix0_UpdateParam; // 0x0
	private static DelegateBridge __Hotfix0_GetSpineID; // 0x8
	private static DelegateBridge __Hotfix0_GetTransformParam; // 0x10
	private static DelegateBridge __Hotfix0_GetAnimParam; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x21f0654 VA: 0x7594808654
	public Void UpdateParam(BattleSpineInput input) { }
	// RVA: 0x21f070c VA: 0x759480870c
	public override SpineID GetSpineID() { }
	// RVA: 0x21f0794 VA: 0x7594808794
	public override TRS GetTransformParam() { }
	// RVA: 0x21f085c VA: 0x759480885c
	public override SpineAnimParam GetAnimParam() { }
	// RVA: 0x21f094c VA: 0x759480894c
	public Void .ctor() { }
	// RVA: 0x21f09dc VA: 0x75948089dc
	private TRS <>xLuaBaseProxy_GetTransformParam() { }
}
```