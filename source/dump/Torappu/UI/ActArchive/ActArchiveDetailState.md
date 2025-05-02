# ActArchiveDetailState

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `CanvasGroup _canvas`

- `ActArchiveStateBean _stateBean`

- `RectTransform _backBtn`

- `ActArchiveCompDataBinder _compBinder`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnBackClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveDetailState : PopupFloatState
{
	private CanvasGroup _canvas; // 0x70
	private ActArchiveStateBean _stateBean; // 0x78
	private RectTransform _backBtn; // 0x80
	private ActArchiveCompDataBinder _compBinder; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x30
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x30910c4 VA: 0x75956a90c4
	private Void _InitIfNot() { }
	// RVA: 0x30911cc VA: 0x75956a91cc
	protected override Void OnEnter() { }
	// RVA: 0x30912a0 VA: 0x75956a92a0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3091308 VA: 0x75956a9308
	public Void OnBackClick() { }
	// RVA: 0x30914f4 VA: 0x75956a94f4
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x309166c VA: 0x75956a966c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x30917e4 VA: 0x75956a97e4
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x3091930 VA: 0x75956a9930
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x3091a68 VA: 0x75956a9a68
	public Void .ctor() { }
	// RVA: 0x3091ad8 VA: 0x75956a9ad8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3091ae0 VA: 0x75956a9ae0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x3091b08 VA: 0x75956a9b08
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x3091b30 VA: 0x75956a9b30
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x3091b58 VA: 0x75956a9b58
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```