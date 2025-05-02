# Activity10D5ResHolder

**Namespace:** `Torappu.Activity.Act10D5`


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
// Namespace : Torappu.Activity.Act10D5
public class Activity10D5ResHolder : ActivityResHolder, IHotfixable
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

	// RVA: 0x34822a8 VA: 0x7595a9a2a8
	public override Sprite get_topbarSprite() { }
	// RVA: 0x348230c VA: 0x7595a9a30c
	public override Sprite get_homeSprite() { }
	// RVA: 0x3482374 VA: 0x7595a9a374
	public override Sprite get_homeSpriteMultiMode() { }
	// RVA: 0x3482420 VA: 0x7595a9a420
	public override ZoneHomeRes get_zoneHomeRes() { }
	// RVA: 0x34824b0 VA: 0x7595a9a4b0
	public Void .ctor() { }
	// RVA: 0x3482568 VA: 0x7595a9a568
	private Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode() { }
	// RVA: 0x3482570 VA: 0x7595a9a570
	private ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes() { }
}
```