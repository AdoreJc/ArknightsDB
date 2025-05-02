# BuildingStationSelectCharCard

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `Text _textName`

- `UIAtlasImage _portrait`

- `SimpleLayoutContent _buffIconLayout`

- `RectTransform _manpowerBarContainer`

- `GameObject _maskRest`

- `GameObject _maskWork`

- `GameObject _maskTired`

- `GameObject _maskTraining`

- `GameObject _panelStationed`

- `GameObject _panelInPreQueue`

- `GameObject _panelInLockStation`

- `Text _textRoom`

- `Image _iconRoom`

- `GameObject _panelCharSortInfo`

- `Text _textFavor`

- `StationCharViewModel m_viewModel`

- `ViewCache m_viewCache`

- `Boolean m_isInited`

- `BuildingCharMPStateBar m_mpBar`

- `BuildingCharMPHelper m_mpHelper`

- `BuffIconAdapter m_buffAdapter`

- `CharSortType m_cachedSortType`


## Properties

- `BuildingCharSelectRoomConfig roomConfig`


## Methods

- `BuildingCharSelectRoomConfig get_roomConfig()`

- `Void Start()`

- `Void OnDestroy()`

- `Void Render(StationCharViewModel, CharSortType)`

- `Void EventOnCardClicked()`

- `Void UpdateTime(Single)`

- `Void _OnManpowerChanged()`

- `Void _Init(StationCharViewModel)`

- `Void _RenderMP()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectCharCard : MonoBehaviour, IHotfixable, ITimeWatcher
{
	private Text _textName; // 0x18
	private UICharRarityImage[] _rarityImages; // 0x20
	private UIAtlasImage _portrait; // 0x28
	private SimpleLayoutContent _buffIconLayout; // 0x30
	private RectTransform _manpowerBarContainer; // 0x38
	private GameObject _maskRest; // 0x40
	private GameObject _maskWork; // 0x48
	private GameObject _maskTired; // 0x50
	private GameObject _maskTraining; // 0x58
	private GameObject _panelStationed; // 0x60
	private GameObject _panelInPreQueue; // 0x68
	private GameObject _panelInLockStation; // 0x70
	private Text _textRoom; // 0x78
	private Image _iconRoom; // 0x80
	private GameObject _panelCharSortInfo; // 0x88
	private Text _textFavor; // 0x90
	private StationCharViewModel m_viewModel; // 0x98
	private ViewCache m_viewCache; // 0xa0
	private Boolean m_isInited; // 0x120
	private BuildingCharMPStateBar m_mpBar; // 0x128
	private BuildingCharMPHelper m_mpHelper; // 0x130
	private BuffIconAdapter m_buffAdapter; // 0x138
	private CharSortType m_cachedSortType; // 0x140
	public Action`1 onCardClicked; // 0x148
	private static DelegateBridge __Hotfix0_get_roomConfig; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCardClicked; // 0x20
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x28
	private static DelegateBridge __Hotfix0__OnManpowerChanged; // 0x30
	private static DelegateBridge __Hotfix0__Init; // 0x38
	private static DelegateBridge __Hotfix0__RenderMP; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public BuildingCharSelectRoomConfig roomConfig { get; }

	// RVA: 0x3d9a1ec VA: 0x75963b21ec
	public BuildingCharSelectRoomConfig get_roomConfig() { }
	// RVA: 0x3d9a284 VA: 0x75963b2284
	private Void Start() { }
	// RVA: 0x3d9a2f4 VA: 0x75963b22f4
	private Void OnDestroy() { }
	// RVA: 0x3d9a364 VA: 0x75963b2364
	public Void Render(StationCharViewModel viewModel, CharSortType sortType) { }
	// RVA: 0x3d9afd4 VA: 0x75963b2fd4
	public Void EventOnCardClicked() { }
	// RVA: 0x3d9b064 VA: 0x75963b3064
	public Void UpdateTime(Single delta) { }
	// RVA: 0x3d9b118 VA: 0x75963b3118
	private Void _OnManpowerChanged() { }
	// RVA: 0x3d9ac74 VA: 0x75963b2c74
	private Void _Init(StationCharViewModel viewModel) { }
	// RVA: 0x3d9ae9c VA: 0x75963b2e9c
	private Void _RenderMP() { }
	// RVA: 0x3d9b214 VA: 0x75963b3214
	public Void .ctor() { }
}
```