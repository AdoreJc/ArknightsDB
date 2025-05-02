# NetworkErrorDisplayer

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `State m_state`

- `String m_errorMsg`

- `HotUpdateNetCheckView m_checkPrefab`

- `HotUpdateNetErrorAlert m_alertPrefab`

- `Action m_callback`

- `State m_initState`

- `UIOKDialog m_alertDialog`

- `UIJudgeDialog m_confirmDialog`


## Methods

- `Boolean ReadyToShow()`

- `Void Show()`

- `Boolean IsClosed()`

- `Void _ToState(State)`

- `Void _DoShowErrorAlert()`

- `Void _OnCreateAlertView(RectTransform)`

- `Void _DoShowConfirmDialog()`

- `Void _DoShowNetCheckView()`

- `Void _DoFinishWholeProcess()`

- `Void _OnAlertClosed()`

- `Void _OnNetCheckClicked()`

- `Void _OnCheckConfirmPositive()`

- `Void _OnCheckConfirmNegative()`

- `Void _OnNetCheckClosed()`

- `Void _OnStateChanged(State, State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class NetworkErrorDisplayer : IHotfixable
{
	private State m_state; // 0x10
	private String m_errorMsg; // 0x18
	private HotUpdateNetCheckView m_checkPrefab; // 0x20
	private HotUpdateNetErrorAlert m_alertPrefab; // 0x28
	private Action m_callback; // 0x30
	private State m_initState; // 0x38
	private UIOKDialog m_alertDialog; // 0x40
	private UIJudgeDialog m_confirmDialog; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ReadyToShow; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_IsClosed; // 0x18
	private static DelegateBridge __Hotfix0__ToState; // 0x20
	private static DelegateBridge __Hotfix0__DoShowErrorAlert; // 0x28
	private static DelegateBridge __Hotfix0__OnCreateAlertView; // 0x30
	private static DelegateBridge __Hotfix0__DoShowConfirmDialog; // 0x38
	private static DelegateBridge __Hotfix0__DoShowNetCheckView; // 0x40
	private static DelegateBridge __Hotfix0__DoFinishWholeProcess; // 0x48
	private static DelegateBridge __Hotfix0__OnAlertClosed; // 0x50
	private static DelegateBridge __Hotfix0__OnNetCheckClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnCheckConfirmPositive; // 0x60
	private static DelegateBridge __Hotfix0__OnCheckConfirmNegative; // 0x68
	private static DelegateBridge __Hotfix0__OnNetCheckClosed; // 0x70
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x78


	// RVA: 0x27bf000 VA: 0x7594dd7000
	public Void .ctor(Options options) { }
	// RVA: 0x27c9a6c VA: 0x7594de1a6c
	public Boolean ReadyToShow() { }
	// RVA: 0x27bf0e8 VA: 0x7594dd70e8
	public Void Show() { }
	// RVA: 0x27c8f98 VA: 0x7594de0f98
	public Boolean IsClosed() { }
	// RVA: 0x27c9adc VA: 0x7594de1adc
	private Void _ToState(State target) { }
	// RVA: 0x27c9c30 VA: 0x7594de1c30
	private Void _DoShowErrorAlert() { }
	// RVA: 0x27ca470 VA: 0x7594de2470
	private Void _OnCreateAlertView(RectTransform parent) { }
	// RVA: 0x27c9e80 VA: 0x7594de1e80
	private Void _DoShowConfirmDialog() { }
	// RVA: 0x27ca0d0 VA: 0x7594de20d0
	private Void _DoShowNetCheckView() { }
	// RVA: 0x27ca218 VA: 0x7594de2218
	private Void _DoFinishWholeProcess() { }
	// RVA: 0x27ca5a0 VA: 0x7594de25a0
	private Void _OnAlertClosed() { }
	// RVA: 0x27ca634 VA: 0x7594de2634
	private Void _OnNetCheckClicked() { }
	// RVA: 0x27ca6b8 VA: 0x7594de26b8
	private Void _OnCheckConfirmPositive() { }
	// RVA: 0x27ca74c VA: 0x7594de274c
	private Void _OnCheckConfirmNegative() { }
	// RVA: 0x27ca7e0 VA: 0x7594de27e0
	private Void _OnNetCheckClosed() { }
	// RVA: 0x27ca2ac VA: 0x7594de22ac
	private Void _OnStateChanged(State from, State to) { }
}
```