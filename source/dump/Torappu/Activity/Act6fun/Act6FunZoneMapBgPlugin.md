# Act6FunZoneMapBgPlugin

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `GameObject _objNormalBg`

- `GameObject _objBonusBg`

- `EventTrigger _bgEventTrigger`

- `Boolean m_hasInited`

- `Action <onBgClick>k__BackingField`


## Properties

- `Action onBgClick`


## Methods

- `Action get_onBgClick()`

- `Void set_onBgClick(Action)`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__9_0(BaseEventData)`

- `Void <>xLuaBaseProxy_Render(ActivityCustomZoneMapViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapBgPlugin : ActivityCustomZoneMapBasePlugin
{
	private GameObject _objNormalBg; // 0x18
	private GameObject _objBonusBg; // 0x20
	private EventTrigger _bgEventTrigger; // 0x28
	private Boolean m_hasInited; // 0x30
	private Action <onBgClick>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onBgClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBgClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onBgClick { get; set; }

	// RVA: 0x31b483c VA: 0x75957cc83c
	private Action get_onBgClick() { }
	// RVA: 0x31b48a4 VA: 0x75957cc8a4
	public Void set_onBgClick(Action value) { }
	// RVA: 0x31b4928 VA: 0x75957cc928
	public override Void Render(ActivityCustomZoneMapViewModel model, Boolean isFastMode) { }
	// RVA: 0x31b4a58 VA: 0x75957cca58
	private Void _InitIfNot() { }
	// RVA: 0x31b4c20 VA: 0x75957ccc20
	public Void .ctor() { }
	// RVA: 0x31b4c90 VA: 0x75957ccc90
	private Void <_InitIfNot>b__9_0(BaseEventData data) { }
	// RVA: 0x31b4cd0 VA: 0x75957cccd0
	private Void <>xLuaBaseProxy_Render(ActivityCustomZoneMapViewModel P0, Boolean P1) { }
}
```