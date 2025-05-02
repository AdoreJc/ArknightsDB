# Activity9D0ResHolder

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Sprite _homeSprite`

- `Sprite _homeMultiSprite`

- `ZoneHomeRes _zoneHomeRes`


## Methods

- `Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode()`

- `ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Activity9D0ResHolder : ActivityResHolder, IHotfixable
{
	private Sprite _homeSprite; // 0x18
	private Sprite _homeMultiSprite; // 0x20
	private ZoneHomeRes _zoneHomeRes; // 0x28
	private static DelegateBridge __Hotfix0_get_topbarSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_homeSprite; // 0x8
	private static DelegateBridge __Hotfix0_get_homeSpriteMultiMode; // 0x10
	private static DelegateBridge __Hotfix0_get_zoneHomeRes; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Sprite topbarSprite { get; }
	public override Sprite homeSprite { get; }
	public override Sprite homeSpriteMultiMode { get; }
	public override ZoneHomeRes zoneHomeRes { get; }

	// RVA: 0x319f418 VA: 0x75957b7418
	public override Sprite get_topbarSprite() { }
	// RVA: 0x319f47c VA: 0x75957b747c
	public override Sprite get_homeSprite() { }
	// RVA: 0x319f4e4 VA: 0x75957b74e4
	public override Sprite get_homeSpriteMultiMode() { }
	// RVA: 0x319f590 VA: 0x75957b7590
	public override ZoneHomeRes get_zoneHomeRes() { }
	// RVA: 0x319f620 VA: 0x75957b7620
	public Void .ctor() { }
	// RVA: 0x319f6d8 VA: 0x75957b76d8
	private Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode() { }
	// RVA: 0x319f6e0 VA: 0x75957b76e0
	private ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes() { }
}
```