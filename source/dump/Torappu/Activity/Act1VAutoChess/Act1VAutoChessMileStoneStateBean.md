# Act1VAutoChessMileStoneStateBean

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessMilestoneProp m_prop`


## Properties

- `Act1VAutoChessMilestoneProp mileStoneProp`


## Methods

- `Act1VAutoChessMilestoneProp get_mileStoneProp()`

- `Void InitModel(String, TemplateActivityMilestoneGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessMileStoneStateBean : IStateBean, IHotfixable
{
	private Act1VAutoChessMilestoneProp m_prop; // 0x10
	private static DelegateBridge __Hotfix0_get_mileStoneProp; // 0x0
	private static DelegateBridge __Hotfix0_InitModel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Act1VAutoChessMilestoneProp mileStoneProp { get; }

	// RVA: 0x335c73c VA: 0x759597473c
	public Act1VAutoChessMilestoneProp get_mileStoneProp() { }
	// RVA: 0x335dcd0 VA: 0x7595975cd0
	public Void InitModel(String actId, TemplateActivityMilestoneGroupViewModel tmplViewModel) { }
	// RVA: 0x335d704 VA: 0x7595975704
	public Void .ctor() { }
}
```