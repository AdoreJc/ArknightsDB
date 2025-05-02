# Act36sideZoneMapCardFrontView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `RectTransform _floatPanel`

- `Act36sideZoneFocusAnimView _animViewPrefab`

- `Button _hotspot`

- `Sprite _backSprite`

- `Boolean m_isInited`

- `Boolean m_isButtonInited`

- `Int32 m_pageIndex`

- `FadeSwitchTween m_lineFadeSwitchTween`

- `UIBiAnimClipSwitchTween m_stableAnimTween`

- `Act36sideZoneMapCardBackView m_backView`


## Properties

- `Int32 pageIndex`

- `Act36sideZoneFocusAnimView animViewPrefab`


## Methods

- `Int32 get_pageIndex()`

- `Act36sideZoneFocusAnimView get_animViewPrefab()`

- `Void _InitStageButtonIfNot(ZoneViewModel)`

- `Void BindBackCard(Act36sideZoneMapCardBackView)`

- `Void Render(ZoneViewModel, Int32)`

- `Void OnCardClick()`

- `Void _ZoneMapOnlyRenderStage(StageButtonOnMap, MainStageButtonOnMapHolder, StageViewModel, ZoneViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneMapCardFrontView : MonoBehaviour, IHotfixable
{
	private RectTransform _floatPanel; // 0x18
	private Act36sideZoneFocusAnimView _animViewPrefab; // 0x20
	private Button _hotspot; // 0x28
	private Sprite _backSprite; // 0x30
	private List`1 _stageButtonHolders; // 0x38
	public Action`1 onCardClick; // 0x40
	public Action`1 onStageSelect; // 0x48
	public Action`1 onSpecialStageReward; // 0x50
	private Boolean m_isInited; // 0x58
	private Boolean m_isButtonInited; // 0x59
	private Int32 m_pageIndex; // 0x5c
	private List`1 m_stagesOnCard; // 0x60
	private List`1 m_activeHolders; // 0x68
	private FadeSwitchTween m_lineFadeSwitchTween; // 0x70
	private UIBiAnimClipSwitchTween m_stableAnimTween; // 0x78
	private Act36sideZoneMapCardBackView m_backView; // 0x80
	private static DelegateBridge __Hotfix0_get_stagesOnCard; // 0x0
	private static DelegateBridge __Hotfix0_get_pageIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_animViewPrefab; // 0x10
	private static DelegateBridge __Hotfix0__InitStageButtonIfNot; // 0x18
	private static DelegateBridge __Hotfix0_BindBackCard; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x30
	private static DelegateBridge __Hotfix0__ZoneMapOnlyRenderStage; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 stagesOnCard { get; }
	public Int32 pageIndex { get; }
	public Act36sideZoneFocusAnimView animViewPrefab { get; }

	// RVA: 0x32497a0 VA: 0x75958617a0
	public List`1 get_stagesOnCard() { }
	// RVA: 0x3249a34 VA: 0x7595861a34
	public Int32 get_pageIndex() { }
	// RVA: 0x3249a9c VA: 0x7595861a9c
	public Act36sideZoneFocusAnimView get_animViewPrefab() { }
	// RVA: 0x3249b04 VA: 0x7595861b04
	private Void _InitStageButtonIfNot(ZoneViewModel model) { }
	// RVA: 0x3249e3c VA: 0x7595861e3c
	public Void BindBackCard(Act36sideZoneMapCardBackView backView) { }
	// RVA: 0x3249f74 VA: 0x7595861f74
	public Void Render(ZoneViewModel model, Int32 pageIndex) { }
	// RVA: 0x324a330 VA: 0x7595862330
	public Void OnCardClick() { }
	// RVA: 0x324a1d4 VA: 0x75958621d4
	private Void _ZoneMapOnlyRenderStage(StageButtonOnMap button, MainStageButtonOnMapHolder holder, StageViewModel stageModel, ZoneViewModel zoneModel, Boolean isSelected) { }
	// RVA: 0x324a3b8 VA: 0x75958623b8
	public Void .ctor() { }
}
```