# SandboxV2NodeFloatView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgBkg`

- `Image _imgFrame`

- `Image _imgHp`

- `Image _imgStack`

- `Image _imgShadow`

- `Image _imgOutline1`

- `Image _imgOutline2`

- `UIColorGraphic _selectionOutline`

- `GameObject _pnlEnemyRush`

- `Int64 _loopInterval`

- `Single _tweenDuration`

- `CanvasGroup _asyncShowHandler`

- `UIAnimationLocation _showAnim`

- `UIAnimationLocation _selectionLoopAnim`

- `CanvasGroup _canvasSelection`

- `CanvasGroup _canvasShow`

- `Boolean m_inited`

- `String m_cachedTopicId`

- `String m_cachedNodeId`

- `SandboxV2DungeonViewConfig m_cachedDungeonViewConfig`

- `UIPageFinder m_pageFinder`

- `TransSwitchTween m_switchTween`

- `SandboxV2EnterAnimTween m_showTween`

- `SelectionSwitchTween m_selectionTween`

- `CountDownTask m_countDownTask`

- `SeqNumChecker m_dungeonChangeChecker`

- `SeqNumChecker m_floatSelectionChecker`

- `SeqNumChecker m_enterAnimChecker`

- `Boolean m_cachedFastMode`

- `Boolean m_cachedPlayedEnterAnim`

- `SandboxV2DungeonFloatViewModel m_currFloatViewModel`

- `SandboxV2DungeonFloatGroupViewModel m_cachedFloatGroupViewModel`


## Methods

- `Void Update()`

- `SandboxV2DungeonFloatViewModel _FetchNextFloatViewModel()`

- `SandboxV2DungeonFloatViewModel _FetchFirstNewFloatViewModel()`

- `Boolean _CheckCurrFloatViewModelExists()`

- `Void _StartCountdownTask()`

- `Void _ClearCountdownTask()`

- `Void _InitIfNot()`

- `Void _RenderBuffer(Int32, SandboxV2DungeonFloatViewModel)`

- `Void _RenderCurr()`

- `Void _RenderNext(SandboxV2DungeonFloatViewModel)`

- `Void _Render(SandboxV2DungeonFloatGroupViewModel)`

- `Void _SetShowStatus(Boolean, Boolean, Single)`

- `Void AsyncSetData(RenderParam)`

- `Void OnClick()`

- `Void AsyncShow()`

- `Void <_InitIfNot>b__44_0(Boolean)`

- `Void <_InitIfNot>b__44_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeFloatView : MonoBehaviour, IAsyncDataView`1, IAsyncShowEffect, IHotfixable
{
	private Image[] _imgDeco; // 0x18
	private Image[] _imgBadge; // 0x20
	private Image _imgBkg; // 0x28
	private Image _imgFrame; // 0x30
	private Image[] _imgIcon; // 0x38
	private Image _imgHp; // 0x40
	private Image _imgStack; // 0x48
	private Image _imgShadow; // 0x50
	private Image _imgOutline1; // 0x58
	private Image _imgOutline2; // 0x60
	private UIColorGraphic _selectionOutline; // 0x68
	private GameObject _pnlEnemyRush; // 0x70
	private Int64 _loopInterval; // 0x78
	private Single _tweenDuration; // 0x80
	private CanvasGroup _asyncShowHandler; // 0x88
	private UIAnimationLocation _showAnim; // 0x90
	private UIAnimationLocation _selectionLoopAnim; // 0xa0
	private CanvasGroup _canvasSelection; // 0xb0
	private CanvasGroup _canvasShow; // 0xb8
	private Boolean m_inited; // 0xc0
	private String m_cachedTopicId; // 0xc8
	private String m_cachedNodeId; // 0xd0
	private SandboxV2DungeonViewConfig m_cachedDungeonViewConfig; // 0xd8
	private UIPageFinder m_pageFinder; // 0xe0
	private TransSwitchTween m_switchTween; // 0xf0
	private SandboxV2EnterAnimTween m_showTween; // 0xf8
	private SelectionSwitchTween m_selectionTween; // 0x100
	private CountDownTask m_countDownTask; // 0x108
	private SeqNumChecker m_dungeonChangeChecker; // 0x110
	private SeqNumChecker m_floatSelectionChecker; // 0x120
	private SeqNumChecker m_enterAnimChecker; // 0x130
	private Boolean m_cachedFastMode; // 0x140
	private Boolean m_cachedPlayedEnterAnim; // 0x141
	private SandboxV2DungeonFloatViewModel m_currFloatViewModel; // 0x148
	private SandboxV2DungeonFloatGroupViewModel m_cachedFloatGroupViewModel; // 0x150
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0__FetchNextFloatViewModel; // 0x8
	private static DelegateBridge __Hotfix0__FetchFirstNewFloatViewModel; // 0x10
	private static DelegateBridge __Hotfix0__CheckCurrFloatViewModelExists; // 0x18
	private static DelegateBridge __Hotfix0__StartCountdownTask; // 0x20
	private static DelegateBridge __Hotfix0__ClearCountdownTask; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderBuffer; // 0x38
	private static DelegateBridge __Hotfix0__RenderCurr; // 0x40
	private static DelegateBridge __Hotfix0__RenderNext; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0__SetShowStatus; // 0x58
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x60
	private static DelegateBridge __Hotfix0_OnClick; // 0x68
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2560d94 VA: 0x7594b78d94
	private Void Update() { }
	// RVA: 0x2560e10 VA: 0x7594b78e10
	private SandboxV2DungeonFloatViewModel _FetchNextFloatViewModel() { }
	// RVA: 0x2560f74 VA: 0x7594b78f74
	private SandboxV2DungeonFloatViewModel _FetchFirstNewFloatViewModel() { }
	// RVA: 0x256108c VA: 0x7594b7908c
	private Boolean _CheckCurrFloatViewModelExists() { }
	// RVA: 0x25611ac VA: 0x7594b791ac
	private Void _StartCountdownTask() { }
	// RVA: 0x2561260 VA: 0x7594b79260
	private Void _ClearCountdownTask() { }
	// RVA: 0x25612dc VA: 0x7594b792dc
	private Void _InitIfNot() { }
	// RVA: 0x25615b8 VA: 0x7594b795b8
	private Void _RenderBuffer(Int32 bufferIndex, SandboxV2DungeonFloatViewModel floatViewModel) { }
	// RVA: 0x25619cc VA: 0x7594b799cc
	private Void _RenderCurr() { }
	// RVA: 0x2561a68 VA: 0x7594b79a68
	private Void _RenderNext(SandboxV2DungeonFloatViewModel nextFloatViewModel) { }
	// RVA: 0x2561b78 VA: 0x7594b79b78
	private Void _Render(SandboxV2DungeonFloatGroupViewModel floatGroup) { }
	// RVA: 0x2561c64 VA: 0x7594b79c64
	private Void _SetShowStatus(Boolean isShow, Boolean fastMode, Single delay) { }
	// RVA: 0x2561d40 VA: 0x7594b79d40
	public Void AsyncSetData(RenderParam param) { }
	// RVA: 0x25621d4 VA: 0x7594b7a1d4
	public Void OnClick() { }
	// RVA: 0x2562300 VA: 0x7594b7a300
	public Void AsyncShow() { }
	// RVA: 0x25623dc VA: 0x7594b7a3dc
	public Void .ctor() { }
	// RVA: 0x25624c4 VA: 0x7594b7a4c4
	private Void <_InitIfNot>b__44_0(Boolean show) { }
	// RVA: 0x256255c VA: 0x7594b7a55c
	private Void <_InitIfNot>b__44_1() { }
}
```