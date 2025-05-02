# AlphaTracker

**Namespace:** ` `


## Fields

- `Boolean m_isTracking`

- `CanvasGroup m_alphaHandler`

- `Graphic m_trackTarget`

- `Single m_baseAlpha`


## Methods

- `Void SetBaseAlpha(Single)`

- `Single _GetTrackTargetAlpha()`

- `Void _EnableTrack(Boolean)`

- `Void UpdateTime(Single)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AlphaTracker : IDisposable, ITimeWatcher
{
	private Boolean m_isTracking; // 0x10
	private CanvasGroup m_alphaHandler; // 0x18
	private Graphic m_trackTarget; // 0x20
	private Single m_baseAlpha; // 0x28


	// RVA: 0x3e96398 VA: 0x75964ae398
	public Void .ctor(CanvasGroup alphaHandler, Graphic trackTarget) { }
	// RVA: 0x3e96450 VA: 0x75964ae450
	public Void SetBaseAlpha(Single baseAlpha) { }
	// RVA: 0x3e96538 VA: 0x75964ae538
	private Single _GetTrackTargetAlpha() { }
	// RVA: 0x3e965e4 VA: 0x75964ae5e4
	private Void _EnableTrack(Boolean enable) { }
	// RVA: 0x3e96618 VA: 0x75964ae618
	public Void UpdateTime(Single delta) { }
	// RVA: 0x3e96744 VA: 0x75964ae744
	public Void Dispose() { }
}
```