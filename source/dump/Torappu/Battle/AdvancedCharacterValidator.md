# AdvancedCharacterValidator

**Namespace:** `Torappu.Battle`


## Fields

- `BuildableType _buildableType`

- `Boolean _checkDeployPosition`

- `BuildableType _deployPositionFromData`

- `RarityRankMask _rarityMask`


## Properties

- `Boolean checkDeployPosition`


## Methods

- `Boolean get_checkDeployPosition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedCharacterValidator : TargetValidator
{
	private BuildableType _buildableType; // 0x8c
	private Boolean _checkDeployPosition; // 0x90
	private BuildableType _deployPositionFromData; // 0x94
	private RarityRankMask _rarityMask; // 0x98

	protected Boolean checkDeployPosition { get; }

	// RVA: 0x1bda178 VA: 0x75941f2178
	protected Boolean get_checkDeployPosition() { }
	// RVA: 0x1bda180 VA: 0x75941f2180
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bda418 VA: 0x75941f2418
	public Void .ctor() { }
}
```