# Lease

**Namespace:** `System.Runtime.Remoting.Lifetime`


## Fields

- `DateTime _leaseExpireTime`

- `LeaseState _currentState`

- `TimeSpan _initialLeaseTime`

- `TimeSpan _renewOnCallTime`

- `TimeSpan _sponsorshipTimeout`

- `ArrayList _sponsors`

- `Queue _renewingSponsors`

- `RenewalDelegate _renewalDelegate`


## Properties

- `TimeSpan CurrentLeaseTime`

- `LeaseState CurrentState`

- `TimeSpan RenewOnCallTime`


## Methods

- `TimeSpan get_CurrentLeaseTime()`

- `LeaseState get_CurrentState()`

- `Void Activate()`

- `TimeSpan get_RenewOnCallTime()`

- `TimeSpan Renew(TimeSpan)`

- `Void Unregister(ISponsor)`

- `Void CheckNextSponsor()`

- `Void ProcessSponsorResponse(Object, Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Lifetime
internal class Lease : MarshalByRefObject, ILease
{
	private DateTime _leaseExpireTime; // 0x18
	private LeaseState _currentState; // 0x20
	private TimeSpan _initialLeaseTime; // 0x28
	private TimeSpan _renewOnCallTime; // 0x30
	private TimeSpan _sponsorshipTimeout; // 0x38
	private ArrayList _sponsors; // 0x40
	private Queue _renewingSponsors; // 0x48
	private RenewalDelegate _renewalDelegate; // 0x50

	public TimeSpan CurrentLeaseTime { get; }
	public LeaseState CurrentState { get; }
	public TimeSpan RenewOnCallTime { get; }

	// RVA: 0x5f92e44 VA: 0x75985aae44
	public Void .ctor() { }
	// RVA: 0x5f92f9c VA: 0x75985aaf9c
	public TimeSpan get_CurrentLeaseTime() { }
	// RVA: 0x5f93004 VA: 0x75985ab004
	public LeaseState get_CurrentState() { }
	// RVA: 0x5f9300c VA: 0x75985ab00c
	public Void Activate() { }
	// RVA: 0x5f93018 VA: 0x75985ab018
	public TimeSpan get_RenewOnCallTime() { }
	// RVA: 0x5f93020 VA: 0x75985ab020
	public TimeSpan Renew(TimeSpan renewalTime) { }
	// RVA: 0x5f930ac VA: 0x75985ab0ac
	public Void Unregister(ISponsor obj) { }
	// RVA: 0x5f931f0 VA: 0x75985ab1f0
	internal Void UpdateState() { }
	// RVA: 0x5f9339c VA: 0x75985ab39c
	private Void CheckNextSponsor() { }
	// RVA: 0x5f9376c VA: 0x75985ab76c
	private Void ProcessSponsorResponse(Object state, Boolean timedOut) { }
}
```