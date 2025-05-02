# Act12sideResHolder

**Namespace:** `Torappu.Activity.Act12side.UI`


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
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideResHolder : ActivityResHolder
{
	private Sprite _homeSprite; // 0x18
	private Sprite _homeMultiSprite; // 0x20
	private ZoneHomeRes _zoneHome; // 0x28
	private static DelegateBridge __Hotfix0_get_homeSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_homeSpriteMultiMode; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneHomeRes; // 0x10
	private static DelegateBridge __Hotfix0_get_topbarSprite; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Sprite homeSprite { get; }
	public override Sprite homeSpriteMultiMode { get; }
	public override ZoneHomeRes zoneHomeRes { get; }
	public override Sprite topbarSprite { get; }

	// RVA: 0x344ba00 VA: 0x7595a63a00
	public override Sprite get_homeSprite() { }
	// RVA: 0x344ba68 VA: 0x7595a63a68
	public override Sprite get_homeSpriteMultiMode() { }
	// RVA: 0x344bad8 VA: 0x7595a63ad8
	public override ZoneHomeRes get_zoneHomeRes() { }
	// RVA: 0x344bb68 VA: 0x7595a63b68
	public override Sprite get_topbarSprite() { }
	// RVA: 0x344bbcc VA: 0x7595a63bcc
	public Void .ctor() { }
	// RVA: 0x344bc84 VA: 0x7595a63c84
	private Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode() { }
	// RVA: 0x344bc8c VA: 0x7595a63c8c
	private ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes() { }
}
```