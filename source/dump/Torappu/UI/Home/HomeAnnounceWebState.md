# HomeAnnounceWebState

**Namespace:** `Torappu.UI.Home`


## Fields

- `LuaUITransEffect _transEffect`


## Methods

- `Void _HandleJumpRecruitMessage(UIWebScheme)`

- `Void _HandleJumpHomeMessage(UIWebScheme)`

- `Void _HandleJumpingShopMessage(UIWebScheme)`

- `Void _HandleJumpingCrisisV2Message(UIWebScheme)`

- `Void _HandleJumpToActivityStageMessage(UIWebScheme)`

- `Void _HandleJumpingCharRepoMessage(UIWebScheme)`

- `Void <>xLuaBaseProxy_OnWebMessage(UIWebScheme)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAnnounceWebState : UIWebWindowState
{
	private LuaUITransEffect _transEffect; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_GetWebWindowType; // 0x8
	private static DelegateBridge __Hotfix0_GetQuery; // 0x10
	private static DelegateBridge __Hotfix0_OnWebMessage; // 0x18
	private static DelegateBridge __Hotfix0__HandleJumpRecruitMessage; // 0x20
	private static DelegateBridge __Hotfix0__HandleJumpHomeMessage; // 0x28
	private static DelegateBridge __Hotfix0__HandleJumpingShopMessage; // 0x30
	private static DelegateBridge __Hotfix0__HandleJumpingCrisisV2Message; // 0x38
	private static DelegateBridge __Hotfix0__HandleJumpToActivityStageMessage; // 0x40
	private static DelegateBridge __Hotfix0__HandleJumpingCharRepoMessage; // 0x48
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x58
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x27e6394 VA: 0x7594dfe394
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27e63f8 VA: 0x7594dfe3f8
	protected override String GetWebWindowType() { }
	// RVA: 0x27e6484 VA: 0x7594dfe484
	protected override Dictionary`2 GetQuery() { }
	// RVA: 0x27e65bc VA: 0x7594dfe5bc
	protected override Void OnWebMessage(UIWebScheme msg) { }
	// RVA: 0x27e69bc VA: 0x7594dfe9bc
	private Void _HandleJumpRecruitMessage(UIWebScheme msg) { }
	// RVA: 0x27e6b4c VA: 0x7594dfeb4c
	private Void _HandleJumpHomeMessage(UIWebScheme msg) { }
	// RVA: 0x27e7178 VA: 0x7594dff178
	private Void _HandleJumpingShopMessage(UIWebScheme msg) { }
	// RVA: 0x27e74d8 VA: 0x7594dff4d8
	private Void _HandleJumpingCrisisV2Message(UIWebScheme msg) { }
	// RVA: 0x27e6f04 VA: 0x7594dfef04
	private Void _HandleJumpToActivityStageMessage(UIWebScheme msg) { }
	// RVA: 0x27e76ec VA: 0x7594dff6ec
	private Void _HandleJumpingCharRepoMessage(UIWebScheme msg) { }
	// RVA: 0x27e785c VA: 0x7594dff85c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x27e7988 VA: 0x7594dff988
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x27e7a94 VA: 0x7594dffa94
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x27e7bc0 VA: 0x7594dffbc0
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x27e7ccc VA: 0x7594dffccc
	public Void .ctor() { }
	// RVA: 0x27e7d3c VA: 0x7594dffd3c
	private Dictionary`2 <>xLuaBaseProxy_GetQuery() { }
	// RVA: 0x27e7d44 VA: 0x7594dffd44
	private Void <>xLuaBaseProxy_OnWebMessage(UIWebScheme P0) { }
	// RVA: 0x27e7d74 VA: 0x7594dffd74
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x27e7d9c VA: 0x7594dffd9c
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
	// RVA: 0x27e7dc4 VA: 0x7594dffdc4
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x27e7dec VA: 0x7594dffdec
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
}
```