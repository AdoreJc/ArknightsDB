# BuffTriggerEventCounter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _notTriggerWhenNotCount`


## Methods

- `Void _ClearBuffs()`

- `Void GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnCountEvent(Event, Int32, Boolean)`

- `Void <>xLuaBaseProxy_OnCountReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffTriggerEventCounter : AbilityEventCounter, IBuffSource
{
	private List`1 _buffs; // 0x48
	private Boolean _notTriggerWhenNotCount; // 0x50
	private List`1 m_buffUid; // 0x58
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x0
	private static DelegateBridge __Hotfix0_OnCountEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnCountReset; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ec0df4 VA: 0x75944d8df4
	private Void _ClearBuffs() { }
	// RVA: 0x1ec0ee4 VA: 0x75944d8ee4
	protected override Void OnCountEvent(Event ev, Int32 triggerTimeCount, Boolean notCount) { }
	// RVA: 0x1ec1118 VA: 0x75944d9118
	protected override Void OnCountReset() { }
	// RVA: 0x1ec1188 VA: 0x75944d9188
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ec137c VA: 0x75944d937c
	public Void .ctor() { }
	// RVA: 0x1ec148c VA: 0x75944d948c
	private Void <>xLuaBaseProxy_OnCountEvent(Event P0, Int32 P1, Boolean P2) { }
	// RVA: 0x1ec1494 VA: 0x75944d9494
	private Void <>xLuaBaseProxy_OnCountReset() { }
}
```