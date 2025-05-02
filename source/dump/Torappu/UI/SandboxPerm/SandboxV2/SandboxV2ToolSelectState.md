# SandboxV2ToolSelectState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _backRt`

- `SandboxV2ToolSelectView _view`

- `Boolean m_hasInited`

- `SandboxV2ToolSelectStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnToolItemClick(Int32)`

- `Void _EventOnBtnBack()`

- `Void EventOnBtnBack()`

- `Void EventOnBtnClear()`

- `Void EventOnBtnConfirm()`

- `Void EventOnBtnNavWorkbench()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ToolSelectState : PopupFadeState
{
	private RectTransform _backRt; // 0x70
	private SandboxV2ToolSelectView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private SandboxV2ToolSelectStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EventOnToolItemClick; // 0x20
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnBack; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnClear; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnConfirm; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnNavWorkbench; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2622c80 VA: 0x7594c3ac80
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2622ce8 VA: 0x7594c3ace8
	protected override Void OnEnter() { }
	// RVA: 0x2623490 VA: 0x7594c3b490
	protected override Void OnResume() { }
	// RVA: 0x2622e20 VA: 0x7594c3ae20
	private Void _InitIfNot() { }
	// RVA: 0x2623650 VA: 0x7594c3b650
	private Void _EventOnToolItemClick(Int32 toolIdx) { }
	// RVA: 0x262388c VA: 0x7594c3b88c
	private Void _EventOnBtnBack() { }
	// RVA: 0x2623900 VA: 0x7594c3b900
	public Void EventOnBtnBack() { }
	// RVA: 0x2623968 VA: 0x7594c3b968
	public Void EventOnBtnClear() { }
	// RVA: 0x2623b5c VA: 0x7594c3bb5c
	public Void EventOnBtnConfirm() { }
	// RVA: 0x2623c4c VA: 0x7594c3bc4c
	public Void EventOnBtnNavWorkbench() { }
	// RVA: 0x2623fcc VA: 0x7594c3bfcc
	public Void .ctor() { }
	// RVA: 0x2624124 VA: 0x7594c3c124
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x262412c VA: 0x7594c3c12c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```