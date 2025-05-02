# Act27SideAnimatorTrigger

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _allySideTypeKey`

- `String _enemySideTypeKey`

- `String _endKey`

- `Act27SideBattleManager m_manager`

- `Tile m_tile`


## Properties

- `Tile effectHolder`

- `Act27SideBattleManager manager`


## Methods

- `Tile get_effectHolder()`

- `Act27SideBattleManager get_manager()`

- `String <>xLuaBaseProxy_GetValueOnPlay()`

- `String <>xLuaBaseProxy_GetValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class Act27SideAnimatorTrigger : AnimatorTriggerSource
{
	private String _allySideTypeKey; // 0x20
	private String _enemySideTypeKey; // 0x28
	private String _endKey; // 0x30
	private Act27SideBattleManager m_manager; // 0x38
	private Tile m_tile; // 0x40
	private static DelegateBridge __Hotfix0_get_effectHolder; // 0x0
	private static DelegateBridge __Hotfix0_get_manager; // 0x8
	private static DelegateBridge __Hotfix0_GetValueOnPlay; // 0x10
	private static DelegateBridge __Hotfix0_GetValue; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Tile effectHolder { get; }
	private Act27SideBattleManager manager { get; }

	// RVA: 0x1ff5d74 VA: 0x759460dd74
	private Tile get_effectHolder() { }
	// RVA: 0x1ff5ee0 VA: 0x759460dee0
	private Act27SideBattleManager get_manager() { }
	// RVA: 0x1ff6088 VA: 0x759460e088
	public override String GetValueOnPlay() { }
	// RVA: 0x1ff6184 VA: 0x759460e184
	public override String GetValue() { }
	// RVA: 0x1ff6250 VA: 0x759460e250
	public Void .ctor() { }
	// RVA: 0x1ff6328 VA: 0x759460e328
	private String <>xLuaBaseProxy_GetValueOnPlay() { }
	// RVA: 0x1ff632c VA: 0x759460e32c
	private String <>xLuaBaseProxy_GetValue() { }
}
```