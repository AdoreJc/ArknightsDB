# Act25sideStageFog

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Text _textTotalCount`

- `Text _textCurrCount`

- `Color _unlockableColor`

- `Color _lockedColor`

- `GameObject _pnlLocked`

- `GameObject _pnlUnlockable`

- `Button _btnUnlock`

- `GameObject _pnlContent`

- `GameObject _pnlNormal`

- `GameObject _pnlStageLocked`

- `Image _imageIcon`

- `UIAnimationLocation _dismissAnim`

- `String m_cachedStageId`

- `Param m_cachedParam`

- `UIPageFinder m_pageFinder`


## Methods

- `Void EventOnFogClicked()`

- `Void _OnUnlockableFogClicked(Param)`

- `Void _OnFogUnlockItemNotEnough(Param)`

- `Void _OnFogUnlockStageNotPass(Param, StageData)`

- `Void <>xLuaBaseProxy_OnFogDismiss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideStageFog : StageFogOnMapBase
{
	private const String PROGRESS_FORMAT; // 0x0
	private Text _textTotalCount; // 0x28
	private Text _textCurrCount; // 0x30
	private Color _unlockableColor; // 0x38
	private Color _lockedColor; // 0x48
	private GameObject _pnlLocked; // 0x58
	private GameObject _pnlUnlockable; // 0x60
	private Button _btnUnlock; // 0x68
	private GameObject _pnlContent; // 0x70
	private GameObject _pnlNormal; // 0x78
	private GameObject _pnlStageLocked; // 0x80
	private Image _imageIcon; // 0x88
	private UIAnimationLocation _dismissAnim; // 0x90
	private String m_cachedStageId; // 0xa0
	private Param m_cachedParam; // 0xa8
	private UIPageFinder m_pageFinder; // 0xc0
	private static DelegateBridge __Hotfix0_OnFogDismiss; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0_EventOnFogClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnUnlockableFogClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnFogUnlockItemNotEnough; // 0x20
	private static DelegateBridge __Hotfix0__OnFogUnlockStageNotPass; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32723f0 VA: 0x759588a3f0
	protected override Void OnFogDismiss() { }
	// RVA: 0x327249c VA: 0x759588a49c
	public override Void RenderView(Param renderParam) { }
	// RVA: 0x3272844 VA: 0x759588a844
	public Void EventOnFogClicked() { }
	// RVA: 0x3272a00 VA: 0x759588aa00
	private Void _OnUnlockableFogClicked(Param param) { }
	// RVA: 0x3272acc VA: 0x759588aacc
	private Void _OnFogUnlockItemNotEnough(Param param) { }
	// RVA: 0x3272ba0 VA: 0x759588aba0
	private Void _OnFogUnlockStageNotPass(Param param, StageData prevStage) { }
	// RVA: 0x3272c84 VA: 0x759588ac84
	public Void .ctor() { }
	// RVA: 0x3272cf4 VA: 0x759588acf4
	private Void <>xLuaBaseProxy_OnFogDismiss() { }
}
```