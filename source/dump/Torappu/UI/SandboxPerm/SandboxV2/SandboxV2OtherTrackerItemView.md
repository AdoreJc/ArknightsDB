# SandboxV2OtherTrackerItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgIcon`

- `Image _imgBkg`

- `Image _imgHp`

- `Image _imgShadow`

- `Image _badgeDeco`

- `Image _imgOutline1`

- `Image _imgOutline2`

- `Text _desc`

- `Color _selectedColor`

- `Color _unselectedColor`

- `UIColorGraphic _selectOutline`

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _loopAnim`

- `Boolean m_isInited`

- `Int32 m_cachedEnterSeq`

- `String m_cachedFloatId`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ILoadAsset m_assetLoader`

- `SandboxV2DungeonViewConfig m_cachedDungeonViewConfig`

- `AnimationSwitchTween m_selectTween`

- `Tween m_loopTween`


## Methods

- `Void Render(String, SandboxV2OtherTrackerItemViewModel, Boolean, Int32)`

- `Void _InitIfNot()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2OtherTrackerItemView : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private Image _imgBkg; // 0x20
	private Image _imgHp; // 0x28
	private Image _imgShadow; // 0x30
	private Image _badgeDeco; // 0x38
	private Image _imgOutline1; // 0x40
	private Image _imgOutline2; // 0x48
	private Text _desc; // 0x50
	private Color _selectedColor; // 0x58
	private Color _unselectedColor; // 0x68
	private UIColorGraphic _selectOutline; // 0x78
	private UIAnimationLocation _selectAnim; // 0x80
	private UIAnimationLocation _loopAnim; // 0x90
	private Boolean m_isInited; // 0xa0
	private Int32 m_cachedEnterSeq; // 0xa4
	private String m_cachedFloatId; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private UIStateFinder m_stateFinder; // 0xc0
	private ILoadAsset m_assetLoader; // 0xd0
	private SandboxV2DungeonViewConfig m_cachedDungeonViewConfig; // 0xd8
	private AnimationSwitchTween m_selectTween; // 0xe0
	private Tween m_loopTween; // 0xe8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x255669c VA: 0x7594b6e69c
	public Void Render(String topicId, SandboxV2OtherTrackerItemViewModel viewModel, Boolean isSelected, Int32 enterSeq) { }
	// RVA: 0x2556ba8 VA: 0x7594b6eba8
	private Void _InitIfNot() { }
	// RVA: 0x2556d74 VA: 0x7594b6ed74
	public Void OnClick() { }
	// RVA: 0x2556e7c VA: 0x7594b6ee7c
	public Void .ctor() { }
}
```