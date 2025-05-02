# LeaseManager

**Namespace:** `System.Runtime.Remoting.Lifetime`


## Fields

- `ArrayList _objects`

- `Timer _timer`


## Methods

- `Void SetPollTime(TimeSpan)`

- `Void TrackLifetime(ServerIdentity)`

- `Void StartManager()`

- `Void StopManager()`

- `Void ManageLeases(Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Lifetime
internal class LeaseManager
{
	private ArrayList _objects; // 0x10
	private Timer _timer; // 0x18


	// RVA: 0x5f9399c VA: 0x75985ab99c
	public Void SetPollTime(TimeSpan timeSpan) { }
	// RVA: 0x5f93a94 VA: 0x75985aba94
	public Void TrackLifetime(ServerIdentity identity) { }
	// RVA: 0x5f93bc8 VA: 0x75985abbc8
	public Void StartManager() { }
	// RVA: 0x5f93d38 VA: 0x75985abd38
	public Void StopManager() { }
	// RVA: 0x5f93d68 VA: 0x75985abd68
	public Void ManageLeases(Object state) { }
	// RVA: 0x5f93fb8 VA: 0x75985abfb8
	public Void .ctor() { }
}
```