# Activity5D1ResHolder

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Sprite _homeSprite`

- `Sprite _zoneTabSprite`

- `ZoneHomeRes _zoneHomeRes`


## Methods

- `ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Activity5D1ResHolder : ActivityResHolder
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

	// RVA: 0x31c66b8 VA: 0x75957de6b8
	public override Sprite get_topbarSprite() { }
	// RVA: 0x31c671c VA: 0x75957de71c
	public override Sprite get_homeSprite() { }
	// RVA: 0x31c6784 VA: 0x75957de784
	public override ZoneHomeRes get_zoneHomeRes() { }
	// RVA: 0x31c6814 VA: 0x75957de814
	public Void .ctor() { }
	// RVA: 0x31c6884 VA: 0x75957de884
	private ZoneHomeRes <>xLuaBaseProxy_get_zoneHomeRes() { }
}
```