# VoicelangSettingStateBean

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `VoicelangCardGroupViewProperty cardGroupProperty`

- `VoicelangPowerGroupViewProperty powerGroupProperty`

- `VoicelangSettingConfirmViewProperty settingConfirmProperty`

- `VoicelangTypeSelectGroupViewProperty typeGroupProperty`


## Methods

- `Void LoadData()`

- `Void OnPowerSelect(Boolean, String)`

- `Void OnTypeTabSelect(Boolean, VoiceLangGroupType)`

- `Void OnCardSelect(String)`

- `Void OnBatchSelect()`

- `Void OnSwitchLangTypeSuccess()`

- `Void OnSwitchLangTypeCancel()`

- `Void OnSwitchLangType(VoiceLangType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangSettingStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public VoicelangCardGroupViewProperty cardGroupProperty; // 0x10
	public VoicelangPowerGroupViewProperty powerGroupProperty; // 0x18
	public VoicelangSettingConfirmViewProperty settingConfirmProperty; // 0x20
	public VoicelangTypeSelectGroupViewProperty typeGroupProperty; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnPowerSelect; // 0x8
	private static DelegateBridge __Hotfix0_OnTypeTabSelect; // 0x10
	private static DelegateBridge __Hotfix0_OnCardSelect; // 0x18
	private static DelegateBridge __Hotfix0_OnBatchSelect; // 0x20
	private static DelegateBridge __Hotfix0_OnSwitchLangTypeSuccess; // 0x28
	private static DelegateBridge __Hotfix0_OnSwitchLangTypeCancel; // 0x30
	private static DelegateBridge __Hotfix0_OnSwitchLangType; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22961d0 VA: 0x75948ae1d0
	public Void LoadData() { }
	// RVA: 0x2297070 VA: 0x75948af070
	public Void OnPowerSelect(Boolean isAll, String powerId) { }
	// RVA: 0x22972a0 VA: 0x75948af2a0
	public Void OnTypeTabSelect(Boolean isAll, VoiceLangGroupType type) { }
	// RVA: 0x22974e4 VA: 0x75948af4e4
	public Void OnCardSelect(String wordKey) { }
	// RVA: 0x229778c VA: 0x75948af78c
	public Void OnBatchSelect() { }
	// RVA: 0x2298a3c VA: 0x75948b0a3c
	public Void OnSwitchLangTypeSuccess() { }
	// RVA: 0x2298064 VA: 0x75948b0064
	public Void OnSwitchLangTypeCancel() { }
	// RVA: 0x22981ec VA: 0x75948b01ec
	public Void OnSwitchLangType(VoiceLangType type) { }
	// RVA: 0x22988cc VA: 0x75948b08cc
	public Void .ctor() { }
}
```