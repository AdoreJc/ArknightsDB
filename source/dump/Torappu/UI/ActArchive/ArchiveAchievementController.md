# ArchiveAchievementController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveAchievementDataBinder _achievementDataBinder`


## Properties

- `ArchiveAchievementDataBinder dataBinder`


## Methods

- `Void set_onFilterChange(Action`2)`

- `Void set_onGotFilterSelectionChange(Action`1)`

- `ArchiveAchievementDataBinder get_dataBinder()`

- `Void OnFilterSelectionChange(FilterType, String)`

- `Void OnGotFilterSelectionChange(GotType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAchievementController : ActArchiveController
{
	private ArchiveAchievementDataBinder _achievementDataBinder; // 0x38
	private Action`2 <onFilterChange>k__BackingField; // 0x40
	private Action`1 <onGotFilterSelectionChange>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onFilterChange; // 0x0
	private static DelegateBridge __Hotfix0_set_onFilterChange; // 0x8
	private static DelegateBridge __Hotfix0_get_onGotFilterSelectionChange; // 0x10
	private static DelegateBridge __Hotfix0_set_onGotFilterSelectionChange; // 0x18
	private static DelegateBridge __Hotfix0_get_dataBinder; // 0x20
	private static DelegateBridge __Hotfix0_OnFilterSelectionChange; // 0x28
	private static DelegateBridge __Hotfix0_OnGotFilterSelectionChange; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`2 onFilterChange { get; set; }
	public Action`1 onGotFilterSelectionChange { get; set; }
	public ArchiveAchievementDataBinder dataBinder { get; }

	// RVA: 0x3014798 VA: 0x759562c798
	public Action`2 get_onFilterChange() { }
	// RVA: 0x3011474 VA: 0x7595629474
	public Void set_onFilterChange(Action`2 value) { }
	// RVA: 0x3014800 VA: 0x759562c800
	public Action`1 get_onGotFilterSelectionChange() { }
	// RVA: 0x30113f0 VA: 0x75956293f0
	public Void set_onGotFilterSelectionChange(Action`1 value) { }
	// RVA: 0x30114f8 VA: 0x75956294f8
	public ArchiveAchievementDataBinder get_dataBinder() { }
	// RVA: 0x3014868 VA: 0x759562c868
	public Void OnFilterSelectionChange(FilterType filterType, String value) { }
	// RVA: 0x301492c VA: 0x759562c92c
	public Void OnGotFilterSelectionChange(GotType type) { }
	// RVA: 0x30149e4 VA: 0x759562c9e4
	public Void .ctor() { }
}
```