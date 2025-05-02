# VoicelangSettingState

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `VoicelangSettingStateBean _stateBean`

- `VoicelangCardGridGroupBinder _cardGroupBinder`

- `VoicelangPowerGridGroup _powerGroupBinder`

- `VoicelangSettingConfirmBinder _settingConfirmBinder`

- `VoicelangTypeSelectGroupBinder _typeSelectGroupBinder`

- `UnityEvent onReturnPageEvent`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _TryToConsumeCharsWithIgnoreType()`

- `Void OnPowerSelect(Boolean, String)`

- `Void OnTypeTabSelect(Boolean, VoiceLangGroupType)`

- `Void OnCardSelect(String)`

- `Void OnBatchSelect()`

- `Void OnSwitchLangTypeConfirm()`

- `Void OnSwitchLangTypeCancel()`

- `Void OnSwitchLangType(VoiceLangType)`

- `Void OnReturn()`

- `Void OnRoute(UIRouteTarget, Boolean)`

- `Void <_OnInitTopMenu>b__11_0()`

- `Void <OnSwitchLangTypeConfirm>b__17_0(SetCharVoiceLanResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangSettingState : State
{
	private VoicelangSettingStateBean _stateBean; // 0x50
	private VoicelangCardGridGroupBinder _cardGroupBinder; // 0x58
	private VoicelangPowerGridGroup _powerGroupBinder; // 0x60
	private VoicelangSettingConfirmBinder _settingConfirmBinder; // 0x68
	private VoicelangTypeSelectGroupBinder _typeSelectGroupBinder; // 0x70
	private UnityEvent onReturnPageEvent; // 0x78
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x18
	private static DelegateBridge __Hotfix0__TryToConsumeCharsWithIgnoreType; // 0x20
	private static DelegateBridge __Hotfix0_OnPowerSelect; // 0x28
	private static DelegateBridge __Hotfix0_OnTypeTabSelect; // 0x30
	private static DelegateBridge __Hotfix0_OnCardSelect; // 0x38
	private static DelegateBridge __Hotfix0_OnBatchSelect; // 0x40
	private static DelegateBridge __Hotfix0_OnSwitchLangTypeConfirm; // 0x48
	private static DelegateBridge __Hotfix0_OnSwitchLangTypeCancel; // 0x50
	private static DelegateBridge __Hotfix0_OnSwitchLangType; // 0x58
	private static DelegateBridge __Hotfix0_OnReturn; // 0x60
	private static DelegateBridge __Hotfix0_OnRoute; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2295eb0 VA: 0x75948adeb0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2295f18 VA: 0x75948adf18
	protected override Void OnEnter() { }
	// RVA: 0x2295fa4 VA: 0x75948adfa4
	private Void _InitIfNot() { }
	// RVA: 0x2296e3c VA: 0x75948aee3c
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2296144 VA: 0x75948ae144
	private Void _TryToConsumeCharsWithIgnoreType() { }
	// RVA: 0x2296fdc VA: 0x75948aefdc
	public Void OnPowerSelect(Boolean isAll, String powerId) { }
	// RVA: 0x229720c VA: 0x75948af20c
	public Void OnTypeTabSelect(Boolean isAll, VoiceLangGroupType type) { }
	// RVA: 0x229745c VA: 0x75948af45c
	public Void OnCardSelect(String wordKey) { }
	// RVA: 0x229771c VA: 0x75948af71c
	public Void OnBatchSelect() { }
	// RVA: 0x22978c0 VA: 0x75948af8c0
	public Void OnSwitchLangTypeConfirm() { }
	// RVA: 0x2297ff4 VA: 0x75948afff4
	public Void OnSwitchLangTypeCancel() { }
	// RVA: 0x2298164 VA: 0x75948b0164
	public Void OnSwitchLangType(VoiceLangType type) { }
	// RVA: 0x2298368 VA: 0x75948b0368
	public Void OnReturn() { }
	// RVA: 0x2298770 VA: 0x75948b0770
	public Void OnRoute(UIRouteTarget t, Boolean b) { }
	// RVA: 0x2298820 VA: 0x75948b0820
	public Void .ctor() { }
	// RVA: 0x2298a20 VA: 0x75948b0a20
	private Void <_OnInitTopMenu>b__11_0() { }
	// RVA: 0x2298a24 VA: 0x75948b0a24
	private Void <OnSwitchLangTypeConfirm>b__17_0(SetCharVoiceLanResponse response) { }
	// RVA: 0x2298be4 VA: 0x75948b0be4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```