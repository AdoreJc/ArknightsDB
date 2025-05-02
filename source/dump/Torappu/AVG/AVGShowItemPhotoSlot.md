# AVGShowItemPhotoSlot

**Namespace:** `Torappu.AVG`


## Fields

- `Single _defaultFadeTime`


## Methods

- `Void <>xLuaBaseProxy_Show(Command, Sprite, Action)`

- `Void <>xLuaBaseProxy_Hide(Command, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGShowItemPhotoSlot : AVGShowItemSlot
{
	private Single _defaultFadeTime; // 0x40
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0__InitSlot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3eaa900 VA: 0x75964c2900
	public override Void Show(Command command, Sprite sprite, Action onShowEnd) { }
	// RVA: 0x3eaab88 VA: 0x75964c2b88
	public override Void Hide(Command command, Action onShowEnd) { }
	// RVA: 0x3eaad38 VA: 0x75964c2d38
	protected override Void _InitSlot() { }
	// RVA: 0x3eaad9c VA: 0x75964c2d9c
	public Void .ctor() { }
	// RVA: 0x3eaae10 VA: 0x75964c2e10
	private Void <>xLuaBaseProxy_Show(Command P0, Sprite P1, Action P2) { }
	// RVA: 0x3eaae14 VA: 0x75964c2e14
	private Void <>xLuaBaseProxy_Hide(Command P0, Action P1) { }
}
```