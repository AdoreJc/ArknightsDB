# Act13sideMissionTrackPointModel

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Boolean hasTrackPoint`

- `Boolean isNew`


## Properties

- `Boolean isShow`


## Methods

- `Void UpdateState(Object)`

- `Boolean get_isShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean hasTrackPoint; // 0x10
	private Boolean isNew; // 0x11
	private static DelegateBridge __Hotfix0_UpdateState; // 0x0
	private static DelegateBridge __Hotfix0_get_isShow; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x3428f34 VA: 0x7595a40f34
	public Void UpdateState(Object param) { }
	// RVA: 0x3429034 VA: 0x7595a41034
	public Boolean get_isShow() { }
	// RVA: 0x34290b4 VA: 0x7595a410b4
	public Void .ctor() { }
}
```