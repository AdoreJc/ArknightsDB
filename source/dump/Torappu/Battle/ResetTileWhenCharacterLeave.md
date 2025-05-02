# ResetTileWhenCharacterLeave

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _resetTileOptions`

- `Boolean _resetTileMode`


## Methods

- `Void AddExcludeCharacter(Character)`

- `Void RemoveExcludeCharacter(Character)`

- `Void _ResetTile()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ResetTileWhenCharacterLeave : Behaviour
{
	private String[] _excludeKeys; // 0x20
	private Boolean _resetTileOptions; // 0x28
	private Boolean _resetTileMode; // 0x29
	private List`1 m_excludeCharacters; // 0x30


	// RVA: 0x4086898 VA: 0x759669e898
	public override Void Init(Tile tile) { }
	// RVA: 0x4086924 VA: 0x759669e924
	public override Void OnEntityLeave(Entity entity) { }
	// RVA: 0x4086b7c VA: 0x759669eb7c
	public Void AddExcludeCharacter(Character character) { }
	// RVA: 0x4086cac VA: 0x759669ecac
	public Void RemoveExcludeCharacter(Character character) { }
	// RVA: 0x4086a94 VA: 0x759669ea94
	private Void _ResetTile() { }
	// RVA: 0x4086ef0 VA: 0x759669eef0
	public Void .ctor() { }
}
```