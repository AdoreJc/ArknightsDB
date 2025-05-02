# ActMultiV3SquadHomeStateBean

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3SquadGroupProp m_prop`

- `TrackPointViewProperty m_trackPointProp`


## Properties

- `ActMultiV3SquadGroupProp prop`

- `TrackPointViewProperty trackPointProp`


## Methods

- `ActMultiV3SquadGroupProp get_prop()`

- `TrackPointViewProperty get_trackPointProp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadHomeStateBean : IStateBean, IHotfixable
{
	private ActMultiV3SquadGroupProp m_prop; // 0x10
	private TrackPointViewProperty m_trackPointProp; // 0x18
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_get_trackPointProp; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public ActMultiV3SquadGroupProp prop { get; }
	public TrackPointViewProperty trackPointProp { get; }

	// RVA: 0x313c440 VA: 0x7595754440
	public ActMultiV3SquadGroupProp get_prop() { }
	// RVA: 0x313df44 VA: 0x7595755f44
	public TrackPointViewProperty get_trackPointProp() { }
	// RVA: 0x313ffe4 VA: 0x7595757fe4
	public Void .ctor() { }
}
```