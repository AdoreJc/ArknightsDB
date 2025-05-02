# Act6FunZoneMapAchieveInfoPlugin

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Act6FunZoneMapAchieveView _achieveView`

- `CanvasGroup _rootCanvasGroup`

- `Single _fadeDuration`

- `UISwitchTween m_switchTween`

- `Boolean m_hasInited`


## Methods

- `Void set_onClaimReward(Action`1)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_Render(ActivityCustomZoneMapViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapAchieveInfoPlugin : ActivityCustomZoneMapBasePlugin
{
	private Act6FunZoneMapAchieveView _achieveView; // 0x18
	private CanvasGroup _rootCanvasGroup; // 0x20
	private Single _fadeDuration; // 0x28
	private Action`1 <onClaimReward>k__BackingField; // 0x30
	private UISwitchTween m_switchTween; // 0x38
	private Boolean m_hasInited; // 0x40
	private static DelegateBridge __Hotfix0_get_onClaimReward; // 0x0
	private static DelegateBridge __Hotfix0_set_onClaimReward; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClaimReward { get; set; }

	// RVA: 0x31b42a8 VA: 0x75957cc2a8
	private Action`1 get_onClaimReward() { }
	// RVA: 0x31b4310 VA: 0x75957cc310
	public Void set_onClaimReward(Action`1 value) { }
	// RVA: 0x31b4394 VA: 0x75957cc394
	public override Void Render(ActivityCustomZoneMapViewModel model, Boolean isFastMode) { }
	// RVA: 0x31b44dc VA: 0x75957cc4dc
	private Void _InitIfNot() { }
	// RVA: 0x31b47b4 VA: 0x75957cc7b4
	public Void .ctor() { }
	// RVA: 0x31b4830 VA: 0x75957cc830
	private Void <>xLuaBaseProxy_Render(ActivityCustomZoneMapViewModel P0, Boolean P1) { }
}
```