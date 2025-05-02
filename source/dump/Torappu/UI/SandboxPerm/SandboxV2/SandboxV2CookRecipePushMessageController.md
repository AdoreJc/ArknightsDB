# SandboxV2CookRecipePushMessageController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `Boolean m_hasInited`


## Methods

- `Void HandleCookRecipeWithToast(List`1)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookRecipePushMessageController : PageSingleComponent, IHotfixable
{
	private String m_topicId; // 0x20
	private Boolean m_hasInited; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_HandleCookRecipeWithToast; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2602c14 VA: 0x7594c1ac14
	protected override Void OnCreate() { }
	// RVA: 0x2602d9c VA: 0x7594c1ad9c
	public Void HandleCookRecipeWithToast(List`1 itemIds) { }
	// RVA: 0x2602c88 VA: 0x7594c1ac88
	private Void _InitIfNot() { }
	// RVA: 0x260313c VA: 0x7594c1b13c
	public Void .ctor() { }
	// RVA: 0x26031ac VA: 0x7594c1b1ac
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```