# CarvingMainRoundEndState

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainRoundEndView _view`

- `Boolean m_inited`

- `Int32 m_confirmDialogInstId`

- `Int32 m_settleDialogInstId`

- `String m_actId`

- `CarvingMainRoundEndStateBean m_stateBean`


## Methods

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void OnClickStartNewRoundBtn()`

- `Void OnClickEndClassBtn()`

- `Void _InitIfNot()`

- `Void _ToNextRound()`

- `Void _ShowConfirmDialog()`

- `Void _OnSettleProceed(CarvingSettleResponse)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainRoundEndState : PopupFadeState, ICompDialogCallBack, IHotfixable
{
	private CarvingMainRoundEndView _view; // 0x70
	private Boolean m_inited; // 0x78
	private Int32 m_confirmDialogInstId; // 0x7c
	private Int32 m_settleDialogInstId; // 0x80
	private String m_actId; // 0x88
	private CarvingMainRoundEndStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x8
	private static DelegateBridge __Hotfix0_OnClickStartNewRoundBtn; // 0x10
	private static DelegateBridge __Hotfix0_OnClickEndClassBtn; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__ToNextRound; // 0x38
	private static DelegateBridge __Hotfix0__ShowConfirmDialog; // 0x40
	private static DelegateBridge __Hotfix0__OnSettleProceed; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2db4608 VA: 0x75953cc608
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2db4670 VA: 0x75953cc670
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2db4a10 VA: 0x75953cca10
	public Void OnClickStartNewRoundBtn() { }
	// RVA: 0x2db4f80 VA: 0x75953ccf80
	public Void OnClickEndClassBtn() { }
	// RVA: 0x2db51f4 VA: 0x75953cd1f4
	protected override Void OnEnter() { }
	// RVA: 0x2db5504 VA: 0x75953cd504
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2db538c VA: 0x75953cd38c
	private Void _InitIfNot() { }
	// RVA: 0x2db4728 VA: 0x75953cc728
	private Void _ToNextRound() { }
	// RVA: 0x2db4c28 VA: 0x75953ccc28
	private Void _ShowConfirmDialog() { }
	// RVA: 0x2db56a0 VA: 0x75953cd6a0
	private Void _OnSettleProceed(CarvingSettleResponse response) { }
	// RVA: 0x2db58c0 VA: 0x75953cd8c0
	public Void .ctor() { }
	// RVA: 0x2db5a18 VA: 0x75953cda18
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2db5a40 VA: 0x75953cda40
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2db5a48 VA: 0x75953cda48
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
}
```