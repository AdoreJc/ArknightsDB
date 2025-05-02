# UIArchitectureBaseView

**Namespace:** `Torappu.Building.UI`


## Fields

- `T m_arg`

- `Action m_onCancel`

- `CanvasGroup m_canvasGroup`

- `Boolean m_isShowing`


## Properties

- `T arg`

- `Boolean isShowing`


## Methods

- `Void Setup(T, Func`1, Action)`

- `T get_arg()`

- `Void OnCancelPressed()`

- `Void OnConfirmPressed()`

- `Void _TweenUpdate(Single)`

- `Void ShowView()`

- `Boolean get_isShowing()`

- `Void CloseView()`

- `Void CancelView()`

- `Void <CloseView>b__16_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureBaseView`1 : PageComponent, IUIArchitectureBaseView, IHotfixable
{
	private T m_arg; // 0x0
	private Func`1 m_onConfirm; // 0x0
	private Action m_onCancel; // 0x0
	private CanvasGroup m_canvasGroup; // 0x0
	private Boolean m_isShowing; // 0x0
	private static DelegateBridge __Hotfix0_OnAwake; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0_get_arg; // 0x0
	private static DelegateBridge __Hotfix0_DoSetup; // 0x0
	private static DelegateBridge __Hotfix0_OnCancelPressed; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirmPressed; // 0x0
	private static DelegateBridge __Hotfix0__TweenUpdate; // 0x0
	private static DelegateBridge __Hotfix0_ShowView; // 0x0
	private static DelegateBridge __Hotfix0_get_isShowing; // 0x0
	private static DelegateBridge __Hotfix0_CloseView; // 0x0
	private static DelegateBridge __Hotfix0_CancelView; // 0x0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	protected T arg { get; }
	public Boolean isShowing { get; }

	// RVA: 0x VA: 0x0
	protected override Void OnAwake() { }
	// RVA: 0x VA: 0x0
	public Void Setup(T arg, Func`1 onConfirm, Action onCancel) { }
	// RVA: 0x VA: 0x0
	protected T get_arg() { }
	// RVA: 0x VA: 0x0
	protected virtual Void DoSetup(T arg) { }
	// RVA: 0x VA: 0x0
	public Void OnCancelPressed() { }
	// RVA: 0x VA: 0x0
	public Void OnConfirmPressed() { }
	// RVA: 0x VA: 0x0
	private Void _TweenUpdate(Single val) { }
	// RVA: 0x VA: 0x0
	public Void ShowView() { }
	// RVA: 0x VA: 0x0
	public Boolean get_isShowing() { }
	// RVA: 0x VA: 0x0
	public Void CloseView() { }
	// RVA: 0x VA: 0x0
	public Void CancelView() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnPlayerDataChanged(Object _) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private Void <CloseView>b__16_0() { }
}
```