# TrackObserverCenter

**Namespace:** ` `


## Methods

- `IDObserver AllocIDObserver(String, String, TrackChangeCallback, Object)`

- `Void ReleaseIDObserver(IDObserver)`

- `Void NotifyTrackChanged(String, String, Boolean)`

- `Void NotifyTrackTypeRemoved(String, ICollection`1)`

- `Void AddObserver(ITrackObserver)`

- `Void RemoveObserver(ITrackObserver)`

- `Void _AddIDObserver(IDObserver)`

- `Void _RemoveIDObserver(IDObserver)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TrackObserverCenter : IHotfixable
{
	private LocalGenericPool`1 m_idObserverPool; // 0x10
	private Dictionary`2 m_idObservers; // 0x18
	private Dictionary`2 m_generalObservers; // 0x20
	private static DelegateBridge __Hotfix0_AllocIDObserver; // 0x0
	private static DelegateBridge __Hotfix0_ReleaseIDObserver; // 0x8
	private static DelegateBridge __Hotfix0_NotifyTrackChanged; // 0x10
	private static DelegateBridge __Hotfix0_NotifyTrackTypeRemoved; // 0x18
	private static DelegateBridge __Hotfix0_AddObserver; // 0x20
	private static DelegateBridge __Hotfix0_RemoveObserver; // 0x28
	private static DelegateBridge __Hotfix0__AddIDObserver; // 0x30
	private static DelegateBridge __Hotfix0__RemoveIDObserver; // 0x38
	private static DelegateBridge __Hotfix0__GetIDObservers; // 0x40
	private static DelegateBridge __Hotfix0__GetGeneralObservers; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2f3d540 VA: 0x7595555540
	public IDObserver AllocIDObserver(String type, String id, TrackChangeCallback callback, Object context) { }
	// RVA: 0x2f3db64 VA: 0x7595555b64
	public Void ReleaseIDObserver(IDObserver inst) { }
	// RVA: 0x2f3b658 VA: 0x7595553658
	public Void NotifyTrackChanged(String type, String id, Boolean exists) { }
	// RVA: 0x2f3bd74 VA: 0x7595553d74
	public Void NotifyTrackTypeRemoved(String type, ICollection`1 idSet) { }
	// RVA: 0x2f3d6fc VA: 0x75955556fc
	public Void AddObserver(ITrackObserver observer) { }
	// RVA: 0x2f3d930 VA: 0x7595555930
	public Void RemoveObserver(ITrackObserver observer) { }
	// RVA: 0x2f3e6d4 VA: 0x75955566d4
	private Void _AddIDObserver(IDObserver observer) { }
	// RVA: 0x2f3ea50 VA: 0x7595556a50
	private Void _RemoveIDObserver(IDObserver observer) { }
	// RVA: 0x2f3e198 VA: 0x7595556198
	private ListSet`1 _GetIDObservers(String type, String id, Boolean autoCreate) { }
	// RVA: 0x2f3e4fc VA: 0x75955564fc
	private ListSet`1 _GetGeneralObservers(String type, Boolean autoCreate) { }
	// RVA: 0x2f39df0 VA: 0x7595551df0
	public Void .ctor() { }
}
```