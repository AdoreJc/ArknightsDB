# CharacterRepoCardView

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `Transform _characterContainer`

- `Single _cardScaleFactor`

- `UIColorGroupSetter _greySetter`

- `Color _greyColor`

- `UICommonTrackPoint _trackPoint`

- `UICommonTrackPoint _newPoint`

- `UICommonTrackPoint _newVoicePoint`

- `GameObject _starMarkSelectBg`

- `GameObject _starMarkSelectTag`

- `RectTransform _sortInfoContainer`

- `UICharacterSortInfoPanel _sortInfoPrefab`

- `CanvasGroup _alphaHandler`

- `Boolean m_isGrey`

- `Boolean m_isInited`

- `Int32 m_chrInstIdCache`

- `TrackPointViewProperty m_charRepoTrackProp`

- `TrackPointViewProperty m_charRepoNewTrackProp`

- `TrackPointViewProperty m_charRepoNewVoiceTrackProp`

- `UICharacterSortInfoPanel m_sortInfoInst`

- `GameObject m_cardObject`

- `Trigger m_avgBindCard`

- `FadeSwitchTween m_showSwitch`

- `Boolean m_isStarMarkSelected`

- `UICharacterCardPanel m_cardInst`


## Properties

- `Boolean isGrey`

- `Boolean isStarMarkSelected`


## Methods

- `Void _InitIfNot()`

- `Void set_onClick(Action`1)`

- `Boolean get_isGrey()`

- `Void set_isGrey(Boolean)`

- `Boolean get_isStarMarkSelected()`

- `Void set_isStarMarkSelected(Boolean)`

- `Void RenderCard(Int32, CharacterCardViewModel, CharacterTrackPointData, CharacterSortType, Params)`

- `Void _UpdateCharCard(Int32, CharacterCardViewModel, Params)`

- `Void _UpdateCharCardSync(Int32, CharacterCardViewModel, Params)`

- `Void EventOnClick()`

- `Void _OnClick(Int32)`

- `Void _SetStarMarkSelectStatus(Boolean)`

- `Void OnGameObjectLoaded(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoCardView : MonoBehaviour, IAsyncObjectListener, IHotfixable
{
	private Transform _characterContainer; // 0x18
	private Single _cardScaleFactor; // 0x20
	private UIColorGroupSetter _greySetter; // 0x28
	private Color _greyColor; // 0x30
	private UICommonTrackPoint _trackPoint; // 0x40
	private UICommonTrackPoint _newPoint; // 0x48
	private UICommonTrackPoint _newVoicePoint; // 0x50
	private GameObject _starMarkSelectBg; // 0x58
	private GameObject _starMarkSelectTag; // 0x60
	private RectTransform _sortInfoContainer; // 0x68
	private UICharacterSortInfoPanel _sortInfoPrefab; // 0x70
	private CanvasGroup _alphaHandler; // 0x78
	private Boolean m_isGrey; // 0x80
	private Boolean m_isInited; // 0x81
	private Int32 m_chrInstIdCache; // 0x84
	private TrackPointViewProperty m_charRepoTrackProp; // 0x88
	private TrackPointViewProperty m_charRepoNewTrackProp; // 0x90
	private TrackPointViewProperty m_charRepoNewVoiceTrackProp; // 0x98
	private UICharacterSortInfoPanel m_sortInfoInst; // 0xa0
	private AsyncDataViewHandler`2 m_asyncHandler; // 0xa8
	private GameObject m_cardObject; // 0xb0
	private Trigger m_avgBindCard; // 0xb8
	private FadeSwitchTween m_showSwitch; // 0xc0
	private Boolean m_isStarMarkSelected; // 0xc8
	private Action`1 <onClick>k__BackingField; // 0xd0
	private UICharacterCardPanel m_cardInst; // 0xd8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_onClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onClick; // 0x10
	private static DelegateBridge __Hotfix0_get_isGrey; // 0x18
	private static DelegateBridge __Hotfix0_set_isGrey; // 0x20
	private static DelegateBridge __Hotfix0_get_isStarMarkSelected; // 0x28
	private static DelegateBridge __Hotfix0_set_isStarMarkSelected; // 0x30
	private static DelegateBridge __Hotfix0_RenderCard; // 0x38
	private static DelegateBridge __Hotfix0__UpdateCharCard; // 0x40
	private static DelegateBridge __Hotfix0__UpdateCharCardSync; // 0x48
	private static DelegateBridge __Hotfix0__TraceForAVGIfPermitted; // 0x50
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x58
	private static DelegateBridge __Hotfix0__OnClick; // 0x60
	private static DelegateBridge __Hotfix0__SetStarMarkSelectStatus; // 0x68
	private static DelegateBridge __Hotfix0_OnGameObjectLoaded; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Action`1 onClick { get; set; }
	public Boolean isGrey { get; set; }
	public Boolean isStarMarkSelected { get; set; }

	// RVA: 0x2cfc930 VA: 0x7595314930
	private Void _InitIfNot() { }
	// RVA: 0x2cfcbf0 VA: 0x7595314bf0
	private Action`1 get_onClick() { }
	// RVA: 0x2cfcc58 VA: 0x7595314c58
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2cfccdc VA: 0x7595314cdc
	public Boolean get_isGrey() { }
	// RVA: 0x2cfcd44 VA: 0x7595314d44
	public Void set_isGrey(Boolean value) { }
	// RVA: 0x2cfce0c VA: 0x7595314e0c
	public Boolean get_isStarMarkSelected() { }
	// RVA: 0x2cfce74 VA: 0x7595314e74
	public Void set_isStarMarkSelected(Boolean value) { }
	// RVA: 0x2cfcf14 VA: 0x7595314f14
	public Void RenderCard(Int32 index, CharacterCardViewModel viewModel, CharacterTrackPointData trackPointData, CharacterSortType sortType, Params customParam) { }
	// RVA: 0x2cfd25c VA: 0x759531525c
	private Void _UpdateCharCard(Int32 index, CharacterCardViewModel cardModel, Params customParam) { }
	// RVA: 0x2cfd4b4 VA: 0x75953154b4
	private Void _UpdateCharCardSync(Int32 index, CharacterCardViewModel cardModel, Params customParam) { }
	// RVA: 0x2cfd678 VA: 0x7595315678
	private static Void _TraceForAVGIfPermitted(Trigger avgBindCard, GameObject cardObject) { }
	// RVA: 0x2cfd94c VA: 0x759531594c
	public Void EventOnClick() { }
	// RVA: 0x2cfd9b8 VA: 0x75953159b8
	private Void _OnClick(Int32 chrInstId) { }
	// RVA: 0x2cfca5c VA: 0x7595314a5c
	private Void _SetStarMarkSelectStatus(Boolean select) { }
	// RVA: 0x2cfd760 VA: 0x7595315760
	public Void OnGameObjectLoaded(GameObject cardObject) { }
	// RVA: 0x2cfda70 VA: 0x7595315a70
	public Void .ctor() { }
}
```