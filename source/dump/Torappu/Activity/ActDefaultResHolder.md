# ActDefaultResHolder

**Namespace:** `Torappu.Activity`


## Fields

- `Sprite _homeSprite`

- `Sprite _homeSpriteMultiMode`

- `Sprite _topbarSprite`


## Methods

- `Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActDefaultResHolder : ActivityResHolder, IHotfixable
{
	private Sprite _homeSprite; // 0x18
	private Sprite _homeSpriteMultiMode; // 0x20
	private Sprite _topbarSprite; // 0x28
	private static DelegateBridge __Hotfix0_get_homeSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_homeSpriteMultiMode; // 0x8
	private static DelegateBridge __Hotfix0_get_topbarSprite; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Sprite homeSprite { get; }
	public override Sprite homeSpriteMultiMode { get; }
	public override Sprite topbarSprite { get; }

	// RVA: 0x30ba6bc VA: 0x75956d26bc
	public override Sprite get_homeSprite() { }
	// RVA: 0x30ba724 VA: 0x75956d2724
	public override Sprite get_homeSpriteMultiMode() { }
	// RVA: 0x30ba78c VA: 0x75956d278c
	public override Sprite get_topbarSprite() { }
	// RVA: 0x30ba7f4 VA: 0x75956d27f4
	public Void .ctor() { }
	// RVA: 0x30ba8d0 VA: 0x75956d28d0
	private Sprite <>xLuaBaseProxy_get_homeSpriteMultiMode() { }
}
```