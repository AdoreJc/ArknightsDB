# SandboxV2BasementView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2BasementBuildingDetailView _buildingDetailView`

- `SandboxV2BasementStatusView _basementStatusView`

- `SandboxV2BasementStatusView _portableBasementStatusView`

- `SandboxV2BasementStatusView _outpostStatusView`

- `SandboxV2BasementMonthEntryBtnView _monthEntryBtnView`

- `SandboxV2NodePreviewView _nodePreviewViewPrefab`

- `RectTransform _nodePreviewViewHolder`

- `Boolean m_inited`

- `SeqNumChecker m_nodeSelectChecker`

- `SeqNumChecker m_dungeonDataChangeChecker`

- `SandboxV2NodePreviewView m_nodePreviewView`


## Methods

- `Void _InitIfNot()`

- `GameObject TutorialOnly_GetStartBattleGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementView : DataBinder`1
{
	private SandboxV2BasementBuildingDetailView _buildingDetailView; // 0x20
	private SandboxV2BasementStatusView _basementStatusView; // 0x28
	private SandboxV2BasementStatusView _portableBasementStatusView; // 0x30
	private SandboxV2BasementStatusView _outpostStatusView; // 0x38
	private SandboxV2BasementMonthEntryBtnView _monthEntryBtnView; // 0x40
	private SandboxV2NodePreviewView _nodePreviewViewPrefab; // 0x48
	private RectTransform _nodePreviewViewHolder; // 0x50
	private Boolean m_inited; // 0x58
	private SeqNumChecker m_nodeSelectChecker; // 0x60
	private SeqNumChecker m_dungeonDataChangeChecker; // 0x70
	private SandboxV2NodePreviewView m_nodePreviewView; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_TutorialOnly_GetStartBattleGo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2511db4 VA: 0x7594b29db4
	private Void _InitIfNot() { }
	// RVA: 0x2511e9c VA: 0x7594b29e9c
	public override Void OnValueChanged(SandboxV2DungeonProperty property) { }
	// RVA: 0x250c990 VA: 0x7594b24990
	public GameObject TutorialOnly_GetStartBattleGo() { }
	// RVA: 0x251205c VA: 0x7594b2a05c
	public Void .ctor() { }
}
```