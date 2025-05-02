# ColorModifier

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Color _color`

- `Boolean _pauseIfOwnerDisappear`


## Properties

- `Color color`


## Methods

- `Color get_color()`

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_OnPaused(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class ColorModifier : Behaviour
{
	private Color _color; // 0x20
	private Boolean _pauseIfOwnerDisappear; // 0x30
	private static DelegateBridge __Hotfix0_get_color; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge __Hotfix0_OnPaused; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Color color { get; }

	// RVA: 0x1ff9840 VA: 0x7594611840
	public Color get_color() { }
	// RVA: 0x1ff98a8 VA: 0x75946118a8
	public override Void OnPlay() { }
	// RVA: 0x1ff9988 VA: 0x7594611988
	private Void Update() { }
	// RVA: 0x1ff9a68 VA: 0x7594611a68
	public override Void OnFinish() { }
	// RVA: 0x1ff9b48 VA: 0x7594611b48
	public override Void OnPaused(Boolean paused) { }
	// RVA: 0x1ff9c54 VA: 0x7594611c54
	public Void .ctor() { }
	// RVA: 0x1ff9cd0 VA: 0x7594611cd0
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff9cd4 VA: 0x7594611cd4
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x1ff9cd8 VA: 0x7594611cd8
	private Void <>xLuaBaseProxy_OnPaused(Boolean P0) { }
}
```