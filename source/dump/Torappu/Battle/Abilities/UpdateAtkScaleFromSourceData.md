# UpdateAtkScaleFromSourceData

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _overwrite`


## Methods

- `Void _SetTalent(Character, AtkScaleConfig)`

- `Void _SetTrait(Character, AtkScaleConfig)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UpdateAtkScaleFromSourceData : Behaviour
{
	private List`1 _atkScaleConfig; // 0x20
	private Boolean _overwrite; // 0x28
	private ListDict`2 m_atkScaleConfigDic; // 0x30
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0__SetTalent; // 0x10
	private static DelegateBridge __Hotfix0__SetTrait; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ed3fcc VA: 0x75944ebfcc
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed4688 VA: 0x75944ec688
	public override Void OnCastStart() { }
	// RVA: 0x1ed4440 VA: 0x75944ec440
	private Void _SetTalent(Character character, AtkScaleConfig config) { }
	// RVA: 0x1ed42e4 VA: 0x75944ec2e4
	private Void _SetTrait(Character character, AtkScaleConfig config) { }
	// RVA: 0x1ed499c VA: 0x75944ec99c
	public Void .ctor() { }
	// RVA: 0x1ed4a60 VA: 0x75944eca60
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed4a68 VA: 0x75944eca68
	private Void <>xLuaBaseProxy_OnCastStart() { }
}
```