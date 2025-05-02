# Act1LockResHolder

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Sprite _homeSprite`

- `Sprite _homeMultiSprite`

- `ZoneHomeRes _zoneHome`


## Methods

- `Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode()`

- `ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockResHolder : ActivityResHolder
{
	private Sprite _homeSprite; // 0x18
	private Sprite _homeMultiSprite; // 0x20
	private ZoneHomeRes _zoneHome; // 0x28
	private static DelegateBridge __Hotfix0_get_homeSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_homeSpriteMultiMode; // 0x8
	private static DelegateBridge __Hotfix0_get_topbarSprite; // 0x10
	private static DelegateBridge __Hotfix0_get_zoneHomeRes; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Sprite homeSprite { get; }
	public override Sprite homeSpriteMultiMode { get; }
	public override Sprite topbarSprite { get; }
	public override ZoneHomeRes zoneHomeRes { get; }

	// RVA: 0x339b1b4 VA: 0x75959b31b4
	public override Sprite get_homeSprite() { }
	// RVA: 0x339b21c VA: 0x75959b321c
	public override Sprite get_homeSpriteMultiMode() { }
	// RVA: 0x339b28c VA: 0x75959b328c
	public override Sprite get_topbarSprite() { }
	// RVA: 0x339b2f0 VA: 0x75959b32f0
	public override ZoneHomeRes get_zoneHomeRes() { }
	// RVA: 0x339b380 VA: 0x75959b3380
	public Void .ctor() { }
	// RVA: 0x339b438 VA: 0x75959b3438
	private Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode() { }
	// RVA: 0x339b440 VA: 0x75959b3440
	private ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes() { }
}
```