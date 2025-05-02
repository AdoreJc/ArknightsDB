# FurniturePresetManager

**Namespace:** `Torappu.Building.DIY`


## Properties

- `Int32 slotCount`


## Methods

- `Int32 get_slotCount()`

- `Int32 GetServerIndex(Int32)`

- `IDIYPreset GetPreset(Int32)`

- `PlayerBuildingDIYSolution CreatePreset(IDIYPreset)`

- `Boolean SetPreset(Int32, IDIYPreset, String, Action`1)`

- `Void RenamePreset(Int32, String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurniturePresetManager : IDIYPresetManager, IDIYPresetProvider
{

	public Int32 slotCount { get; }

	// RVA: 0x37d3114 VA: 0x7595deb114
	public Int32 get_slotCount() { }
	// RVA: 0x37d319c VA: 0x7595deb19c
	public Int32 GetServerIndex(Int32 index) { }
	// RVA: 0x37d322c VA: 0x7595deb22c
	public IDIYPreset GetPreset(Int32 index) { }
	// RVA: 0x37d3384 VA: 0x7595deb384
	private PlayerBuildingDIYSolution CreatePreset(IDIYPreset origin) { }
	// RVA: 0x37d3a88 VA: 0x7595deba88
	public Boolean SetPreset(Int32 index, IDIYPreset preset, String imageBase64, Action`1 resultHandler) { }
	// RVA: 0x37d3e88 VA: 0x7595debe88
	public Void RenamePreset(Int32 index, String newName, Action`1 resultHandler) { }
	// RVA: 0x37d41a8 VA: 0x7595dec1a8
	public Void .ctor() { }
}
```