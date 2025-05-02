# SandboxV2EventView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _icon`

- `Image _nodeIcon`

- `Text _title`

- `SandboxV2EventTypeWriter _textWriter`

- `ScrollRect _scrollRect`

- `Color _textLight`

- `Color _textDark`

- `Text _choiceTitle`

- `Text _choiceDesc`

- `GameObject _panelChoiceDesc`

- `UILayoutDimensionListener _contentDimensionListener`

- `SimpleLayoutContent _choiceContent`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _exitAnim`

- `ScrollRect _tutorialScrollRectRight`

- `Int32 m_animSeq`

- `Int32 m_enterSeq`

- `Boolean m_isInited`

- `Boolean m_playAnim`

- `Boolean m_isEnter`

- `Tween m_bottomTween`

- `Adapter m_adapter`

- `String m_cachedNodeId`

- `String m_cachedEventId`

- `String m_cachedSceneId`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `Coroutine m_animCoroutine`

- `AnimEnterTween m_enterTween`

- `SandboxV2EventViewModel m_cachedViewModel`

- `UILayoutDimensionListener m_dimensionListener`

- `Boolean m_isLocked`


## Methods

- `Void _PlayAnim()`

- `Void _RenderImmediately(Boolean)`

- `Void _InitIfNot()`

- `IEnumerator _AnimCoroutine()`

- `Void _LoadIcon(String, String, ILoadAsset)`

- `Void _LoadNodeTypeIcon(String, String, ILoadAsset)`

- `Void _OnPostLayout()`

- `Void OnBackGroundPress()`

- `IEnumerator _TutorialOnly_TryRaiseAVGSignal()`

- `Void _TutorialOnly_RegisterTutorialGo()`

- `Void <_OnPostLayout>b__42_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EventView : DataBinder`1
{
	private const Single BOTTOM_TWEEN_DURATION; // 0x0
	private Image _icon; // 0x20
	private Image _nodeIcon; // 0x28
	private Text _title; // 0x30
	private SandboxV2EventTypeWriter _textWriter; // 0x38
	private ScrollRect _scrollRect; // 0x40
	private Color _textLight; // 0x48
	private Color _textDark; // 0x58
	private Text _choiceTitle; // 0x68
	private Text _choiceDesc; // 0x70
	private GameObject _panelChoiceDesc; // 0x78
	private UILayoutDimensionListener _contentDimensionListener; // 0x80
	private SimpleLayoutContent _choiceContent; // 0x88
	private UIAnimationLocation _enterAnim; // 0x90
	private UIAnimationLocation _exitAnim; // 0xa0
	private ScrollRect _tutorialScrollRectRight; // 0xb0
	private Int32 m_animSeq; // 0xb8
	private Int32 m_enterSeq; // 0xbc
	private Boolean m_isInited; // 0xc0
	private Boolean m_playAnim; // 0xc1
	private Boolean m_isEnter; // 0xc2
	private Tween m_bottomTween; // 0xc8
	private Adapter m_adapter; // 0xd0
	private String m_cachedNodeId; // 0xd8
	private String m_cachedEventId; // 0xe0
	private String m_cachedSceneId; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf0
	private UIStateFinder m_stateFinder; // 0x100
	private Coroutine m_animCoroutine; // 0x110
	private AnimEnterTween m_enterTween; // 0x118
	private SandboxV2EventViewModel m_cachedViewModel; // 0x120
	private UILayoutDimensionListener m_dimensionListener; // 0x128
	private Boolean m_isLocked; // 0x130
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0__RenderImmediately; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__AnimCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__LoadIcon; // 0x28
	private static DelegateBridge __Hotfix0__LoadNodeTypeIcon; // 0x30
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0x38
	private static DelegateBridge __Hotfix0_OnBackGroundPress; // 0x40
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignal; // 0x48
	private static DelegateBridge __Hotfix0__TutorialOnly_RegisterTutorialGo; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x255ef54 VA: 0x7594b76f54
	public override Void OnValueChanged(SandboxV2EventProperty property) { }
	// RVA: 0x255f5e0 VA: 0x7594b775e0
	private Void _PlayAnim() { }
	// RVA: 0x255f6ac VA: 0x7594b776ac
	private Void _RenderImmediately(Boolean isSameScene) { }
	// RVA: 0x255f410 VA: 0x7594b77410
	private Void _InitIfNot() { }
	// RVA: 0x255f95c VA: 0x7594b7795c
	private IEnumerator _AnimCoroutine() { }
	// RVA: 0x255f794 VA: 0x7594b77794
	private Void _LoadIcon(String topicId, String iconId, ILoadAsset assetLoader) { }
	// RVA: 0x255f878 VA: 0x7594b77878
	private Void _LoadNodeTypeIcon(String topicId, String nodeIconId, ILoadAsset assetLoader) { }
	// RVA: 0x255fb58 VA: 0x7594b77b58
	private Void _OnPostLayout() { }
	// RVA: 0x255fdb0 VA: 0x7594b77db0
	public Void OnBackGroundPress() { }
	// RVA: 0x255ff2c VA: 0x7594b77f2c
	private IEnumerator _TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x2560000 VA: 0x7594b78000
	private Void _TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x256025c VA: 0x7594b7825c
	public Void .ctor() { }
	// RVA: 0x25602ec VA: 0x7594b782ec
	private Void <_OnPostLayout>b__42_0() { }
}
```