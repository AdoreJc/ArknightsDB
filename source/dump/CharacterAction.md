# CharacterAction

**Namespace:** ` `


## Fields

- `Single timestamp`

- `String charId`

- `PlayerOperationType op`

- `Direction direction`

- `GridPosition pos`


## Methods

- `Int32 CompareTo(CharacterAction)`

- `StringBuilder ToStringBuilder()`

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharacterAction : IComparable`1, IHotfixable
{
	public Single timestamp; // 0x10
	public String charId; // 0x18
	public PlayerOperationType op; // 0x20
	public Direction direction; // 0x24
	public GridPosition pos; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge __Hotfix0_ToStringBuilder; // 0x8
	private static DelegateBridge __Hotfix0_ToString; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f288ac VA: 0x75965408ac
	public Int32 CompareTo(CharacterAction other) { }
	// RVA: 0x3f28938 VA: 0x7596540938
	public StringBuilder ToStringBuilder() { }
	// RVA: 0x3f28bf4 VA: 0x7596540bf4
	public override String ToString() { }
	// RVA: 0x3f28c70 VA: 0x7596540c70
	public Void .ctor() { }
	// RVA: 0x3f28ce0 VA: 0x7596540ce0
	private String <>xLuaBaseProxy_ToString() { }
}
```