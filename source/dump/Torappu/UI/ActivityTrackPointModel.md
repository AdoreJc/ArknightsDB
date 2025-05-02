# ActivityTrackPointModel

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_hasTrackPoint`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ActivityTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_hasTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x20fdc7c VA: 0x7594715c7c
	public Boolean get_isShow() { }
	// RVA: 0x20fdce4 VA: 0x7594715ce4
	public Void UpdateState(Object param) { }
	// RVA: 0x20fe0c4 VA: 0x75947160c4
	public Void .ctor() { }
}
```