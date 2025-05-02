# SandboxV2AdminMainSciencePanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainScienceView _contentView`

- `SandboxV2AdminMainScienceTypeSelectView _selectView`

- `SandboxV2AdminMainScienceDetailView _detailView`

- `SandboxV2AdminMainScienceTopBarView _topbarView`

- `SandboxV2AdminMainSciencePanelModelProperty m_property`

- `String m_cachedTopicId`


## Methods

- `Void _InitIfNot()`

- `Void _UpdatePlayerData()`

- `Void EventOnNodeDevelop(String)`

- `Void _OnScienceUnlockRespond(SandboxV2ScienceUnlockResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainSciencePanel : SandboxV2AdminMainTabPanel
{
	private SandboxV2AdminMainScienceView _contentView; // 0x60
	private SandboxV2AdminMainScienceTypeSelectView _selectView; // 0x68
	private SandboxV2AdminMainScienceDetailView _detailView; // 0x70
	private SandboxV2AdminMainScienceTopBarView _topbarView; // 0x78
	private SandboxV2AdminMainSciencePanelModelProperty m_property; // 0x80
	private String m_cachedTopicId; // 0x88
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_get_topTitle; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x20
	private static DelegateBridge __Hotfix0_EventOnNodeDevelop; // 0x28
	private static DelegateBridge __Hotfix0__OnScienceUnlockRespond; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SandboxV2AdminMainPanelType panelType { get; }
	public override String topTitle { get; }

	// RVA: 0x24e2204 VA: 0x7594afa204
	public override SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24e226c VA: 0x7594afa26c
	public override String get_topTitle() { }
	// RVA: 0x24e22f8 VA: 0x7594afa2f8
	protected override Void OnUpdate(SandboxV2AdminMainTabPanelUpdateCase updateCase) { }
	// RVA: 0x24e23d8 VA: 0x7594afa3d8
	private Void _InitIfNot() { }
	// RVA: 0x24e29bc VA: 0x7594afa9bc
	private Void _UpdatePlayerData() { }
	// RVA: 0x24e2d08 VA: 0x7594afad08
	private Void EventOnNodeDevelop(String nodeId) { }
	// RVA: 0x24e3058 VA: 0x7594afb058
	private Void _OnScienceUnlockRespond(SandboxV2ScienceUnlockResponse resp) { }
	// RVA: 0x24e30d4 VA: 0x7594afb0d4
	public Void .ctor() { }
}
```