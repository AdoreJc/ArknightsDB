# HandBookInfoStageDetailState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookInfoStageDetailView _view`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `Boolean m_isInited`


## Methods

- `Void OnStartBattleClick()`

- `Void OnOpenEnemy()`

- `Void _InitIfNot()`

- `Void <RegisterToDataListener>b__5_0(IStateBean)`

- `Void <_InitIfNot>b__12_0(GameObject)`

- `Void <_InitIfNot>b__12_1()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStageDetailState : UIPopupState
{
	private HandBookInfoStageDetailView _view; // 0x60
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0_OnStartBattleClick; // 0x0
	private static DelegateBridge __Hotfix0_OnOpenEnemy; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x30
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2e9fc4c VA: 0x75954b7c4c
	public Void OnStartBattleClick() { }
	// RVA: 0x2e9feb0 VA: 0x75954b7eb0
	public Void OnOpenEnemy() { }
	// RVA: 0x2ea0030 VA: 0x75954b8030
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ea01a8 VA: 0x75954b81a8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ea020c VA: 0x75954b820c
	protected override Void OnEnter() { }
	// RVA: 0x2ea0430 VA: 0x75954b8430
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2ea05a8 VA: 0x75954b85a8
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2ea06b4 VA: 0x75954b86b4
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2ea082c VA: 0x75954b882c
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2ea0280 VA: 0x75954b8280
	private Void _InitIfNot() { }
	// RVA: 0x2ea0938 VA: 0x75954b8938
	public Void .ctor() { }
	// RVA: 0x2ea09a8 VA: 0x75954b89a8
	private Void <RegisterToDataListener>b__5_0(IStateBean stateBean) { }
	// RVA: 0x2ea0bd0 VA: 0x75954b8bd0
	private Void <_InitIfNot>b__12_0(GameObject inst) { }
	// RVA: 0x2ea0ccc VA: 0x75954b8ccc
	private Void <_InitIfNot>b__12_1() { }
	// RVA: 0x2ea0cec VA: 0x75954b8cec
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2ea0cf4 VA: 0x75954b8cf4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```