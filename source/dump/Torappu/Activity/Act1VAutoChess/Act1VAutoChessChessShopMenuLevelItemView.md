# Act1VAutoChessChessShopMenuLevelItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _imgShopLevelIcon`

- `Text _txtShopLevel`

- `GameObject _objDiyCharInfo`

- `Text _txtCurDiyCharCount`

- `GameObject _objSplitLine`

- `UIAnimationLocation _animationLocationClickTips`

- `CanvasGroup _canvasHasInfo`

- `CanvasGroup _canvasNoInfo`

- `Transform _trackPointContainer`

- `GameObject _objNewPrefab`

- `Int32 m_cachedShopLevel`

- `Int32 m_cachedIndex`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `Tween m_tween`

- `FadeSwitchTween m_hasInfoTween`

- `FadeSwitchTween m_noInfoTween`

- `GameObject m_trackPointObj`


## Methods

- `Void Render(Act1VAutoChessChessShopMenuLevelItemViewModel)`

- `Void _InitIfNot()`

- `Void _RenderItemView(Act1VAutoChessChessShopMenuLevelItemViewModel)`

- `Void _ShowClickTips()`

- `Void _ResetClickTips()`

- `Void _SetCharTabShowTrackPoint(Boolean)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopMenuLevelItemView : MonoBehaviour, IHotfixable
{
	private Image _imgShopLevelIcon; // 0x18
	private Text _txtShopLevel; // 0x20
	private GameObject _objDiyCharInfo; // 0x28
	private Text _txtCurDiyCharCount; // 0x30
	private GameObject _objSplitLine; // 0x38
	private UIAnimationLocation _animationLocationClickTips; // 0x40
	private CanvasGroup _canvasHasInfo; // 0x50
	private CanvasGroup _canvasNoInfo; // 0x58
	private Transform _trackPointContainer; // 0x60
	private GameObject _objNewPrefab; // 0x68
	private Int32 m_cachedShopLevel; // 0x70
	private Int32 m_cachedIndex; // 0x74
	private Boolean m_hasInited; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private UIStateFinder m_stateFinder; // 0x90
	private Tween m_tween; // 0xa0
	private FadeSwitchTween m_hasInfoTween; // 0xa8
	private FadeSwitchTween m_noInfoTween; // 0xb0
	private GameObject m_trackPointObj; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderItemView; // 0x10
	private static DelegateBridge __Hotfix0__ShowClickTips; // 0x18
	private static DelegateBridge __Hotfix0__ResetClickTips; // 0x20
	private static DelegateBridge __Hotfix0__SetCharTabShowTrackPoint; // 0x28
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x33157b0 VA: 0x759592d7b0
	public Void Render(Act1VAutoChessChessShopMenuLevelItemViewModel itemViewModel) { }
	// RVA: 0x33158a8 VA: 0x759592d8a8
	private Void _InitIfNot() { }
	// RVA: 0x3315a00 VA: 0x759592da00
	private Void _RenderItemView(Act1VAutoChessChessShopMenuLevelItemViewModel itemViewModel) { }
	// RVA: 0x3315e60 VA: 0x759592de60
	private Void _ShowClickTips() { }
	// RVA: 0x3315c64 VA: 0x759592dc64
	private Void _ResetClickTips() { }
	// RVA: 0x3315cf0 VA: 0x759592dcf0
	private Void _SetCharTabShowTrackPoint(Boolean isShow) { }
	// RVA: 0x3315f50 VA: 0x759592df50
	public Void OnItemClick() { }
	// RVA: 0x3316078 VA: 0x759592e078
	public Void .ctor() { }
}
```