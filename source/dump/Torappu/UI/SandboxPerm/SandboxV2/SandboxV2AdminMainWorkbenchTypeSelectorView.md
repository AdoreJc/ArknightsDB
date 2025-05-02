# SandboxV2AdminMainWorkbenchTypeSelectorView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainWorkbenchPanelModelProperty m_cachedProp`

- `Boolean m_tutorialIsTypeButtonRegistered`


## Methods

- `Void _TutorialOnly_TryRegisterTypeButtonGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainWorkbenchTypeSelectorView : SandboxV2AdminMainTypeSelectViewBase`2
{
	private SandboxV2WorkbenchTypeDefine[] _typeDefine; // 0x50
	private SandboxV2AdminMainWorkbenchPanelModelProperty m_cachedProp; // 0x58
	private Boolean m_tutorialIsTypeButtonRegistered; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_GetDefinedTypeList; // 0x8
	private static DelegateBridge __Hotfix0_CheckTypeActive; // 0x10
	private static DelegateBridge __Hotfix0_OnTypeSelectChanged; // 0x18
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRegisterTypeButtonGO; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x24efb10 VA: 0x7594b07b10
	public override Void OnValueChanged(SandboxV2AdminMainWorkbenchPanelModelProperty property) { }
	// RVA: 0x24efd30 VA: 0x7594b07d30
	protected override IList`1 GetDefinedTypeList() { }
	// RVA: 0x24efd98 VA: 0x7594b07d98
	protected override Boolean CheckTypeActive(SandboxV2AdminMainWorkbenchType type) { }
	// RVA: 0x24efe8c VA: 0x7594b07e8c
	protected override Void OnTypeSelectChanged(SandboxV2AdminMainWorkbenchType selectType) { }
	// RVA: 0x24efbf0 VA: 0x7594b07bf0
	private Void _TutorialOnly_TryRegisterTypeButtonGO() { }
	// RVA: 0x24eff70 VA: 0x7594b07f70
	public Void .ctor() { }
}
```