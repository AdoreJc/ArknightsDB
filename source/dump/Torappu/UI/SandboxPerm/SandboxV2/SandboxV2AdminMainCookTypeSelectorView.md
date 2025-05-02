# SandboxV2AdminMainCookTypeSelectorView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainCookPanelModelProperty m_cachedProp`

- `Boolean m_tutorialIsTypeButtonRegistered`


## Methods

- `Void _TutorialOnly_TryRegisterTypeButtonGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainCookTypeSelectorView : SandboxV2AdminMainTypeSelectViewBase`2
{
	private SandboxV2CookTypeDefine[] _typeDefine; // 0x50
	private SandboxV2AdminMainCookPanelModelProperty m_cachedProp; // 0x58
	private Boolean m_tutorialIsTypeButtonRegistered; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_GetDefinedTypeList; // 0x8
	private static DelegateBridge __Hotfix0_CheckTypeActive; // 0x10
	private static DelegateBridge __Hotfix0_OnTypeSelectChanged; // 0x18
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRegisterTypeButtonGO; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x24cdce0 VA: 0x7594ae5ce0
	public override Void OnValueChanged(SandboxV2AdminMainCookPanelModelProperty property) { }
	// RVA: 0x24cdfec VA: 0x7594ae5fec
	protected override IList`1 GetDefinedTypeList() { }
	// RVA: 0x24ce054 VA: 0x7594ae6054
	protected override Boolean CheckTypeActive(SandboxV2AdminMainCookType type) { }
	// RVA: 0x24ce0fc VA: 0x7594ae60fc
	protected override Void OnTypeSelectChanged(SandboxV2AdminMainCookType selectType) { }
	// RVA: 0x24cddc4 VA: 0x7594ae5dc4
	private Void _TutorialOnly_TryRegisterTypeButtonGO() { }
	// RVA: 0x24ce1e0 VA: 0x7594ae61e0
	public Void .ctor() { }
}
```