# Act1ArcadeSettlementCharCardItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelWithInfo`


## Methods

- `Void ApplyData(Boolean, SquadItemStruct)`

- `Void _SetPanelsStatus(GameObject[], Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementCharCardItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelWithInfo; // 0x20
	private GameObject[] _normalCardShowOnlyPanels; // 0x28
	private GameObject[] _assistCardShowOnlyPanels; // 0x30
	private Act1ArcadeSettlementCharCardItemAdvanceInfoPlugin[] _plugins; // 0x38
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__SetPanelsStatus; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x340868c VA: 0x7595a2068c
	public Void ApplyData(Boolean isAssist, SquadItemStruct squadItemStruct) { }
	// RVA: 0x3408848 VA: 0x7595a20848
	private Void _SetPanelsStatus(GameObject[] panels, Boolean isShow) { }
	// RVA: 0x3408910 VA: 0x7595a20910
	public Void .ctor() { }
}
```