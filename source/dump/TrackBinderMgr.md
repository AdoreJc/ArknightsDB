# TrackBinderMgr

**Namespace:** ` `


## Fields

- `TrackObserverCenter m_observerCenter`

- `BinderSetter m_trackPointBinderSetter`


## Methods

- `Void BindLocalTrackPoint(TrackPointBinderKey, IBindLocalTrackStore)`

- `Void UnBindLocalTrackPoint(IBindLocalTrackStore)`

- `Void _AddBindedTrackPointToDict(TrackPointBinderKey, IBindLocalTrackStore)`

- `Void _RemoveBindedTrackPointFromDict(TrackPointBinderKey, IBindLocalTrackStore)`

- `Void _AddTrackPointObserverForBinder(BinderMeta)`

- `Void _ReleaseTrackPointMeta(BinderMeta)`

- `Void _UpdateTrackPointBinderCallback(Boolean, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TrackBinderMgr : IHotfixable
{
	private TrackObserverCenter m_observerCenter; // 0x10
	private Dictionary`2 m_bindedTrackPoints; // 0x18
	private Dictionary`2 m_trackBinderMetaDict; // 0x20
	private BinderSetter m_trackPointBinderSetter; // 0x28
	private LocalGenericPool`1 m_metaPool; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_BindLocalTrackPoint; // 0x8
	private static DelegateBridge __Hotfix0_UnBindLocalTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0__AddBindedTrackPointToDict; // 0x18
	private static DelegateBridge __Hotfix0__RemoveBindedTrackPointFromDict; // 0x20
	private static DelegateBridge __Hotfix0__AddTrackPointObserverForBinder; // 0x28
	private static DelegateBridge __Hotfix0__ReleaseTrackPointMeta; // 0x30
	private static DelegateBridge __Hotfix0__UpdateTrackPointBinderCallback; // 0x38


	// RVA: 0x2f39fb0 VA: 0x7595551fb0
	public Void .ctor(TrackObserverCenter observerCenter) { }
	// RVA: 0x2f3a270 VA: 0x7595552270
	public Void BindLocalTrackPoint(TrackPointBinderKey binderKey, IBindLocalTrackStore binder) { }
	// RVA: 0x2f3a554 VA: 0x7595552554
	public Void UnBindLocalTrackPoint(IBindLocalTrackStore trackPoint) { }
	// RVA: 0x2f3cfd8 VA: 0x7595554fd8
	private Void _AddBindedTrackPointToDict(TrackPointBinderKey binderKey, IBindLocalTrackStore binder) { }
	// RVA: 0x2f3d290 VA: 0x7595555290
	private Void _RemoveBindedTrackPointFromDict(TrackPointBinderKey binderKey, IBindLocalTrackStore binder) { }
	// RVA: 0x2f3d160 VA: 0x7595555160
	private Void _AddTrackPointObserverForBinder(BinderMeta meta) { }
	// RVA: 0x2f3d390 VA: 0x7595555390
	private Void _ReleaseTrackPointMeta(BinderMeta meta) { }
	// RVA: 0x2f3dc04 VA: 0x7595555c04
	private Void _UpdateTrackPointBinderCallback(Boolean isShow, Object rawMeta) { }
}
```