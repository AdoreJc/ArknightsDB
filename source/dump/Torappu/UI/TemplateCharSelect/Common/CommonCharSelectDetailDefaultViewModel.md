# CommonCharSelectDetailDefaultViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `CharSelectBranchGroupViewModel <branchViewModel>k__BackingField`

- `CharSelectSkillGroupViewModel <skillViewModel>k__BackingField`

- `TemplateCharSelectCardViewModel m_targetChar`


## Properties

- `CharSelectBranchGroupViewModel branchViewModel`

- `CharSelectSkillGroupViewModel skillViewModel`


## Methods

- `CharSelectBranchGroupViewModel get_branchViewModel()`

- `Void set_branchViewModel(CharSelectBranchGroupViewModel)`

- `CharSelectSkillGroupViewModel get_skillViewModel()`

- `Void set_skillViewModel(CharSelectSkillGroupViewModel)`

- `Void _SetSkillViewModel(TemplateCharSelectCardViewModel, Boolean)`

- `Void _SetBranchViewModel(TemplateCharSelectCardViewModel, Boolean)`

- `Void <>xLuaBaseProxy_Resume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectDetailDefaultViewModel : TemplateCharSelectDetailViewModelBase`1
{
	private CharSelectBranchGroupViewModel <branchViewModel>k__BackingField; // 0x10
	private CharSelectSkillGroupViewModel <skillViewModel>k__BackingField; // 0x18
	private TemplateCharSelectCardViewModel m_targetChar; // 0x20
	private static DelegateBridge __Hotfix0_get_branchViewModel; // 0x0
	private static DelegateBridge __Hotfix0_set_branchViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_skillViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_skillViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_targetChar; // 0x20
	private static DelegateBridge __Hotfix0_OnUpdateWithChar; // 0x28
	private static DelegateBridge __Hotfix0_Resume; // 0x30
	private static DelegateBridge __Hotfix0__SetSkillViewModel; // 0x38
	private static DelegateBridge __Hotfix0__SetBranchViewModel; // 0x40
	private static DelegateBridge __Hotfix0_Reset; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public CharSelectBranchGroupViewModel branchViewModel { get; set; }
	public CharSelectSkillGroupViewModel skillViewModel { get; set; }
	public override TemplateCharSelectCardViewModel targetChar { get; }

	// RVA: 0x2c54694 VA: 0x759526c694
	public CharSelectBranchGroupViewModel get_branchViewModel() { }
	// RVA: 0x2c54ec0 VA: 0x759526cec0
	private Void set_branchViewModel(CharSelectBranchGroupViewModel value) { }
	// RVA: 0x2c54ac8 VA: 0x759526cac8
	public CharSelectSkillGroupViewModel get_skillViewModel() { }
	// RVA: 0x2c54f44 VA: 0x759526cf44
	private Void set_skillViewModel(CharSelectSkillGroupViewModel value) { }
	// RVA: 0x2c54fc8 VA: 0x759526cfc8
	public override TemplateCharSelectCardViewModel get_targetChar() { }
	// RVA: 0x2c55030 VA: 0x759526d030
	protected override Void OnUpdateWithChar(TemplateCharSelectCardViewModel charModel, Boolean forceUpdate) { }
	// RVA: 0x2c55710 VA: 0x759526d710
	public override Void Resume() { }
	// RVA: 0x2c55154 VA: 0x759526d154
	private Void _SetSkillViewModel(TemplateCharSelectCardViewModel charModel, Boolean forceRefresh) { }
	// RVA: 0x2c55310 VA: 0x759526d310
	private Void _SetBranchViewModel(TemplateCharSelectCardViewModel charModel, Boolean forceRefresh) { }
	// RVA: 0x2c557a0 VA: 0x759526d7a0
	public override Void Reset(TemplateCharSelectModelResetData data) { }
	// RVA: 0x2c55844 VA: 0x759526d844
	public Void .ctor() { }
	// RVA: 0x2c558d4 VA: 0x759526d8d4
	private Void <>xLuaBaseProxy_Resume() { }
}
```