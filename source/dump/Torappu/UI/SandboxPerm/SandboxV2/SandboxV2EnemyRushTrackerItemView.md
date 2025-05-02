# SandboxV2EnemyRushTrackerItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgIcon`

- `Image _imgBkg`

- `Image _imgHp`

- `Image _imgShadow`

- `Image _bkgDeco`

- `Image _badgeDeco`

- `Text _desc`

- `Image _outline1`

- `Image _outline2`

- `UIColorGraphic _selectOutline`

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _loopAnim`

- `Boolean m_isInited`

- `String m_cachedEnemeRushId`

- `Int32 m_cachedEnterSeq`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ILoadAsset m_assetLoader`

- `SandboxV2DungeonViewConfig m_cachedDungeonViewConfig`

- `AnimationSwitchTween m_selectTween`

- `Tween m_loopTween`


## Methods

- `Void Render(String, SandboxV2TrackerEnemyRushViewModel, Boolean, Int32)`

- `Void _InitIfNot()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EnemyRushTrackerItemView : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private Image _imgBkg; // 0x20
	private Image _imgHp; // 0x28
	private Image _imgShadow; // 0x30
	private Image _bkgDeco; // 0x38
	private Image _badgeDeco; // 0x40
	private Text _desc; // 0x48
	private Image _outline1; // 0x50
	private Image _outline2; // 0x58
	private UIColorGraphic _selectOutline; // 0x60
	private UIAnimationLocation _selectAnim; // 0x68
	private UIAnimationLocation _loopAnim; // 0x78
	private Boolean m_isInited; // 0x88
	private String m_cachedEnemeRushId; // 0x90
	private Int32 m_cachedEnterSeq; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private UIStateFinder m_stateFinder; // 0xb0
	private ILoadAsset m_assetLoader; // 0xc0
	private SandboxV2DungeonViewConfig m_cachedDungeonViewConfig; // 0xc8
	private AnimationSwitchTween m_selectTween; // 0xd0
	private Tween m_loopTween; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2555718 VA: 0x7594b6d718
	public Void Render(String topicId, SandboxV2TrackerEnemyRushViewModel viewModel, Boolean isSelected, Int32 enterSeq) { }
	// RVA: 0x2555c44 VA: 0x7594b6dc44
	private Void _InitIfNot() { }
	// RVA: 0x2555e10 VA: 0x7594b6de10
	public Void OnClick() { }
	// RVA: 0x2555f18 VA: 0x7594b6df18
	public Void .ctor() { }
}
```