# SandboxV2CharSelectLogisticsBuffItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgProfession`

- `Graphic _graphicIconBg`

- `Color _colorBgNormal`

- `Color _colorBgFull`

- `Color _colorIconNormal`

- `Color _colorIconFull`

- `Text _txtBuffDesc`

- `SandboxV2LogisticsCharBeanView _charBeanView`

- `Text _txtBuffCount`

- `Color _colorCountDefault`

- `Color _colorCountNormal`

- `Color _colorCountOverflow`

- `CanvasGroup _canvasGroup`

- `Single _fadeDuration`

- `GameObject _panelOverflow`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `CanvasNoBuffSwitchTween m_canvasSwitchTween`

- `Int32 m_cachedBuffBeanCnt`


## Methods

- `Void Render(SandboxV2LogisticsCharSelectBuffViewModel)`

- `Void _InitIfNot(Int32)`

- `Void _RenderBuffBeanRelated(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectLogisticsBuffItem : MonoBehaviour, IHotfixable
{
	private Image _imgProfession; // 0x18
	private Graphic _graphicIconBg; // 0x20
	private Color _colorBgNormal; // 0x28
	private Color _colorBgFull; // 0x38
	private Color _colorIconNormal; // 0x48
	private Color _colorIconFull; // 0x58
	private Text _txtBuffDesc; // 0x68
	private SandboxV2LogisticsCharBeanView _charBeanView; // 0x70
	private Text _txtBuffCount; // 0x78
	private Color _colorCountDefault; // 0x80
	private Color _colorCountNormal; // 0x90
	private Color _colorCountOverflow; // 0xa0
	private CanvasGroup _canvasGroup; // 0xb0
	private Single _fadeDuration; // 0xb8
	private GameObject _panelOverflow; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private Boolean m_isInited; // 0xd8
	private CanvasNoBuffSwitchTween m_canvasSwitchTween; // 0xe0
	private Int32 m_cachedBuffBeanCnt; // 0xe8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderBuffBeanRelated; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2482230 VA: 0x7594a9a230
	public Void Render(SandboxV2LogisticsCharSelectBuffViewModel buffViewModel) { }
	// RVA: 0x24826cc VA: 0x7594a9a6cc
	private Void _InitIfNot(Int32 curBuffCount) { }
	// RVA: 0x24827bc VA: 0x7594a9a7bc
	private Void _RenderBuffBeanRelated(Int32 maxValidCount, Int32 curCount) { }
	// RVA: 0x248294c VA: 0x7594a9a94c
	public Void .ctor() { }
}
```