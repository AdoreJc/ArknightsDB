# DefaultActAnimContext

**Namespace:** `Torappu.Activity`


## Fields

- `String m_actId`


## Methods

- `Boolean _IsActStageClosed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class DefaultActAnimContext : IActAnimContext
{
	private String m_actId; // 0x10

	public virtual Single animDuration { get; }

	// RVA: 0x30ba938 VA: 0x75956d2938
	public Void .ctor(String activityId) { }
	// RVA: 0x30ba968 VA: 0x75956d2968
	public virtual Boolean CanSkipAnim() { }
	// RVA: 0x30ba96c VA: 0x75956d296c
	protected Boolean _IsActStageClosed() { }
	// RVA: 0x30baa40 VA: 0x75956d2a40
	public virtual Single get_animDuration() { }
}
```