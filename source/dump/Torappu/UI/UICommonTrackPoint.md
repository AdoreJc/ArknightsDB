# UICommonTrackPoint

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _trackPointPrefab`

- `Transform _pointContainer`

- `Boolean m_isInited`

- `GameObject m_trackPoint`


## Properties

- `GameObject trackPoint`


## Methods

- `GameObject get_trackPoint()`

- `Void _InitIfNot()`

- `Void OnStateChanged(ITrackPointStatus)`

- `Void _Set(Boolean)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommonTrackPoint : DataBinder`1, IBindLocalTrackStore
{
	private GameObject _trackPointPrefab; // 0x20
	private Transform _pointContainer; // 0x28
	private Boolean m_isInited; // 0x30
	private GameObject m_trackPoint; // 0x38
	private static DelegateBridge __Hotfix0_get_trackPoint; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnStateChanged; // 0x18
	private static DelegateBridge __Hotfix0__Set; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected GameObject trackPoint { get; }

	// RVA: 0x21ea988 VA: 0x7594802988
	protected GameObject get_trackPoint() { }
	// RVA: 0x21ea9f0 VA: 0x75948029f0
	private Void _InitIfNot() { }
	// RVA: 0x21eab48 VA: 0x7594802b48
	public override Void OnValueChanged(TrackPointViewProperty property) { }
	// RVA: 0x21eacf0 VA: 0x7594802cf0
	public Void OnStateChanged(ITrackPointStatus status) { }
	// RVA: 0x21eac64 VA: 0x7594802c64
	private Void _Set(Boolean show) { }
	// RVA: 0x21eade4 VA: 0x7594802de4
	private Void OnDestroy() { }
	// RVA: 0x21eae74 VA: 0x7594802e74
	public Void .ctor() { }
}
```