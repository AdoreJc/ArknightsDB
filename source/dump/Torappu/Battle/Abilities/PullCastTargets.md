# PullCastTargets

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _pullSourceOffset`

- `Single _pullDuration`

- `Int32 m_pullForceLevel`


## Methods

- `Int32 _RegisterPullRemainingTime()`

- `IEnumerator _DoLink(Enemy)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PullCastTargets : Behaviour
{
	private Single _pullSourceOffset; // 0x20
	private Single _pullDuration; // 0x24
	private List`1 m_pullRemainingTimeList; // 0x28
	private Int32 m_pullForceLevel; // 0x30
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__RegisterPullRemainingTime; // 0x20
	private static DelegateBridge __Hotfix0__DoLink; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1ed1aec VA: 0x75944e9aec
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed1ba8 VA: 0x75944e9ba8
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ed1c54 VA: 0x75944e9c54
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ed1e84 VA: 0x75944e9e84
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ed2050 VA: 0x75944ea050
	private Int32 _RegisterPullRemainingTime() { }
	// RVA: 0x1ed1db4 VA: 0x75944e9db4
	private IEnumerator _DoLink(Enemy target) { }
	// RVA: 0x1ed21b0 VA: 0x75944ea1b0
	public Void .ctor() { }
	// RVA: 0x1ed227c VA: 0x75944ea27c
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed2284 VA: 0x75944ea284
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ed228c VA: 0x75944ea28c
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ed2294 VA: 0x75944ea294
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```