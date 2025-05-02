# Activity5D0ResHolder

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Sprite _homeSprite`

- `Sprite _zoneTabSprite`

- `ZoneHomeRes _zoneHomeRes`


## Methods

- `ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Activity5D0ResHolder : ActivityResHolder, IHotfixable
{
	private Sprite _homeSprite; // 0x18
	private Sprite _zoneTabSprite; // 0x20
	private ZoneHomeRes _zoneHomeRes; // 0x28
	private static DelegateBridge __Hotfix0_get_topbarSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_homeSprite; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneHomeRes; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Sprite topbarSprite { get; }
	public override Sprite homeSprite { get; }
	public override ZoneHomeRes zoneHomeRes { get; }

	// RVA: 0x31bdb68 VA: 0x75957d5b68
	public override Sprite get_topbarSprite() { }
	// RVA: 0x31bdbcc VA: 0x75957d5bcc
	public override Sprite get_homeSprite() { }
	// RVA: 0x31bdc34 VA: 0x75957d5c34
	public override ZoneHomeRes get_zoneHomeRes() { }
	// RVA: 0x31bdcc4 VA: 0x75957d5cc4
	public Void .ctor() { }
	// RVA: 0x31bdd34 VA: 0x75957d5d34
	private ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes() { }
}
```