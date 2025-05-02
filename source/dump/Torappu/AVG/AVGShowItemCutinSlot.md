# AVGShowItemCutinSlot

**Namespace:** `Torappu.AVG`


## Fields

- `Single _defaultFadeTime`

- `RectTransform _offsetTransform`

- `RectTransform _maskRectTransform`

- `FadeStyle _showFadeStyle`


## Methods

- `Void <>xLuaBaseProxy_Show(Command, Sprite, Action)`

- `Void <>xLuaBaseProxy_Hide(Command, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGShowItemCutinSlot : AVGShowItemSlot
{
	private Single _defaultFadeTime; // 0x40
	private RectTransform _offsetTransform; // 0x48
	private RectTransform _maskRectTransform; // 0x50
	private FadeStyle _showFadeStyle; // 0x58
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0__InitSlot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3ea9db8 VA: 0x75964c1db8
	public override Void Show(Command command, Sprite sprite, Action onShowEnd) { }
	// RVA: 0x3eaa518 VA: 0x75964c2518
	public override Void Hide(Command command, Action onShowEnd) { }
	// RVA: 0x3eaa7a4 VA: 0x75964c27a4
	protected override Void _InitSlot() { }
	// RVA: 0x3eaa808 VA: 0x75964c2808
	public Void .ctor() { }
	// RVA: 0x3eaa8f8 VA: 0x75964c28f8
	private Void <>xLuaBaseProxy_Show(Command P0, Sprite P1, Action P2) { }
	// RVA: 0x3eaa8fc VA: 0x75964c28fc
	private Void <>xLuaBaseProxy_Hide(Command P0, Action P1) { }
}
```