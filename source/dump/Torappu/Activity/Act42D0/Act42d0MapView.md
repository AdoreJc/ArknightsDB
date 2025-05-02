# Act42d0MapView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `RectTransform _areaGroupContainer`

- `GameObject _mapInfoGo`

- `GameObject _nextBtn`

- `GameObject _prevBtn`

- `Text _textAreaTitle`

- `Text _textAreaContent`

- `GameObject _mapInfoBgGo`

- `GameObject _progressInfo`

- `Text _areaCode`

- `Text _stageCode`

- `Text _rateName`

- `Image _areaRateIcon`

- `Button _btnBoss`

- `UIAtlasImage _imgBoss`

- `UIAtlasObject _atlasAsset`

- `GameObject _blankSpace`

- `Single _focusThreshold`

- `Single _focusDuration`

- `UIAnimationLocation _animMapInfo`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Act42D0AreaDifficulty m_cachedDiff`

- `Tween m_mapInfoTween`


## Methods

- `Void _PlayAnimMapInfoIfNecessary(Act42D0AreaDifficulty)`

- `Void _RegisterTutorialGo()`

- `Void _InitIfNot()`

- `Void _RefreshInfo(Act42d0AreaMapViewModel)`

- `Void _RenderProgressOnMap(Act42d0AreaMapViewModel)`

- `Void _RefreshMap(Act42d0AreaMapViewModel)`

- `Void _RefreshBtn(Act42d0AreaMapViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0MapView : DataBinder`1, IHotfixable
{
	private RectTransform _areaGroupContainer; // 0x20
	private GameObject _mapInfoGo; // 0x28
	private GameObject _nextBtn; // 0x30
	private GameObject _prevBtn; // 0x38
	private Text _textAreaTitle; // 0x40
	private Text _textAreaContent; // 0x48
	private GameObject _mapInfoBgGo; // 0x50
	private GameObject _progressInfo; // 0x58
	private Text _areaCode; // 0x60
	private Text _stageCode; // 0x68
	private Text _rateName; // 0x70
	private Image _areaRateIcon; // 0x78
	private Button _btnBoss; // 0x80
	private UIAtlasImage _imgBoss; // 0x88
	private UIAtlasObject _atlasAsset; // 0x90
	private GameObject _blankSpace; // 0x98
	private Act42d0AreaGroupView[] _areaGroupPrefabs; // 0xa0
	private Single _focusThreshold; // 0xa8
	private Single _focusDuration; // 0xac
	private UIAnimationLocation _animMapInfo; // 0xb0
	private Boolean m_isInited; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private Act42D0AreaDifficulty m_cachedDiff; // 0xd8
	private Tween m_mapInfoTween; // 0xe0
	private Dictionary`2 m_areaGroupViewsDict; // 0xe8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnimMapInfoIfNecessary; // 0x8
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RefreshInfo; // 0x20
	private static DelegateBridge __Hotfix0__RenderProgressOnMap; // 0x28
	private static DelegateBridge __Hotfix0__RefreshMap; // 0x30
	private static DelegateBridge __Hotfix0__RefreshBtn; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x321d0c4 VA: 0x75958350c4
	public override Void OnValueChanged(Act42d0AreaMapProperty property) { }
	// RVA: 0x321dc1c VA: 0x7595835c1c
	private Void _PlayAnimMapInfoIfNecessary(Act42D0AreaDifficulty currentDiff) { }
	// RVA: 0x321da64 VA: 0x7595835a64
	private Void _RegisterTutorialGo() { }
	// RVA: 0x321d2bc VA: 0x75958352bc
	private Void _InitIfNot() { }
	// RVA: 0x321d360 VA: 0x7595835360
	private Void _RefreshInfo(Act42d0AreaMapViewModel mapViewModel) { }
	// RVA: 0x321d4e4 VA: 0x75958354e4
	private Void _RenderProgressOnMap(Act42d0AreaMapViewModel viewModel) { }
	// RVA: 0x321d654 VA: 0x7595835654
	private Void _RefreshMap(Act42d0AreaMapViewModel mapViewModel) { }
	// RVA: 0x321d994 VA: 0x7595835994
	private Void _RefreshBtn(Act42d0AreaMapViewModel mapViewModel) { }
	// RVA: 0x321dd2c VA: 0x7595835d2c
	public Void .ctor() { }
}
```