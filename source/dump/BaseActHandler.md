# BaseActHandler

**Namespace:** ` `


## Fields

- `TemplateActivityBindPlainHolder m_binderListHolder`

- `TemplateActivityViewModelProperty m_activityModelProperty`

- `ActivityEntryPageHandler m_pageActHandler`


## Methods

- `Void OnDispose()`

- `Void _InitViewModel(String, TemplateActivityViewModel)`

- `TemplateActivityViewModel GetViewModel(String)`

- `Void UnBind(IBaseActViewBinder, String)`

- `Void Bind(IBaseActViewBinder, String)`

- `Void OnDataUpdated(String)`

- `ActState GetCurrentState()`

- `Boolean CheckIfActivityIsOpen()`

- `String GetActId()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BaseActHandler : IBaseActHanlder, IHotfixable, IPlayerDataListener
{
	private TemplateActivityBindPlainHolder m_binderListHolder; // 0x10
	private TemplateActivityViewModelProperty m_activityModelProperty; // 0x18
	private ActivityEntryPageHandler m_pageActHandler; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnDispose; // 0x8
	private static DelegateBridge __Hotfix0__InitViewModel; // 0x10
	private static DelegateBridge __Hotfix0_GetViewModel; // 0x18
	private static DelegateBridge __Hotfix0_UnBind; // 0x20
	private static DelegateBridge __Hotfix0_Bind; // 0x28
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x30
	private static DelegateBridge __Hotfix0_GetCurrentState; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfActivityIsOpen; // 0x40
	private static DelegateBridge __Hotfix0_GetActId; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x50
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x58


	// RVA: 0x2ef1ba8 VA: 0x7595509ba8
	public Void .ctor(ActivityEntryPageHandler pageActHandler) { }
	// RVA: 0x2ef1d5c VA: 0x7595509d5c
	public Void OnDispose() { }
	// RVA: 0x2ef1df4 VA: 0x7595509df4
	private Void _InitViewModel(String id, TemplateActivityViewModel viewModel) { }
	// RVA: 0x2ef2158 VA: 0x759550a158
	public TemplateActivityViewModel GetViewModel(String param) { }
	// RVA: 0x2ef2278 VA: 0x759550a278
	public Void UnBind(IBaseActViewBinder binder, String param) { }
	// RVA: 0x2ef23c0 VA: 0x759550a3c0
	public Void Bind(IBaseActViewBinder binder, String param) { }
	// RVA: 0x2ef262c VA: 0x759550a62c
	public Void OnDataUpdated(String param) { }
	// RVA: 0x2ef279c VA: 0x759550a79c
	public ActState GetCurrentState() { }
	// RVA: 0x2ef287c VA: 0x759550a87c
	public Boolean CheckIfActivityIsOpen() { }
	// RVA: 0x2ef28f0 VA: 0x759550a8f0
	public String GetActId() { }
	// RVA: 0x2ef29f8 VA: 0x759550a9f8
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2ef2b28 VA: 0x759550ab28
	public Void OnPlayerDataChanged() { }
}
```