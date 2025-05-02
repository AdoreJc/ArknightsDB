# SandboxV2AdminMainWorkbenchPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainWorkbenchTypeSelectorView _leftTypeView`

- `SandboxV2WorkbenchView _workbenchView`

- `Boolean m_hasInited`

- `SandboxV2AdminMainWorkbenchPanelModelProperty m_prop`


## Methods

- `Void _InitIfNot()`

- `Void _ItemSelectEvent(Int32)`

- `Void _SetFilterCanMakeEvent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainWorkbenchPanel : SandboxV2AdminMainTabPanel
{
	private SandboxV2AdminMainWorkbenchTypeSelectorView _leftTypeView; // 0x60
	private SandboxV2WorkbenchView _workbenchView; // 0x68
	private Boolean m_hasInited; // 0x70
	private SandboxV2AdminMainWorkbenchPanelModelProperty m_prop; // 0x78
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_get_topTitle; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__ItemSelectEvent; // 0x20
	private static DelegateBridge __Hotfix0__SetFilterCanMakeEvent; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override SandboxV2AdminMainPanelType panelType { get; }
	public override String topTitle { get; }

	// RVA: 0x24ecd70 VA: 0x7594b04d70
	public override SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24ecdd8 VA: 0x7594b04dd8
	public override String get_topTitle() { }
	// RVA: 0x24ece64 VA: 0x7594b04e64
	protected override Void OnUpdate(SandboxV2AdminMainTabPanelUpdateCase updateCase) { }
	// RVA: 0x24ecf30 VA: 0x7594b04f30
	private Void _InitIfNot() { }
	// RVA: 0x24ed7f8 VA: 0x7594b057f8
	private Void _ItemSelectEvent(Int32 index) { }
	// RVA: 0x24eda00 VA: 0x7594b05a00
	private Void _SetFilterCanMakeEvent() { }
	// RVA: 0x24edab4 VA: 0x7594b05ab4
	public Void .ctor() { }
}
```