# CrisisV2StageDetailState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2StageDetailView _view`

- `CrisisV2StageDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void OnEnemyInfoBtnClicked()`

- `Void OnBackroundClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2StageDetailState : PopupFloatState, IHotfixable
{
	private CrisisV2StageDetailView _view; // 0x70
	private CrisisV2StageDetailStateBean m_stateBean; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnemyInfoBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnBackroundClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2be288c VA: 0x75951fa88c
	protected override Void OnEnter() { }
	// RVA: 0x2be2afc VA: 0x75951faafc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2be2970 VA: 0x75951fa970
	private Void _InitIfNot() { }
	// RVA: 0x2be2b64 VA: 0x75951fab64
	public Void OnEnemyInfoBtnClicked() { }
	// RVA: 0x2be2d64 VA: 0x75951fad64
	public Void OnBackroundClicked() { }
	// RVA: 0x2be2e78 VA: 0x75951fae78
	public Void .ctor() { }
	// RVA: 0x2be2f28 VA: 0x75951faf28
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```