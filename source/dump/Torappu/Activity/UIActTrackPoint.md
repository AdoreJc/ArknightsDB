# UIActTrackPoint

**Namespace:** `Torappu.Activity`


## Fields

- `Transform _pointContainer`

- `GameObject _customPrefab`

- `Boolean m_isInited`

- `GameObject m_trackPoint`


## Properties

- `GameObject trackPoint`


## Methods

- `GameObject get_trackPoint()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class UIActTrackPoint : DataBinder`1
{
	private Transform _pointContainer; // 0x20
	private GameObject _customPrefab; // 0x28
	private Boolean m_isInited; // 0x30
	private GameObject m_trackPoint; // 0x38
	private static DelegateBridge __Hotfix0_get_trackPoint; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected GameObject trackPoint { get; }

	// RVA: 0x30cc318 VA: 0x75956e4318
	protected GameObject get_trackPoint() { }
	// RVA: 0x30cc380 VA: 0x75956e4380
	private Void _InitIfNot() { }
	// RVA: 0x30cc4cc VA: 0x75956e44cc
	public override Void OnValueChanged(TrackPointViewProperty property) { }
	// RVA: 0x30cc5f0 VA: 0x75956e45f0
	public Void .ctor() { }
}
```