# StageZoneHomeThemeView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Button _btnEnter`

- `GameObject _panelLock`

- `Text _textLock`

- `GameObject _panelContent`

- `GameObject _panelEmpty`

- `GameObject _themeInfo`

- `RectTransform _pluginContainer`

- `GameObject _panelEndTime`

- `Text _textEndTime`

- `StageZoneHomeEntryMedalView _medalPrefab`

- `RectTransform _medalContainer`

- `UIProgressCalender _calender`

- `UIProgressCalender _bkgCalender`

- `Text _titleCalender`

- `GameObject _logoContainer`

- `Image _logoImg`

- `ZoneHomeThemeViewModel m_cachedModel`

- `CountDownTask m_endTimeCountDown`

- `StageZoneHomeEntryMedalView m_medalView`

- `Plugin m_plugin`

- `HomeEntryFuncType m_pluginType`


## Methods

- `Void set_onThemeClicked(Action`1)`

- `Void EventOnThemeClicked()`

- `Void EventOnThemeClickedPluginOnly()`

- `Void _UpdatePlugin(ZoneHomeThemeViewModel)`

- `Plugin _GetPluginPrefabFromType(HomeEntryFuncType)`

- `Void _UpdateMedalInfo(ZoneHomeEntryItemModel)`

- `Void _UpdateEndTime(ZoneHomeEntryItemModel)`

- `Void _TickEndTimeDisplay(TickValue)`

- `Void _UpdateCalender(ZoneHomeThemeViewModel)`

- `Void _UpdateLockStatus(ZoneHomeEntryItemModel)`

- `Void _UpdateLogo(ZoneHomeEntryItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeThemeView : DataBinder`1
{
	private Button _btnEnter; // 0x20
	private GameObject _panelLock; // 0x28
	private Text _textLock; // 0x30
	private GameObject _panelContent; // 0x38
	private GameObject _panelEmpty; // 0x40
	private GameObject _themeInfo; // 0x48
	private List`1 _plugins; // 0x50
	private RectTransform _pluginContainer; // 0x58
	private GameObject _panelEndTime; // 0x60
	private Text _textEndTime; // 0x68
	private StageZoneHomeEntryMedalView _medalPrefab; // 0x70
	private RectTransform _medalContainer; // 0x78
	private UIProgressCalender _calender; // 0x80
	private UIProgressCalender _bkgCalender; // 0x88
	private Text _titleCalender; // 0x90
	private GameObject _logoContainer; // 0x98
	private Image _logoImg; // 0xa0
	private ZoneHomeThemeViewModel m_cachedModel; // 0xa8
	private CountDownTask m_endTimeCountDown; // 0xb0
	private StageZoneHomeEntryMedalView m_medalView; // 0xb8
	private List`1 m_calenderNodes; // 0xc0
	private Action`1 <onThemeClicked>k__BackingField; // 0xc8
	private Plugin m_plugin; // 0xd0
	private HomeEntryFuncType m_pluginType; // 0xd8
	private static DelegateBridge __Hotfix0_get_onThemeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onThemeClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_EventOnThemeClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnThemeClickedPluginOnly; // 0x20
	private static DelegateBridge __Hotfix0__UpdatePlugin; // 0x28
	private static DelegateBridge __Hotfix0__GetPluginPrefabFromType; // 0x30
	private static DelegateBridge __Hotfix0__UpdateMedalInfo; // 0x38
	private static DelegateBridge __Hotfix0__UpdateEndTime; // 0x40
	private static DelegateBridge __Hotfix0__TickEndTimeDisplay; // 0x48
	private static DelegateBridge __Hotfix0__UpdateCalender; // 0x50
	private static DelegateBridge __Hotfix0__UpdateLockStatus; // 0x58
	private static DelegateBridge __Hotfix0__UpdateLogo; // 0x60
	private static DelegateBridge __Hotfix0_Update; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Action`1 onThemeClicked { get; set; }

	// RVA: 0x2f02d4c VA: 0x759551ad4c
	private Action`1 get_onThemeClicked() { }
	// RVA: 0x2f02db4 VA: 0x759551adb4
	public Void set_onThemeClicked(Action`1 value) { }
	// RVA: 0x2f02e38 VA: 0x759551ae38
	public override Void OnValueChanged(ZoneHomeThemeViewProp viewProp) { }
	// RVA: 0x2f039e8 VA: 0x759551b9e8
	public Void EventOnThemeClicked() { }
	// RVA: 0x2f03aa0 VA: 0x759551baa0
	public Void EventOnThemeClickedPluginOnly() { }
	// RVA: 0x2f02f78 VA: 0x759551af78
	private Void _UpdatePlugin(ZoneHomeThemeViewModel viewModel) { }
	// RVA: 0x2f03b08 VA: 0x759551bb08
	private Plugin _GetPluginPrefabFromType(HomeEntryFuncType funcType) { }
	// RVA: 0x2f03174 VA: 0x759551b174
	private Void _UpdateMedalInfo(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2f0333c VA: 0x759551b33c
	private Void _UpdateEndTime(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2f03d2c VA: 0x759551bd2c
	private Void _TickEndTimeDisplay(TickValue value) { }
	// RVA: 0x2f03428 VA: 0x759551b428
	private Void _UpdateCalender(ZoneHomeThemeViewModel themeModel) { }
	// RVA: 0x2f03720 VA: 0x759551b720
	private Void _UpdateLockStatus(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2f038b0 VA: 0x759551b8b0
	private Void _UpdateLogo(ZoneHomeEntryItemModel entryModel) { }
	// RVA: 0x2f03e2c VA: 0x759551be2c
	protected virtual Void Update() { }
	// RVA: 0x2f03ea8 VA: 0x759551bea8
	public Void .ctor() { }
}
```