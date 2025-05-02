# Act1D5ResHolder

**Namespace:** `Torappu.Activity.Act1D5`


## Fields

- `Sprite _homeSprite`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1D5
public class Act1D5ResHolder : ActivityResHolder, IHotfixable
{
	private Sprite _homeSprite; // 0x18
	private static DelegateBridge __Hotfix0_get_topbarSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_homeSprite; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Sprite topbarSprite { get; }
	public override Sprite homeSprite { get; }

	// RVA: 0x33e340c VA: 0x75959fb40c
	public override Sprite get_topbarSprite() { }
	// RVA: 0x33e3474 VA: 0x75959fb474
	public override Sprite get_homeSprite() { }
	// RVA: 0x33e34d8 VA: 0x75959fb4d8
	public Void .ctor() { }
}
```