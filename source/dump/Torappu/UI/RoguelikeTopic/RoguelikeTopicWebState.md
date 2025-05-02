# RoguelikeTopicWebState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _blurImage`

- `CanvasGroup _rootView`


## Methods

- `Void _CleanBlurShot()`

- `Void _SetupBlurShot()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicWebState : UIWebWindowState
{
	public const Single FADE_DURATION; // 0x0
	private Image _blurImage; // 0x78
	private CanvasGroup _rootView; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_GetWebWindowType; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x28
	private static DelegateBridge __Hotfix0__CleanBlurShot; // 0x30
	private static DelegateBridge __Hotfix0__SetupBlurShot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x267bde4 VA: 0x7594c93de4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x267be48 VA: 0x7594c93e48
	protected override String GetWebWindowType() { }
	// RVA: 0x267bfd0 VA: 0x7594c93fd0
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x267c148 VA: 0x7594c94148
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x267c3cc VA: 0x7594c943cc
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x267c544 VA: 0x7594c94544
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x267c278 VA: 0x7594c94278
	private Void _CleanBlurShot() { }
	// RVA: 0x267c674 VA: 0x7594c94674
	private Void _SetupBlurShot() { }
	// RVA: 0x267c728 VA: 0x7594c94728
	public Void .ctor() { }
	// RVA: 0x267c798 VA: 0x7594c94798
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x267c7c0 VA: 0x7594c947c0
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
	// RVA: 0x267c7e8 VA: 0x7594c947e8
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x267c810 VA: 0x7594c94810
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
}
```