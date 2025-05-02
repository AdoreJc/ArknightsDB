# CharacterInfoPotentialFullState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoPotentialFullView _view`

- `UICommonPageEffectHolder _effectHolder`

- `CharacterInfoPotentialStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _OnClick()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialFullState : UIPopupState, IHotfixable
{
	private CharacterInfoPotentialFullView _view; // 0x60
	private UICommonPageEffectHolder _effectHolder; // 0x68
	private CharacterInfoPotentialStateBean m_stateBean; // 0x70
	private Boolean m_hasInited; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x28
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x30
	private static DelegateBridge __Hotfix0__OnClick; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2d445d8 VA: 0x759535c5d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d44640 VA: 0x759535c640
	protected override Void OnEnter() { }
	// RVA: 0x2d4488c VA: 0x759535c88c
	protected override Void OnResume() { }
	// RVA: 0x2d44948 VA: 0x759535c948
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2d44a98 VA: 0x759535ca98
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2d44be8 VA: 0x759535cbe8
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2d44d60 VA: 0x759535cd60
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2d44e6c VA: 0x759535ce6c
	private Void _OnClick() { }
	// RVA: 0x2d447ac VA: 0x759535c7ac
	private Void _InitIfNot() { }
	// RVA: 0x2d44f64 VA: 0x759535cf64
	public Void .ctor() { }
	// RVA: 0x2d45014 VA: 0x759535d014
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d4501c VA: 0x759535d01c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```