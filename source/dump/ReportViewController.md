# ReportViewController

**Namespace:** ` `


## Fields

- `RL02ReportController m_closure`

- `RL02CommonReportViewBase m_currentView`


## Methods

- `Void Init()`

- `ReportViewType GetCurrentViewType()`

- `Void SwitchView(ReportViewType, Boolean)`

- `IEnumerator _SwitchViewCoroutine(ReportViewType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReportViewController : IHotfixable
{
	private RL02ReportController m_closure; // 0x10
	private ListDict`2 m_prefabMap; // 0x18
	private ListDict`2 m_instMap; // 0x20
	private RL02CommonReportViewBase m_currentView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_GetCurrentViewType; // 0x10
	private static DelegateBridge __Hotfix0_SwitchView; // 0x18
	private static DelegateBridge __Hotfix0__SwitchViewCoroutine; // 0x20


	// RVA: 0x2b61754 VA: 0x7595179754
	public Void .ctor(RL02ReportController closure) { }
	// RVA: 0x2b613c8 VA: 0x75951793c8
	public Void Init() { }
	// RVA: 0x2b61e64 VA: 0x7595179e64
	public ReportViewType GetCurrentViewType() { }
	// RVA: 0x2b61f28 VA: 0x7595179f28
	public Void SwitchView(ReportViewType targetViewType, Boolean isForward) { }
	// RVA: 0x2b62678 VA: 0x759517a678
	private IEnumerator _SwitchViewCoroutine(ReportViewType targetViewType, Boolean isForward) { }
}
```