# ViewHitRangeProvider

**Namespace:** ` `


## Fields

- `FP tileRadius`

- `TargetOptions selectedTargetOption`


## Properties

- `String providerId`


## Methods

- `Boolean IsInHitRange(HitRangeOption)`

- `Boolean IsTargetIn(HitRangeOption)`

- `String get_providerId()`

- `Boolean _CheckHitRangeWithView2Block(HitRangeOption)`

- `Boolean _IsGridBlockedByView2Block(TSVector2, FP, TSVector2)`

- `Void _GetGridsOnLine(TSVector2, TSVector2, ref)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ViewHitRangeProvider : IHitRangeProvider, IHotfixable, IDisposable
{
	private const String VIEW_HIT_RANGE_PROVIDER; // 0x0
	private static List`1 s_sharedPos; // 0x0
	public FP tileRadius; // 0x10
	public TargetOptions selectedTargetOption; // 0x18
	public List`1 specialAllowedTag; // 0x78
	public List`1 specialUnviewedBuffKey; // 0x80
	private static DelegateBridge __Hotfix0_IsInHitRange; // 0x8
	private static DelegateBridge __Hotfix0_IsTargetIn; // 0x10
	private static DelegateBridge __Hotfix0_get_providerId; // 0x18
	private static DelegateBridge __Hotfix0__CheckHitRangeWithView2Block; // 0x20
	private static DelegateBridge __Hotfix0__IsGridBlockedByView2Block; // 0x28
	private static DelegateBridge __Hotfix0__GetGridsOnLine; // 0x30
	private static DelegateBridge __Hotfix0_Dispose; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String providerId { get; }

	// RVA: 0x40267d8 VA: 0x759663e7d8
	public Boolean IsInHitRange(HitRangeOption option) { }
	// RVA: 0x4026bd8 VA: 0x759663ebd8
	public Boolean IsTargetIn(HitRangeOption option) { }
	// RVA: 0x40263e8 VA: 0x759663e3e8
	public String get_providerId() { }
	// RVA: 0x40268a0 VA: 0x759663e8a0
	public Boolean _CheckHitRangeWithView2Block(HitRangeOption option) { }
	// RVA: 0x4026ca0 VA: 0x759663eca0
	private Boolean _IsGridBlockedByView2Block(TSVector2 center, FP radius, TSVector2 gridCenter) { }
	// RVA: 0x4027688 VA: 0x759663f688
	private Void _GetGridsOnLine(TSVector2 start, TSVector2 end, ref List`1 grids) { }
	// RVA: 0x40264e4 VA: 0x759663e4e4
	public Void Dispose() { }
	// RVA: 0x40266cc VA: 0x759663e6cc
	public Void .ctor() { }
	// RVA: 0x4027964 VA: 0x759663f964
	private static Void .cctor() { }
}
```