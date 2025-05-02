# SpScaleAfterSkillCast

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `Int32 _spScale`

- `Int32 m_spScaleCnt`


## Methods

- `Void _ScaleSpCost()`

- `Void <>xLuaBaseProxy_AssignData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastSucceed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class SpScaleAfterSkillCast : Behaviour
{
	private Int32 _spScale; // 0x20
	private Int32 m_spScaleCnt; // 0x24
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastSucceed; // 0x8
	private static DelegateBridge __Hotfix0__ScaleSpCost; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d35484 VA: 0x759434d484
	public override Void AssignData(Blackboard blackboard) { }
	// RVA: 0x1d35544 VA: 0x759434d544
	public override Void OnCastSucceed() { }
	// RVA: 0x1d35620 VA: 0x759434d620
	private Void _ScaleSpCost() { }
	// RVA: 0x1d35764 VA: 0x759434d764
	public Void .ctor() { }
	// RVA: 0x1d357d4 VA: 0x759434d7d4
	private Void <>xLuaBaseProxy_AssignData(Blackboard P0) { }
	// RVA: 0x1d357dc VA: 0x759434d7dc
	private Void <>xLuaBaseProxy_OnCastSucceed() { }
}
```