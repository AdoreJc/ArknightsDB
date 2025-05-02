# DebugLevelBaker

**Namespace:** `Torappu.Battle.DevelopTools`


## Fields

- `String _levelId`

- `MapGraphic _graphicPrefab`

- `TextAsset _levelJson`


## Properties

- `TextAsset levelJson`


## Methods

- `TextAsset get_levelJson()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.DevelopTools
public class DebugLevelBaker : LevelBaker
{
	private String _levelId; // 0x18
	private MapGraphic _graphicPrefab; // 0x20
	private TextAsset _levelJson; // 0x28

	public TextAsset levelJson { get; }
	protected override String outputFolder { get; }

	// RVA: 0x1d2c1b4 VA: 0x75943441b4
	public TextAsset get_levelJson() { }
	// RVA: 0x1d2c1bc VA: 0x75943441bc
	protected override String get_outputFolder() { }
	// RVA: 0x1d2c204 VA: 0x7594344204
	public Void .ctor() { }
}
```