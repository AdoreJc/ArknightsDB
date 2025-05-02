# SandboxV2RiftTeamSelectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _background`

- `CanvasGroup _backgroundCanvasGroup`

- `Single _backgroundFadeTime`

- `Image _teamBigIcon`

- `Text _teamName`

- `GameObject _teamLevelObject`

- `Text _teamLevel`

- `Text _teamDesc`

- `TwoStateToggle _teamBuffDescToggle`

- `SimpleLayoutContent _teamBuffDescContent`

- `GameObject _teamBuffDescTipObject`

- `CanvasGroup _teamBuffDescCanvasGroup`

- `Single _teamBuffDescFadeTime`

- `SimpleLayoutContent _teamButtonContent`

- `RectTransform _backPressArea`

- `UIAnimationLocation _titleAnim`

- `Boolean m_hasInited`

- `SandboxV2RiftTeamSelectViewModel m_cachedViewModel`

- `TeamDescAdapter m_teamDescAdapter`

- `TeamButtonAdapter m_teamButtonAdapter`

- `UISwitchTween m_titleTween`

- `UISwitchTween m_buffDescTween`

- `UISwitchTween m_backgroundTween`

- `String m_cachedBgId`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void _RenderBgPart()`

- `Boolean _HasBgChanged()`

- `Void _RenderTitlePart()`

- `Void _RenderDescPart()`

- `Void OnBackClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftTeamSelectView : DataBinder`1
{
	private const String NO_TEAM_LEVEL_TEXT; // 0x0
	private Image _background; // 0x20
	private CanvasGroup _backgroundCanvasGroup; // 0x28
	private Single _backgroundFadeTime; // 0x30
	private Image _teamBigIcon; // 0x38
	private Text _teamName; // 0x40
	private GameObject _teamLevelObject; // 0x48
	private Text _teamLevel; // 0x50
	private Text _teamDesc; // 0x58
	private TwoStateToggle _teamBuffDescToggle; // 0x60
	private SimpleLayoutContent _teamBuffDescContent; // 0x68
	private GameObject _teamBuffDescTipObject; // 0x70
	private CanvasGroup _teamBuffDescCanvasGroup; // 0x78
	private Single _teamBuffDescFadeTime; // 0x80
	private SimpleLayoutContent _teamButtonContent; // 0x88
	private RectTransform _backPressArea; // 0x90
	private UIAnimationLocation _titleAnim; // 0x98
	private Boolean m_hasInited; // 0xa8
	private SandboxV2RiftTeamSelectViewModel m_cachedViewModel; // 0xb0
	private List`1 m_cachedTeamDesc; // 0xb8
	private TeamDescAdapter m_teamDescAdapter; // 0xc0
	private TeamButtonAdapter m_teamButtonAdapter; // 0xc8
	private UISwitchTween m_titleTween; // 0xd0
	private UISwitchTween m_buffDescTween; // 0xd8
	private UISwitchTween m_backgroundTween; // 0xe0
	private String m_cachedBgId; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf0
	private UIStateFinder m_stateFinder; // 0x100
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderBgPart; // 0x10
	private static DelegateBridge __Hotfix0__HasBgChanged; // 0x18
	private static DelegateBridge __Hotfix0__RenderTitlePart; // 0x20
	private static DelegateBridge __Hotfix0__RenderDescPart; // 0x28
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x25ffbc8 VA: 0x7594c17bc8
	public override Void OnValueChanged(SandboxV2RiftTeamSelectProperty property) { }
	// RVA: 0x25ffd40 VA: 0x7594c17d40
	private Void _InitIfNot() { }
	// RVA: 0x260050c VA: 0x7594c1850c
	private Void _RenderBgPart() { }
	// RVA: 0x260040c VA: 0x7594c1840c
	private Boolean _HasBgChanged() { }
	// RVA: 0x2600038 VA: 0x7594c18038
	private Void _RenderTitlePart() { }
	// RVA: 0x2600298 VA: 0x7594c18298
	private Void _RenderDescPart() { }
	// RVA: 0x26007a8 VA: 0x7594c187a8
	public Void OnBackClicked() { }
	// RVA: 0x260084c VA: 0x7594c1884c
	public Void .ctor() { }
}
```