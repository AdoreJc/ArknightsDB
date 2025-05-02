# RangeIdHitRangeProvider

**Namespace:** ` `


## Fields

- `RangeData m_data`


## Properties

- `String providerId`


## Methods

- `String get_providerId()`

- `Boolean IsInHitRange(HitRangeOption)`

- `Boolean IsTargetIn(HitRangeOption)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RangeIdHitRangeProvider : IHitRangeProvider, IHotfixable
{
	public const String RANGE_ID_HIT_RANGE_CHECKER_PROVIDER; // 0x0
	private RangeData m_data; // 0x10
	private ObjectPtr`1 m_owner; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_providerId; // 0x8
	private static DelegateBridge __Hotfix0_IsInHitRange; // 0x10
	private static DelegateBridge __Hotfix0_IsTargetIn; // 0x18

	public String providerId { get; }

	// RVA: 0x1c31eac VA: 0x7594249eac
	public Void .ctor(ObjectPtr`1 owner) { }
	// RVA: 0x1c368b0 VA: 0x759424e8b0
	public String get_providerId() { }
	// RVA: 0x1c3692c VA: 0x759424e92c
	public Boolean IsInHitRange(HitRangeOption option) { }
	// RVA: 0x1c36b98 VA: 0x759424eb98
	public Boolean IsTargetIn(HitRangeOption option) { }
}
```