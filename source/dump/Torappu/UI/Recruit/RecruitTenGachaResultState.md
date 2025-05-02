# RecruitTenGachaResultState

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RecruitTenGachaResultStateBean _stateBean`

- `RecruitTenObject _object`

- `Transform _container`

- `DateTime m_timeParse`


## Methods

- `Void ParseDismiss()`

- `Void DismissOrRemoveTo()`

- `Void _PlayTenGachaPanelShownSE()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitTenGachaResultState : PopupFadeState
{
	private RecruitTenGachaResultStateBean _stateBean; // 0x70
	private RecruitTenObject _object; // 0x78
	private Transform _container; // 0x80
	private List`1 m_objectList; // 0x88
	private const Single TIMEPARSE; // 0x0
	private DateTime m_timeParse; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_ParseDismiss; // 0x10
	private static DelegateBridge __Hotfix0_DismissOrRemoveTo; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnPause; // 0x28
	private static DelegateBridge __Hotfix0__PlayTenGachaPanelShownSE; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x26fb68c VA: 0x7594d1368c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26fb6f4 VA: 0x7594d136f4
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x26fb86c VA: 0x7594d1386c
	public Void ParseDismiss() { }
	// RVA: 0x26fb960 VA: 0x7594d13960
	public Void DismissOrRemoveTo() { }
	// RVA: 0x26fbb0c VA: 0x7594d13b0c
	protected override Void OnEnter() { }
	// RVA: 0x26fbe04 VA: 0x7594d13e04
	protected override Void OnPause() { }
	// RVA: 0x26fbd5c VA: 0x7594d13d5c
	private Void _PlayTenGachaPanelShownSE() { }
	// RVA: 0x26fbf74 VA: 0x7594d13f74
	public Void .ctor() { }
	// RVA: 0x26fc038 VA: 0x7594d14038
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x26fc060 VA: 0x7594d14060
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x26fc068 VA: 0x7594d14068
	private Void <>xLuaBaseProxy_OnPause() { }
}
```