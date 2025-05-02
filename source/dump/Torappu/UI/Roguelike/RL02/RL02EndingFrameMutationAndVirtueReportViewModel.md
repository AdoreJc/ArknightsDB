# RL02EndingFrameMutationAndVirtueReportViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `String topicId`

- `RoguelikeCharBuffModel mutation`


## Properties

- `Boolean hasMutation`

- `Boolean hasVirtue`


## Methods

- `Boolean get_hasMutation()`

- `Boolean get_hasVirtue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02EndingFrameMutationAndVirtueReportViewModel : RL02EndingFrameReportViewModel
{
	public String topicId; // 0x18
	public RoguelikeCharBuffModel mutation; // 0x20
	public List`1 mutationCharNames; // 0x58
	public List`1 virtueList; // 0x60
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_get_hasMutation; // 0x10
	private static DelegateBridge __Hotfix0_get_hasVirtue; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override ReportViewType viewType { get; }
	public Boolean hasMutation { get; }
	public Boolean hasVirtue { get; }

	// RVA: 0x2b68018 VA: 0x7595180018
	public override ReportViewType get_viewType() { }
	// RVA: 0x2b68080 VA: 0x7595180080
	protected override Boolean LoadData(String topicId, RL02EndingFrameViewModel dataSource) { }
	// RVA: 0x2b686f4 VA: 0x75951806f4
	public Boolean get_hasMutation() { }
	// RVA: 0x2b68798 VA: 0x7595180798
	public Boolean get_hasVirtue() { }
	// RVA: 0x2b68824 VA: 0x7595180824
	public Void .ctor() { }
}
```