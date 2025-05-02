# CrisisV2NodeTipsView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Text _textName`

- `Text _textDesc`

- `Text _textScore`

- `UIAtlasImage _imgBg`

- `GameObject _unavailDeco`

- `GameObject _removeDeco`

- `GameObject _unavailTitleBg`

- `GameObject _removeTitleBg`

- `Color _colorBgUnavail`

- `Color _colorTitleUnavail`

- `Color _colorDescUnavail`

- `Color _colorBgRemove`

- `Color _colorTitleRemove`

- `Color _colorDescRemove`

- `UIAnimationLocation _animSwitch`

- `Single _closeDelay`

- `UIAtlasImage _imgDimension`

- `UIAtlasObject _dimensionAtlas`

- `Boolean m_hasInited`

- `AnimationSwitchTween m_switchTween`

- `Int32 m_cacheTipsSeqNum`

- `Coroutine m_delayCloseCoroutine`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _RenderView(CrisisV2TipsInfo)`

- `Void _CloseTipsAfterDelay()`

- `IEnumerator _CloseTipsCoroutine()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2NodeTipsView : DataBinder`1
{
	private Text _textName; // 0x20
	private Text _textDesc; // 0x28
	private Text _textScore; // 0x30
	private UIAtlasImage _imgBg; // 0x38
	private GameObject _unavailDeco; // 0x40
	private GameObject _removeDeco; // 0x48
	private GameObject _unavailTitleBg; // 0x50
	private GameObject _removeTitleBg; // 0x58
	private Color _colorBgUnavail; // 0x60
	private Color _colorTitleUnavail; // 0x70
	private Color _colorDescUnavail; // 0x80
	private Color _colorBgRemove; // 0x90
	private Color _colorTitleRemove; // 0xa0
	private Color _colorDescRemove; // 0xb0
	private UIAnimationLocation _animSwitch; // 0xc0
	private Single _closeDelay; // 0xd0
	private UIAtlasImage _imgDimension; // 0xd8
	private UIAtlasObject _dimensionAtlas; // 0xe0
	private Boolean m_hasInited; // 0xe8
	private AnimationSwitchTween m_switchTween; // 0xf0
	private Int32 m_cacheTipsSeqNum; // 0xf8
	private Coroutine m_delayCloseCoroutine; // 0x100
	private UIPageFinder m_pageFinder; // 0x108
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderView; // 0x8
	private static DelegateBridge __Hotfix0__CloseTipsAfterDelay; // 0x10
	private static DelegateBridge __Hotfix0__CloseTipsCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c0ced0 VA: 0x7595224ed0
	public override Void OnValueChanged(CrisisV2MapProp property) { }
	// RVA: 0x2c0d0e0 VA: 0x75952250e0
	private Void _RenderView(CrisisV2TipsInfo tipsInfo) { }
	// RVA: 0x2c0d3cc VA: 0x75952253cc
	private Void _CloseTipsAfterDelay() { }
	// RVA: 0x2c0d4b4 VA: 0x75952254b4
	private IEnumerator _CloseTipsCoroutine() { }
	// RVA: 0x2c0cff8 VA: 0x7595224ff8
	private Void _InitIfNot() { }
	// RVA: 0x2c0d588 VA: 0x7595225588
	public Void .ctor() { }
}
```