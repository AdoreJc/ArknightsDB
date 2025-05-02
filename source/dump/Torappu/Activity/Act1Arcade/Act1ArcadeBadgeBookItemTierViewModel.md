# Act1ArcadeBadgeBookItemTierViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `String tierId`

- `Int32 sortId`

- `String iconId`

- `String shareIconId`

- `String effectId`

- `String title`

- `String desc`

- `String rawUnlockDesc`

- `PackedRuneData runeData`

- `Boolean unlocked`

- `String <unlockDesc>k__BackingField`

- `Int32 <unlockProgress>k__BackingField`

- `Int32 <unlockTarget>k__BackingField`


## Properties

- `String unlockDesc`

- `Int32 unlockProgress`

- `Int32 unlockTarget`


## Methods

- `String get_unlockDesc()`

- `Void set_unlockDesc(String)`

- `Int32 get_unlockProgress()`

- `Void set_unlockProgress(Int32)`

- `Int32 get_unlockTarget()`

- `Void set_unlockTarget(Int32)`

- `Int32 CompareTo(Act1ArcadeBadgeBookItemTierViewModel)`

- `String GetUnlockDescWithHighlightColor(Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookItemTierViewModel : IComparable`1, IHotfixable
{
	public String tierId; // 0x10
	public Int32 sortId; // 0x18
	public String iconId; // 0x20
	public String shareIconId; // 0x28
	public String effectId; // 0x30
	public String title; // 0x38
	public String desc; // 0x40
	public String rawUnlockDesc; // 0x48
	public PackedRuneData runeData; // 0x50
	public Boolean unlocked; // 0x58
	private String <unlockDesc>k__BackingField; // 0x60
	private Int32 <unlockProgress>k__BackingField; // 0x68
	private Int32 <unlockTarget>k__BackingField; // 0x6c
	private static DelegateBridge __Hotfix0_get_unlockDesc; // 0x0
	private static DelegateBridge __Hotfix0_set_unlockDesc; // 0x8
	private static DelegateBridge __Hotfix0_get_unlockProgress; // 0x10
	private static DelegateBridge __Hotfix0_set_unlockProgress; // 0x18
	private static DelegateBridge __Hotfix0_get_unlockTarget; // 0x20
	private static DelegateBridge __Hotfix0_set_unlockTarget; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x30
	private static DelegateBridge __Hotfix0_GetUnlockDescWithHighlightColor; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private String unlockDesc { get; set; }
	private Int32 unlockProgress { get; set; }
	private Int32 unlockTarget { get; set; }

	// RVA: 0x33fbcdc VA: 0x7595a13cdc
	private String get_unlockDesc() { }
	// RVA: 0x33fbd44 VA: 0x7595a13d44
	public Void set_unlockDesc(String value) { }
	// RVA: 0x33fbdc8 VA: 0x7595a13dc8
	private Int32 get_unlockProgress() { }
	// RVA: 0x33fbe30 VA: 0x7595a13e30
	public Void set_unlockProgress(Int32 value) { }
	// RVA: 0x33fbeac VA: 0x7595a13eac
	private Int32 get_unlockTarget() { }
	// RVA: 0x33fbf14 VA: 0x7595a13f14
	public Void set_unlockTarget(Int32 value) { }
	// RVA: 0x33fbf90 VA: 0x7595a13f90
	public Int32 CompareTo(Act1ArcadeBadgeBookItemTierViewModel other) { }
	// RVA: 0x33fa388 VA: 0x7595a12388
	public String GetUnlockDescWithHighlightColor(Color color) { }
	// RVA: 0x33fc01c VA: 0x7595a1401c
	public Void .ctor() { }
}
```