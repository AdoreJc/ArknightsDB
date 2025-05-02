# FireworkCraftView

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `Image _imgMap`

- `Single _gridSize`

- `Vector2 _mapOffsetSize`

- `RectTransform _bkgParticleFxContainer`

- `RectTransform _animalBgContainer`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _mapBtnOnAnim`

- `UIAnimationLocation _mapBtnOffAnim`

- `UIAnimationLocation _rightListSwitchAnim`

- `UIAnimationLocation _bkgSwitchAnim`

- `RectTransform _plateViewContainer`

- `RectTransform _plateViewContainerMap`

- `RectTransform _plateRootMap`

- `RectTransform _plateSelectionViewContainer`

- `RectTransform _plateSelectionViewContainerMap`

- `RectTransform _plateListViewContainer`

- `RectTransform _filledPlateListViewContainer`

- `FireworkCraftBtnSaveView _saveBtnView`

- `FireworkGroupListRaycastLayer _pnlRaycastLayer`

- `SimpleLayoutContent _stageContent`

- `Text _zoneName`

- `Text _stageCode`

- `Image _scrollHandler`

- `UIAnimationLocation _animalIconSwitchAnim`

- `Image _animalIcon`

- `Image _animalName`

- `Text _effectBuffDesc`

- `GameObject _animalNewPanel`

- `Image _animalDescBgColor`

- `UIAtlasImage _animalSelectBtnBg`

- `Image _animalSelectedPlateBg`

- `GameObject _fireworkPlateGo`

- `Button _fireworkAnimalSwitchButton`

- `Button _btnSave`

- `Button _btnSwitchMap`

- `CanvasGroup _alphaHandler`

- `Single _alphaMin`

- `Single _alphaMax`

- `Single _loopDur`

- `Boolean m_hasInited`

- `Tween m_enterAnimTween`

- `UISwitchTween m_mapBtnSwitchTween`

- `UISwitchTween m_rightListSwitchTween`

- `UISwitchTween m_bkgSwitchTween`

- `Tween m_animalIconSwitchTween`

- `Int32 m_cachedEnterSeqNum`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `EditStatus m_cachedStatus`

- `FireworkPlateListView m_plateListView`

- `FireworkPlateGroupViewStyle m_plateListStyle`

- `FireworkPlateView m_plateView`

- `FireworkPlateSelectionView m_plateSelectionView`

- `FireworkPlateViewStyle m_plateStyle`

- `FireworkPlateView m_plateViewMap`

- `FireworkPlateSelectionView m_plateSelectionViewMap`

- `FireworkPlateViewStyle m_plateStyleMap`

- `FireworkPlateFilledListView m_filledPlateListView`

- `GameObject m_animalBkg`

- `String m_cachedAnimalId`

- `String m_cachedAnimalIconId`

- `String m_cachedAnimalNameId`

- `String m_cachedSelectedStageId`

- `StageAdapter m_stageAdapter`

- `Tween m_loopTween`


## Properties

- `Boolean isStable`


## Methods

- `Boolean get_isStable()`

- `Void _InitIfNot()`

- `Void _PlayTweens(FireworkCraftModel)`

- `Void _ResetPlateStyle(String)`

- `Void _RenderImgMap(String, Boolean)`

- `Void _RenderFireworkView(FireworkPlateGroupModel, String, Boolean)`

- `Void _RenderAnimalBkg(String)`

- `Void _RenderStageList(FireworkCraftModel, Boolean)`

- `Void _RenderAnimalEffectPart(FireworkCraftModel)`

- `Void _SetPlatePos(EditStatus, CraftStageInfoModel, Boolean)`

- `Void RegisterTutorialGo()`

- `Void EventOnMapEditBtnClicked()`

- `Void EventOnStageChooseBtnClicked()`

- `Void EventOnStageChooseBgClicked()`

- `Void EventOnAnimalSelectClicked()`

- `Void OnBtnSaveClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftView : DataBinder`1
{
	private Image _imgMap; // 0x20
	private Single _gridSize; // 0x28
	private Vector2 _mapOffsetSize; // 0x2c
	private RectTransform _bkgParticleFxContainer; // 0x38
	private RectTransform _animalBgContainer; // 0x40
	private UIAnimationLocation _enterAnim; // 0x48
	private UIAnimationLocation _mapBtnOnAnim; // 0x58
	private UIAnimationLocation _mapBtnOffAnim; // 0x68
	private UIAnimationLocation _rightListSwitchAnim; // 0x78
	private UIAnimationLocation _bkgSwitchAnim; // 0x88
	private RectTransform _plateViewContainer; // 0x98
	private RectTransform _plateViewContainerMap; // 0xa0
	private RectTransform _plateRootMap; // 0xa8
	private RectTransform _plateSelectionViewContainer; // 0xb0
	private RectTransform _plateSelectionViewContainerMap; // 0xb8
	private RectTransform _plateListViewContainer; // 0xc0
	private RectTransform _filledPlateListViewContainer; // 0xc8
	private FireworkCraftBtnSaveView _saveBtnView; // 0xd0
	private FireworkGroupListRaycastLayer _pnlRaycastLayer; // 0xd8
	private SimpleLayoutContent _stageContent; // 0xe0
	private FireworkCraftZoneBtnItem[] _zoneItems; // 0xe8
	private Text _zoneName; // 0xf0
	private Text _stageCode; // 0xf8
	private Image _scrollHandler; // 0x100
	private UIAnimationLocation _animalIconSwitchAnim; // 0x108
	private Image _animalIcon; // 0x118
	private Image _animalName; // 0x120
	private Text _effectBuffDesc; // 0x128
	private GameObject _animalNewPanel; // 0x130
	private Image _animalDescBgColor; // 0x138
	private UIAtlasImage _animalSelectBtnBg; // 0x140
	private Image _animalSelectedPlateBg; // 0x148
	private GameObject _fireworkPlateGo; // 0x150
	private Button _fireworkAnimalSwitchButton; // 0x158
	private Button _btnSave; // 0x160
	private Button _btnSwitchMap; // 0x168
	private CanvasGroup _alphaHandler; // 0x170
	private Single _alphaMin; // 0x178
	private Single _alphaMax; // 0x17c
	private Single _loopDur; // 0x180
	private Boolean m_hasInited; // 0x184
	private Tween m_enterAnimTween; // 0x188
	private UISwitchTween m_mapBtnSwitchTween; // 0x190
	private UISwitchTween m_rightListSwitchTween; // 0x198
	private UISwitchTween m_bkgSwitchTween; // 0x1a0
	private Tween m_animalIconSwitchTween; // 0x1a8
	private Int32 m_cachedEnterSeqNum; // 0x1b0
	private UIStateFinder m_stateFinder; // 0x1b8
	private UIPageFinder m_pageFinder; // 0x1c8
	private EditStatus m_cachedStatus; // 0x1d8
	private FireworkPlateListView m_plateListView; // 0x1e0
	private FireworkPlateGroupViewStyle m_plateListStyle; // 0x1e8
	private FireworkPlateView m_plateView; // 0x1f0
	private FireworkPlateSelectionView m_plateSelectionView; // 0x1f8
	private FireworkPlateViewStyle m_plateStyle; // 0x200
	private FireworkPlateView m_plateViewMap; // 0x208
	private FireworkPlateSelectionView m_plateSelectionViewMap; // 0x210
	private FireworkPlateViewStyle m_plateStyleMap; // 0x218
	private FireworkPlateFilledListView m_filledPlateListView; // 0x220
	private GameObject m_animalBkg; // 0x228
	private String m_cachedAnimalId; // 0x230
	private String m_cachedAnimalIconId; // 0x238
	private String m_cachedAnimalNameId; // 0x240
	private List`1 m_cachedStageList; // 0x248
	private String m_cachedSelectedStageId; // 0x250
	private StageAdapter m_stageAdapter; // 0x258
	private Tween m_loopTween; // 0x260
	private static DelegateBridge __Hotfix0_get_isStable; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayTweens; // 0x18
	private static DelegateBridge __Hotfix0__ResetPlateStyle; // 0x20
	private static DelegateBridge __Hotfix0__RenderImgMap; // 0x28
	private static DelegateBridge __Hotfix0__RenderFireworkView; // 0x30
	private static DelegateBridge __Hotfix0__RenderAnimalBkg; // 0x38
	private static DelegateBridge __Hotfix0__RenderStageList; // 0x40
	private static DelegateBridge __Hotfix0__RenderAnimalEffectPart; // 0x48
	private static DelegateBridge __Hotfix0__SetPlatePos; // 0x50
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x58
	private static DelegateBridge __Hotfix0_EventOnMapEditBtnClicked; // 0x60
	private static DelegateBridge __Hotfix0_EventOnStageChooseBtnClicked; // 0x68
	private static DelegateBridge __Hotfix0_EventOnStageChooseBgClicked; // 0x70
	private static DelegateBridge __Hotfix0_EventOnAnimalSelectClicked; // 0x78
	private static DelegateBridge __Hotfix0_OnBtnSaveClicked; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean isStable { get; }

	// RVA: 0x2906a30 VA: 0x7594f1ea30
	public Boolean get_isStable() { }
	// RVA: 0x2908050 VA: 0x7594f20050
	public override Void OnValueChanged(FireworkCraftProperty property) { }
	// RVA: 0x29081a0 VA: 0x7594f201a0
	private Void _InitIfNot() { }
	// RVA: 0x29088f4 VA: 0x7594f208f4
	private Void _PlayTweens(FireworkCraftModel model) { }
	// RVA: 0x2908a94 VA: 0x7594f20a94
	private Void _ResetPlateStyle(String currAnimalId) { }
	// RVA: 0x29092d0 VA: 0x7594f212d0
	private Void _RenderImgMap(String stageId, Boolean isMap) { }
	// RVA: 0x2908bd0 VA: 0x7594f20bd0
	private Void _RenderFireworkView(FireworkPlateGroupModel plateGroupModel, String currAnimalId, Boolean isMap) { }
	// RVA: 0x2909570 VA: 0x7594f21570
	private Void _RenderAnimalBkg(String currAnimalId) { }
	// RVA: 0x2908d28 VA: 0x7594f20d28
	private Void _RenderStageList(FireworkCraftModel model, Boolean isMap) { }
	// RVA: 0x2908f98 VA: 0x7594f20f98
	private Void _RenderAnimalEffectPart(FireworkCraftModel model) { }
	// RVA: 0x29093b0 VA: 0x7594f213b0
	private Void _SetPlatePos(EditStatus status, CraftStageInfoModel selectedStage, Boolean isMap) { }
	// RVA: 0x2906b3c VA: 0x7594f1eb3c
	public Void RegisterTutorialGo() { }
	// RVA: 0x29097f4 VA: 0x7594f217f4
	public Void EventOnMapEditBtnClicked() { }
	// RVA: 0x29098f8 VA: 0x7594f218f8
	public Void EventOnStageChooseBtnClicked() { }
	// RVA: 0x2909a08 VA: 0x7594f21a08
	public Void EventOnStageChooseBgClicked() { }
	// RVA: 0x2909af4 VA: 0x7594f21af4
	public Void EventOnAnimalSelectClicked() { }
	// RVA: 0x2909b98 VA: 0x7594f21b98
	public Void OnBtnSaveClicked() { }
	// RVA: 0x2909c3c VA: 0x7594f21c3c
	public Void .ctor() { }
}
```