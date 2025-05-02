# MapAttachment

**Namespace:** `Torappu.Battle`


## Methods

- `Void OnLocatedCharacterUpdate(Character)`

- `Void OnEntityEnter(Entity)`

- `Void OnEntityLeave(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MapAttachment : MapWidget, ITileListener
{
	private GridPosition[] _attachedTiles; // 0x20

	public GridPosition[] attachedTiles { get; }

	// RVA: 0x4079228 VA: 0x7596691228
	public GridPosition[] get_attachedTiles() { }
	// RVA: 0x4079230 VA: 0x7596691230
	public Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x4079234 VA: 0x7596691234
	public Void OnEntityEnter(Entity entity) { }
	// RVA: 0x4079238 VA: 0x7596691238
	public Void OnEntityLeave(Entity entity) { }
	// RVA: 0x407923c VA: 0x759669123c
	public Void .ctor() { }
}
```