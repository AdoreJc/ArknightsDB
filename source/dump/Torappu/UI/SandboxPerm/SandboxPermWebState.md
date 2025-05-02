# SandboxPermWebState

**Namespace:** `Torappu.UI.SandboxPerm`


## Fields

- `Image _blurImage`

- `CanvasGroup _rootView`

- `Boolean m_isInited`

- `String m_topicId`


## Methods

- `Void _InitIfNot()`

- `Void _CleanBlurShot()`

- `Void _SetupBlurShot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm
public class SandboxPermWebState : UIWebWindowState
{
	public const Single FADE_DURATION; // 0x0
	private Image _blurImage; // 0x78
	private CanvasGroup _rootView; // 0x80
	private Boolean m_isInited; // 0x88
	private String m_topicId; // 0x90
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_GetWebWindowType; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__CleanBlurShot; // 0x40
	private static DelegateBridge __Hotfix0__SetupBlurShot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x247f8f4 VA: 0x7594a978f4
	protected override Void OnEnter() { }
	// RVA: 0x247faa4 VA: 0x7594a97aa4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x247fb08 VA: 0x7594a97b08
	protected override String GetWebWindowType() { }
	// RVA: 0x247fc10 VA: 0x7594a97c10
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x247fd88 VA: 0x7594a97d88
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x248000c VA: 0x7594a9800c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2480184 VA: 0x7594a98184
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x247f968 VA: 0x7594a97968
	protected Void _InitIfNot() { }
	// RVA: 0x247feb8 VA: 0x7594a97eb8
	private Void _CleanBlurShot() { }
	// RVA: 0x24802b4 VA: 0x7594a982b4
	private Void _SetupBlurShot() { }
	// RVA: 0x2480368 VA: 0x7594a98368
	public Void .ctor() { }
	// RVA: 0x24803d8 VA: 0x7594a983d8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x24803e0 VA: 0x7594a983e0
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2480408 VA: 0x7594a98408
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
	// RVA: 0x2480430 VA: 0x7594a98430
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2480458 VA: 0x7594a98458
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
}
```