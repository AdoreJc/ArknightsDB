# SandboxV2AdminMainScienceTypeSelectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainScienceTypeSelector _selectorPrefab`

- `Text _scienceTitle`

- `SandboxV2AdminMainSciencePanelModelProperty m_cachedProp`

- `SandboxV2AdminMainScienceTypeSelector m_selector`


## Methods

- `Void _InitIfNot()`

- `Void _InitDataIfNot(SandboxV2AdminMainSciencePanelModel)`

- `Boolean _GenTypeLockStatus(SandboxV2AdminMainScienceType, SandboxV2AdminMainSciencePanelModel)`

- `Void _EventSelectChanged(Int32)`

- `Void _RefreshTitle(SandboxV2AdminMainSciencePanelModel)`

- `Void _RefreshSelectorProgress(SandboxV2AdminMainSciencePanelModel)`

- `Void _OnTypeSelectChanged(SandboxV2AdminMainScienceType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceTypeSelectView : DataBinder`1
{
	private SandboxV2AdminMainScienceTypeSelector _selectorPrefab; // 0x20
	private SandboxV2ScienceTypeDefine[] _typeDefine; // 0x28
	private Text _scienceTitle; // 0x30
	private SandboxV2AdminMainSciencePanelModelProperty m_cachedProp; // 0x38
	private SandboxV2AdminMainScienceTypeSelector m_selector; // 0x40
	private List`1 m_itemDatas; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__InitDataIfNot; // 0x8
	private static DelegateBridge __Hotfix0__GenTypeLockStatus; // 0x10
	private static DelegateBridge __Hotfix0__EventSelectChanged; // 0x18
	private static DelegateBridge __Hotfix0__RefreshTitle; // 0x20
	private static DelegateBridge __Hotfix0__RefreshSelectorProgress; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__OnTypeSelectChanged; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x24e714c VA: 0x7594aff14c
	private Void _InitIfNot() { }
	// RVA: 0x24e72d0 VA: 0x7594aff2d0
	private Void _InitDataIfNot(SandboxV2AdminMainSciencePanelModel viewModel) { }
	// RVA: 0x24e75d8 VA: 0x7594aff5d8
	private Boolean _GenTypeLockStatus(SandboxV2AdminMainScienceType type, SandboxV2AdminMainSciencePanelModel viewModel) { }
	// RVA: 0x24e7658 VA: 0x7594aff658
	private Void _EventSelectChanged(Int32 idx) { }
	// RVA: 0x24e77fc VA: 0x7594aff7fc
	private Void _RefreshTitle(SandboxV2AdminMainSciencePanelModel viewModel) { }
	// RVA: 0x24e7924 VA: 0x7594aff924
	private Void _RefreshSelectorProgress(SandboxV2AdminMainSciencePanelModel viewModel) { }
	// RVA: 0x24e7a68 VA: 0x7594affa68
	public override Void OnValueChanged(SandboxV2AdminMainSciencePanelModelProperty property) { }
	// RVA: 0x24e770c VA: 0x7594aff70c
	public Void _OnTypeSelectChanged(SandboxV2AdminMainScienceType selectType) { }
	// RVA: 0x24e7b48 VA: 0x7594affb48
	public Void .ctor() { }
}
```