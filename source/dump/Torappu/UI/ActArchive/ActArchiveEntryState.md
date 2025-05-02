# ActArchiveEntryState

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `CanvasGroup _canvas`

- `RectTransform _topMenuHolder`

- `ActArchiveStateBean _stateBean`

- `ActArchiveCompDataBinder _compBinder`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void PageOnlyNotifyBeforePageHide(Boolean)`

- `Void <_InitIfNot>b__5_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveEntryState : PopupFloatState
{
	private CanvasGroup _canvas; // 0x70
	private RectTransform _topMenuHolder; // 0x78
	private ActArchiveStateBean _stateBean; // 0x80
	private ActArchiveCompDataBinder _compBinder; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_PageOnlyNotifyBeforePageHide; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x30
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3091f50 VA: 0x75956a9f50
	private Void _InitIfNot() { }
	// RVA: 0x30920c0 VA: 0x75956aa0c0
	protected override Void OnEnter() { }
	// RVA: 0x3092194 VA: 0x75956aa194
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30921fc VA: 0x75956aa1fc
	public Void PageOnlyNotifyBeforePageHide(Boolean isPageIntoStack) { }
	// RVA: 0x3092288 VA: 0x75956aa288
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3092400 VA: 0x75956aa400
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x3092578 VA: 0x75956aa578
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x30926c4 VA: 0x75956aa6c4
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x30927ec VA: 0x75956aa7ec
	public Void .ctor() { }
	// RVA: 0x309285c VA: 0x75956aa85c
	private Void <_InitIfNot>b__5_0() { }
	// RVA: 0x3092898 VA: 0x75956aa898
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30928a0 VA: 0x75956aa8a0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x30928c8 VA: 0x75956aa8c8
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x30928f0 VA: 0x75956aa8f0
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x3092918 VA: 0x75956aa918
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```