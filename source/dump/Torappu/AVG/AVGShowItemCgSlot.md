# AVGShowItemCgSlot

**Namespace:** `Torappu.AVG`


## Fields

- `Single _defaultFadeTime`

- `Canvas _canvas`


## Methods

- `Void _OverrideLayer(Int32)`

- `Vector3 _GenPosByRaw(String)`

- `Color _GenColorByRaw(String)`

- `Void <>xLuaBaseProxy_Show(Command, Sprite, Action)`

- `Void <>xLuaBaseProxy_Hide(Command, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGShowItemCgSlot : AVGShowItemSlot
{
	private Single _defaultFadeTime; // 0x40
	private Canvas _canvas; // 0x48
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0__OverrideLayer; // 0x10
	private static DelegateBridge __Hotfix0__GenPosByRaw; // 0x18
	private static DelegateBridge __Hotfix0__GenColorByRaw; // 0x20
	private static DelegateBridge __Hotfix0__InitSlot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3ea8b74 VA: 0x75964c0b74
	public override Void Show(Command command, Sprite sprite, Action onShowEnd) { }
	// RVA: 0x3ea9a38 VA: 0x75964c1a38
	public override Void Hide(Command command, Action onShowEnd) { }
	// RVA: 0x3ea96c8 VA: 0x75964c16c8
	private Void _OverrideLayer(Int32 layer) { }
	// RVA: 0x3ea97c0 VA: 0x75964c17c0
	private Vector3 _GenPosByRaw(String rawPos) { }
	// RVA: 0x3ea98fc VA: 0x75964c18fc
	private Color _GenColorByRaw(String rawColor) { }
	// RVA: 0x3ea9cc8 VA: 0x75964c1cc8
	protected override Void _InitSlot() { }
	// RVA: 0x3ea9d2c VA: 0x75964c1d2c
	public Void .ctor() { }
	// RVA: 0x3ea9da8 VA: 0x75964c1da8
	private Void <>xLuaBaseProxy_Show(Command P0, Sprite P1, Action P2) { }
	// RVA: 0x3ea9db0 VA: 0x75964c1db0
	private Void <>xLuaBaseProxy_Hide(Command P0, Action P1) { }
}
```