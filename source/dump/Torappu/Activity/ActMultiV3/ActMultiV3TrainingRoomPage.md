# ActMultiV3TrainingRoomPage

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Params m_param`


## Properties

- `String actId`


## Methods

- `String get_actId()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TrainingRoomPage : StateEnginePage
{
	private Params m_param; // 0xe8
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x10
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String actId { get; }

	// RVA: 0x3152ec8 VA: 0x759576aec8
	public String get_actId() { }
	// RVA: 0x3152f40 VA: 0x759576af40
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x3152ff4 VA: 0x759576aff4
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x31530e4 VA: 0x759576b0e4
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x31531d4 VA: 0x759576b1d4
	public Void .ctor() { }
	// RVA: 0x3153244 VA: 0x759576b244
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x315324c VA: 0x759576b24c
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x3153258 VA: 0x759576b258
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```