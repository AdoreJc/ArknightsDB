# Act4D0ZoneMapPlugin

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Text _textPoint`

- `GameObject _viewRoot`


## Methods

- `Boolean _CheckIfToShowOnZone(String, ZoneViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0ZoneMapPlugin : StageZoneMapStatePlugin
{
	private Text _textPoint; // 0x18
	private GameObject _viewRoot; // 0x20
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x0
	private static DelegateBridge __Hotfix0__CheckIfToShowOnZone; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31e1984 VA: 0x75957f9984
	public override Void UpdateStatus(String actId, StagePage page, ZoneViewProperty zoneProp) { }
	// RVA: 0x31e1ae0 VA: 0x75957f9ae0
	private Boolean _CheckIfToShowOnZone(String actid, ZoneViewProperty zoneProp) { }
	// RVA: 0x31e1c18 VA: 0x75957f9c18
	public Void .ctor() { }
}
```