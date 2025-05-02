# AutoMoveScrollViewPagerWrapped

**Namespace:** `Torappu.UI`


## Fields

- `ScrollViewPager _viewPager`

- `Image _objImg`

- `Transform _imgContainer`

- `Toggle _pageToggle`

- `Transform _toggleContainer`

- `Boolean _dontMoveWhenOnlyHaveOneImage`

- `AutoPackSpriteHub m_hub`

- `UIPageFinder m_pageFinder`

- `ILoadAsset m_assetLoader`

- `Single m_switchCountDown`


## Methods

- `Void InitRenderFunc(List`1, String)`

- `Void _EnsureImg(Int32)`

- `Void InitRender(List`1)`

- `Void Awake()`

- `Void OnDestroy()`

- `Void _PageSwitchCallback(Int32)`

- `Void Update()`

- `Void _TryTweenToPage(Int32)`

- `Void _EnsureSelectedPicState(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AutoMoveScrollViewPagerWrapped : MonoBehaviour, IHotfixable
{
	private ScrollViewPager _viewPager; // 0x18
	private Image _objImg; // 0x20
	private Transform _imgContainer; // 0x28
	private Toggle _pageToggle; // 0x30
	private Transform _toggleContainer; // 0x38
	private Boolean _dontMoveWhenOnlyHaveOneImage; // 0x40
	private List`1 m_imageList; // 0x48
	private List`1 m_switchToggles; // 0x50
	private List`1 m_spriteList; // 0x58
	private AutoPackSpriteHub m_hub; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private ILoadAsset m_assetLoader; // 0x78
	private Single m_switchCountDown; // 0x80
	private const Single SWITCH_PAGE_PERIOD; // 0x0
	private static DelegateBridge __Hotfix0_InitRenderFunc; // 0x0
	private static DelegateBridge __Hotfix0__EnsureImg; // 0x8
	private static DelegateBridge __Hotfix0_InitRender; // 0x10
	private static DelegateBridge __Hotfix0_Awake; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0__PageSwitchCallback; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0__TryTweenToPage; // 0x38
	private static DelegateBridge __Hotfix0__EnsureSelectedPicState; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2213ba8 VA: 0x759482bba8
	public Void InitRenderFunc(List`1 spriteList, String hubPath) { }
	// RVA: 0x22140dc VA: 0x759482c0dc
	private Void _EnsureImg(Int32 indexI) { }
	// RVA: 0x2214314 VA: 0x759482c314
	public Void InitRender(List`1 spriteList) { }
	// RVA: 0x2214684 VA: 0x759482c684
	private Void Awake() { }
	// RVA: 0x2214790 VA: 0x759482c790
	private Void OnDestroy() { }
	// RVA: 0x2213fec VA: 0x759482bfec
	private Void _PageSwitchCallback(Int32 index) { }
	// RVA: 0x2214934 VA: 0x759482c934
	private Void Update() { }
	// RVA: 0x2213f4c VA: 0x759482bf4c
	private Void _TryTweenToPage(Int32 pageIndex) { }
	// RVA: 0x221489c VA: 0x759482c89c
	private Void _EnsureSelectedPicState(Int32 pageIndex) { }
	// RVA: 0x2214a48 VA: 0x759482ca48
	public Void .ctor() { }
}
```