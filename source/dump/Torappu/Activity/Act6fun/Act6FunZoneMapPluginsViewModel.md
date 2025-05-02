# Act6FunZoneMapPluginsViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Act6FunZoneMapBgPluginViewModel m_bgPluginViewModel`

- `Act6FunZoneMapAchievePluginViewModel m_achievePluginViewModel`


## Properties

- `Act6FunZoneMapBgPluginViewModel bgPluginViewModel`

- `Act6FunZoneMapAchievePluginViewModel achievePluginViewModel`


## Methods

- `Act6FunZoneMapBgPluginViewModel get_bgPluginViewModel()`

- `Act6FunZoneMapAchievePluginViewModel get_achievePluginViewModel()`

- `Void LoadData(ActivityCustomZoneMapViewModel)`

- `Void RefreshAchievePluginByPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapPluginsViewModel : IHotfixable
{
	private Act6FunZoneMapBgPluginViewModel m_bgPluginViewModel; // 0x10
	private Act6FunZoneMapAchievePluginViewModel m_achievePluginViewModel; // 0x18
	private ListDict`2 m_stageButtonPluginViewModelDict; // 0x20
	private Dictionary`2 m_stagePreviewPluginViewModelDict; // 0x28
	private static DelegateBridge __Hotfix0_get_bgPluginViewModel; // 0x0
	private static DelegateBridge __Hotfix0_get_achievePluginViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_stageButtonPluginViewModelDict; // 0x10
	private static DelegateBridge __Hotfix0_get_stagePreviewPluginViewModelDict; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshAchievePluginByPlayerData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Act6FunZoneMapBgPluginViewModel bgPluginViewModel { get; }
	public Act6FunZoneMapAchievePluginViewModel achievePluginViewModel { get; }
	public ListDict`2 stageButtonPluginViewModelDict { get; }
	public Dictionary`2 stagePreviewPluginViewModelDict { get; }

	// RVA: 0x31b4060 VA: 0x75957cc060
	public Act6FunZoneMapBgPluginViewModel get_bgPluginViewModel() { }
	// RVA: 0x31b40c8 VA: 0x75957cc0c8
	public Act6FunZoneMapAchievePluginViewModel get_achievePluginViewModel() { }
	// RVA: 0x31b4130 VA: 0x75957cc130
	public ListDict`2 get_stageButtonPluginViewModelDict() { }
	// RVA: 0x31b4198 VA: 0x75957cc198
	public Dictionary`2 get_stagePreviewPluginViewModelDict() { }
	// RVA: 0x31b042c VA: 0x75957c842c
	public Void LoadData(ActivityCustomZoneMapViewModel zoneModel) { }
	// RVA: 0x31b4200 VA: 0x75957cc200
	public Void RefreshAchievePluginByPlayerData() { }
	// RVA: 0x31b02a8 VA: 0x75957c82a8
	public Void .ctor() { }
}
```