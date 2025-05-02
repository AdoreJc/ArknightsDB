# Act1LockDetailViewBase

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `DetailViewStatus m_detailStatus`

- `UIPage m_page`

- `Tween m_defaultEnterTween`

- `Tween m_defaultExitTween`

- `CanvasGroup m_canvasGroup`


## Properties

- `Boolean isActive`

- `Boolean isTransiting`

- `UIPage page`

- `CanvasGroup alphaHandler`


## Methods

- `Boolean get_isActive()`

- `Boolean get_isTransiting()`

- `UIPage get_page()`

- `Void Setup(UIPage)`

- `CanvasGroup get_alphaHandler()`

- `IEnumerator _EnterProcess()`

- `IEnumerator _ExitProcess()`

- `Void _CoroutineWithPage(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockDetailViewBase : DataBinder`1
{
	private const Single DEFAULT_ANIM_DUR; // 0x0
	private DetailViewStatus m_detailStatus; // 0x20
	private UIPage m_page; // 0x28
	private Tween m_defaultEnterTween; // 0x30
	private Tween m_defaultExitTween; // 0x38
	private CanvasGroup m_canvasGroup; // 0x40
	private static DelegateBridge __Hotfix0_get_isActive; // 0x0
	private static DelegateBridge __Hotfix0_get_isTransiting; // 0x8
	private static DelegateBridge __Hotfix0_get_page; // 0x10
	private static DelegateBridge __Hotfix0_Setup; // 0x18
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x38
	private static DelegateBridge __Hotfix0_CancelExit; // 0x40
	private static DelegateBridge __Hotfix0_CancelEnter; // 0x48
	private static DelegateBridge __Hotfix0_EnterYieldInstruction; // 0x50
	private static DelegateBridge __Hotfix0_ExitYieldInstruction; // 0x58
	private static DelegateBridge __Hotfix0__EnterProcess; // 0x60
	private static DelegateBridge __Hotfix0__ExitProcess; // 0x68
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected Boolean isActive { get; }
	protected Boolean isTransiting { get; }
	protected UIPage page { get; }
	protected CanvasGroup alphaHandler { get; }

	// RVA: 0x33a9570 VA: 0x75959c1570
	protected Boolean get_isActive() { }
	// RVA: 0x33a95e4 VA: 0x75959c15e4
	protected Boolean get_isTransiting() { }
	// RVA: 0x33a9658 VA: 0x75959c1658
	protected UIPage get_page() { }
	// RVA: 0x339e76c VA: 0x75959b676c
	public Void Setup(UIPage page) { }
	// RVA: 0x33a96c0 VA: 0x75959c16c0
	protected CanvasGroup get_alphaHandler() { }
	// RVA: 0x33a9798 VA: 0x75959c1798
	public override Void OnValueChanged(Act1LockDetailProperty property) { }
	// RVA: 0x33a9b1c VA: 0x75959c1b1c
	protected virtual Void OnEnter() { }
	// RVA: 0x33a9b80 VA: 0x75959c1b80
	protected virtual Void OnDataUpdated(Act1LockDetailProperty prop) { }
	// RVA: 0x33a9bf8 VA: 0x75959c1bf8
	protected virtual Void CancelExit() { }
	// RVA: 0x33a9c98 VA: 0x75959c1c98
	protected virtual Void CancelEnter() { }
	// RVA: 0x33a9d38 VA: 0x75959c1d38
	protected virtual IEnumerator EnterYieldInstruction() { }
	// RVA: 0x33a9e0c VA: 0x75959c1e0c
	protected virtual IEnumerator ExitYieldInstruction() { }
	// RVA: 0x33a98ec VA: 0x75959c18ec
	private IEnumerator _EnterProcess() { }
	// RVA: 0x33a9a70 VA: 0x75959c1a70
	private IEnumerator _ExitProcess() { }
	// RVA: 0x33a9998 VA: 0x75959c1998
	private Void _CoroutineWithPage(IEnumerator coroutine) { }
	// RVA: 0x33a9f30 VA: 0x75959c1f30
	public Void .ctor() { }
}
```