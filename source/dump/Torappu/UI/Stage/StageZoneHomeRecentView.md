# StageZoneHomeRecentView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textType`

- `Image _imgType`

- `Text _textStageCode`

- `Text _textStageName`

- `GameObject _panelStage`

- `String m_cachedStageId`

- `Action <onClick>k__BackingField`


## Properties

- `Action onClick`


## Methods

- `Action get_onClick()`

- `Void set_onClick(Action)`

- `Boolean _CheckIfDirty(ZoneHomeRecentViewModel)`

- `Void _Render(ZoneHomeRecentViewModel)`

- `TypeConfig _GetTypeConfig(HomeRecentStageType)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeRecentView : DataBinder`1
{
	private Text _textType; // 0x20
	private Image _imgType; // 0x28
	private Text _textStageCode; // 0x30
	private Text _textStageName; // 0x38
	private GameObject _panelStage; // 0x40
	private List`1 _typeConfigs; // 0x48
	private String m_cachedStageId; // 0x50
	private Action <onClick>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfDirty; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0__GetTypeConfig; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onClick { get; set; }

	// RVA: 0x2f01898 VA: 0x7595519898
	private Action get_onClick() { }
	// RVA: 0x2f01900 VA: 0x7595519900
	public Void set_onClick(Action value) { }
	// RVA: 0x2f01984 VA: 0x7595519984
	public override Void OnValueChanged(ZoneHomeRecentViewProp property) { }
	// RVA: 0x2f01a50 VA: 0x7595519a50
	private Boolean _CheckIfDirty(ZoneHomeRecentViewModel viewModel) { }
	// RVA: 0x2f01b00 VA: 0x7595519b00
	private Void _Render(ZoneHomeRecentViewModel viewModel) { }
	// RVA: 0x2f01c9c VA: 0x7595519c9c
	private TypeConfig _GetTypeConfig(HomeRecentStageType type) { }
	// RVA: 0x2f01e54 VA: 0x7595519e54
	public Void EventOnClicked() { }
	// RVA: 0x2f01ef0 VA: 0x7595519ef0
	public Void .ctor() { }
}
```