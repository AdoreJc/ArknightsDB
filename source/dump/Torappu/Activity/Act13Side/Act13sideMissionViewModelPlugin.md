# Act13sideMissionViewModelPlugin

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `TemplateActivityMissionGroupViewModel m_context`

- `String m_currentSelectOrg`

- `String missionGroupId`


## Properties

- `String orgId`


## Methods

- `Void set_orgId(String)`

- `String get_orgId()`

- `Void SetContext(TemplateActivityMissionGroupViewModel)`

- `Boolean CheckMissionShowAbleFlag(Int32)`

- `TemplateMissionViewModel GetTargetViewModel(String)`

- `Boolean GetCanGetMissionByOrg(String)`

- `Boolean Compare(TemplateMissionViewModel, TemplateMissionViewModel, out)`

- `Void OnChangeOrg(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionViewModelPlugin : TemplateActivityMissionViewModelPlugin
{
	private const String INIT_ORG_PARAM; // 0x0
	private TemplateActivityMissionGroupViewModel m_context; // 0x10
	private String m_currentSelectOrg; // 0x18
	public String missionGroupId; // 0x20

	public String orgId { get; set; }

	// RVA: 0x3439e60 VA: 0x7595a51e60
	public Void set_orgId(String value) { }
	// RVA: 0x3439e68 VA: 0x7595a51e68
	public String get_orgId() { }
	// RVA: 0x3439e70 VA: 0x7595a51e70
	public Void SetContext(TemplateActivityMissionGroupViewModel viewModel) { }
	// RVA: 0x3439ed8 VA: 0x7595a51ed8
	public Boolean CheckMissionShowAbleFlag(Int32 missionIndex) { }
	// RVA: 0x34333ec VA: 0x7595a4b3ec
	public TemplateMissionViewModel GetTargetViewModel(String groupId) { }
	// RVA: 0x3432f80 VA: 0x7595a4af80
	public Boolean GetCanGetMissionByOrg(String orgId) { }
	// RVA: 0x3439f94 VA: 0x7595a51f94
	public Boolean Compare(TemplateMissionViewModel a, TemplateMissionViewModel b, out Int32 result) { }
	// RVA: 0x3433cc8 VA: 0x7595a4bcc8
	public Void OnChangeOrg(String orgId_) { }
	// RVA: 0x3439fa0 VA: 0x7595a51fa0
	public Void .ctor() { }
}
```