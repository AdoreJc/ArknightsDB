# WaitForSpineTrackEntryEnd

**Namespace:** `Spine.Unity`


## Fields

- `Boolean m_WasFired`


## Methods

- `Void HandleEnd(TrackEntry)`

- `Void SafeSubscribe(TrackEntry)`

- `WaitForSpineTrackEntryEnd NowWaitFor(TrackEntry)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class WaitForSpineTrackEntryEnd : IEnumerator
{
	private Boolean m_WasFired; // 0x10

	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x621eeac VA: 0x7598836eac
	public Void .ctor(TrackEntry trackEntry) { }
	// RVA: 0x621efbc VA: 0x7598836fbc
	private Void HandleEnd(TrackEntry trackEntry) { }
	// RVA: 0x621eed8 VA: 0x7598836ed8
	private Void SafeSubscribe(TrackEntry trackEntry) { }
	// RVA: 0x621efc8 VA: 0x7598836fc8
	public WaitForSpineTrackEntryEnd NowWaitFor(TrackEntry trackEntry) { }
	// RVA: 0x621efe0 VA: 0x7598836fe0
	private Boolean System.Collections.IEnumerator.MoveNext() { }
	// RVA: 0x621f090 VA: 0x7598837090
	private Void System.Collections.IEnumerator.Reset() { }
	// RVA: 0x621f098 VA: 0x7598837098
	private Object System.Collections.IEnumerator.get_Current() { }
}
```