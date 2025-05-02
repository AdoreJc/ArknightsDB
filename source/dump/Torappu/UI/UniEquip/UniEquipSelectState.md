# UniEquipSelectState

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UniEquipSelectStateBean _stateBean`

- `UniEquipSelectHolder _holder`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnSelectUniEquip(String)`

- `Void OnCheckDetail(String)`

- `Void OnUnlockUniEquip(String)`

- `Void OnChangeUniEquip(String)`

- `Void OnLevelUpUniEquip(String)`

- `Void _TriggerAVGSignal()`

- `Void <RegisterToDataListener>b__13_0(IStateBean)`

- `Void <RegisterToDataListener>b__13_1(IStateBean)`

- `Void <RegisterToDataListener>b__13_2(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipSelectState : State
{
	private UniEquipSelectStateBean _stateBean; // 0x50
	private UniEquipSelectHolder _holder; // 0x58
	private Boolean m_isInited; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectUniEquip; // 0x8
	private static DelegateBridge __Hotfix0_OnCheckDetail; // 0x10
	private static DelegateBridge __Hotfix0_OnUnlockUniEquip; // 0x18
	private static DelegateBridge __Hotfix0_OnChangeUniEquip; // 0x20
	private static DelegateBridge __Hotfix0_OnLevelUpUniEquip; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0__TriggerAVGSignal; // 0x40
	private static DelegateBridge __Hotfix0_OnResume; // 0x48
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x22fa03c VA: 0x759491203c
	private Void _InitIfNot() { }
	// RVA: 0x22fa14c VA: 0x759491214c
	public Void OnSelectUniEquip(String equipId) { }
	// RVA: 0x22fa1d8 VA: 0x75949121d8
	public Void OnCheckDetail(String equipId) { }
	// RVA: 0x22fa318 VA: 0x7594912318
	public Void OnUnlockUniEquip(String equipId) { }
	// RVA: 0x22fa458 VA: 0x7594912458
	public Void OnChangeUniEquip(String equipId) { }
	// RVA: 0x22fa704 VA: 0x7594912704
	public Void OnLevelUpUniEquip(String equipId) { }
	// RVA: 0x22fa8a8 VA: 0x75949128a8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22fa910 VA: 0x7594912910
	protected override Void OnEnter() { }
	// RVA: 0x22faa90 VA: 0x7594912a90
	private Void _TriggerAVGSignal() { }
	// RVA: 0x22faaf4 VA: 0x7594912af4
	protected override Void OnResume() { }
	// RVA: 0x22fac00 VA: 0x7594912c00
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x22fae64 VA: 0x7594912e64
	public Void .ctor() { }
	// RVA: 0x22faed4 VA: 0x7594912ed4
	private Void <RegisterToDataListener>b__13_0(IStateBean stateBean) { }
	// RVA: 0x22fb058 VA: 0x7594913058
	private Void <RegisterToDataListener>b__13_1(IStateBean stateBean) { }
	// RVA: 0x22fb12c VA: 0x759491312c
	private Void <RegisterToDataListener>b__13_2(IStateBean stateBean) { }
	// RVA: 0x22fb284 VA: 0x7594913284
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22fb28c VA: 0x759491328c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x22fb294 VA: 0x7594913294
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```