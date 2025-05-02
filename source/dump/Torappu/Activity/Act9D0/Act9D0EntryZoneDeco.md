# Act9D0EntryZoneDeco

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0EntryZoneView _zoneView`

- `Int32 m_frameCounter`


## Methods

- `Void OnEnable()`

- `IEnumerator _TrackVisibility()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0EntryZoneDeco : MonoBehaviour, IHotfixable
{
	private const Int32 TRACK_VISIBILITY_FRAME_CNT; // 0x0
	private Act9D0EntryZoneView _zoneView; // 0x18
	private Int32 m_frameCounter; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0__TrackVisibility; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31af264 VA: 0x75957c7264
	public Void OnEnable() { }
	// RVA: 0x31af338 VA: 0x75957c7338
	private IEnumerator _TrackVisibility() { }
	// RVA: 0x31af40c VA: 0x75957c740c
	public Void .ctor() { }
}
```