# ArchiveRelicController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveRelicListDataBinder _relicDataBinder`

- `Image _imgBkg`


## Methods

- `Void set_onRelicItemClicked(Action`2)`

- `Void set_onFilterMethodClicked(Action`1)`

- `Void set_onSwitchDifficultyClicked(Action`1)`

- `Void OnFilterMethodClick(FilterRule)`

- `Void OnSwitchForwardClicked()`

- `Void OnSwitchBackwardClicked()`

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicController : ActArchiveController
{
	private ArchiveRelicListDataBinder _relicDataBinder; // 0x38
	private Image _imgBkg; // 0x40
	private Action`2 <onRelicItemClicked>k__BackingField; // 0x48
	private Action`1 <onFilterMethodClicked>k__BackingField; // 0x50
	private Action`1 <onSwitchDifficultyClicked>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onRelicItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onRelicItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onFilterMethodClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onFilterMethodClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onSwitchDifficultyClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onSwitchDifficultyClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x30
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x38
	private static DelegateBridge __Hotfix0_OnFilterMethodClick; // 0x40
	private static DelegateBridge __Hotfix0_OnSwitchForwardClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnSwitchBackwardClicked; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action`2 onRelicItemClicked { get; set; }
	private Action`1 onFilterMethodClicked { get; set; }
	private Action`1 onSwitchDifficultyClicked { get; set; }

	// RVA: 0x307799c VA: 0x759568f99c
	private Action`2 get_onRelicItemClicked() { }
	// RVA: 0x3077a04 VA: 0x759568fa04
	public Void set_onRelicItemClicked(Action`2 value) { }
	// RVA: 0x3077a88 VA: 0x759568fa88
	private Action`1 get_onFilterMethodClicked() { }
	// RVA: 0x3077af0 VA: 0x759568faf0
	public Void set_onFilterMethodClicked(Action`1 value) { }
	// RVA: 0x3077b74 VA: 0x759568fb74
	private Action`1 get_onSwitchDifficultyClicked() { }
	// RVA: 0x3077bdc VA: 0x759568fbdc
	public Void set_onSwitchDifficultyClicked(Action`1 value) { }
	// RVA: 0x3077c60 VA: 0x759568fc60
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3077d1c VA: 0x759568fd1c
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3077ecc VA: 0x759568fecc
	public Void OnFilterMethodClick(FilterRule rule) { }
	// RVA: 0x3077f84 VA: 0x759568ff84
	public Void OnSwitchForwardClicked() { }
	// RVA: 0x3078024 VA: 0x7595690024
	public Void OnSwitchBackwardClicked() { }
	// RVA: 0x30780c4 VA: 0x75956900c4
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x30781fc VA: 0x75956901fc
	public Void .ctor() { }
	// RVA: 0x307826c VA: 0x759569026c
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x3078274 VA: 0x7595690274
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
}
```