# RoguelikeModuleDialogState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _dialogContainer`

- `Boolean m_isInited`

- `UICompDialogMgr m_dialogMgr`

- `IRoguelikeModuleDialogHandler m_dialogHandler`

- `MenuAdapter m_menuAdapter`


## Methods

- `Void _InitIfNot()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeModuleDialogState : UIPopupState, ICompDialogCallBack
{
	private const Single SHOW_TWEEN_DELAY; // 0x0
	private RectTransform _dialogContainer; // 0x60
	private Boolean m_isInited; // 0x68
	private UICompDialogMgr m_dialogMgr; // 0x70
	private IRoguelikeModuleDialogHandler m_dialogHandler; // 0x78
	private MenuAdapter m_menuAdapter; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x40
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2a7fa58 VA: 0x7595097a58
	private Void _InitIfNot() { }
	// RVA: 0x2a7fc24 VA: 0x7595097c24
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a7fc88 VA: 0x7595097c88
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2a7fdcc VA: 0x7595097dcc
	protected override Void OnEnter() { }
	// RVA: 0x2a8015c VA: 0x759509815c
	protected override Void OnResume() { }
	// RVA: 0x2a801f0 VA: 0x75950981f0
	protected override Void OnExit() { }
	// RVA: 0x2a80284 VA: 0x7595098284
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2a803fc VA: 0x75950983fc
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2a80564 VA: 0x7595098564
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2a80648 VA: 0x7595098648
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2a8072c VA: 0x759509872c
	public Void .ctor() { }
	// RVA: 0x2a8079c VA: 0x759509879c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a807a4 VA: 0x75950987a4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a807ac VA: 0x75950987ac
	private Void <>xLuaBaseProxy_OnExit() { }
}
```