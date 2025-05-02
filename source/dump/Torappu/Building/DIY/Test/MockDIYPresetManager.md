# MockDIYPresetManager

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `Int32 _slotCount`


## Properties

- `Int32 slotCount`


## Methods

- `Void Setup()`

- `Int32 get_slotCount()`

- `IDIYPreset GetPreset(Int32)`

- `Boolean SetPreset(Int32, IDIYPreset, String, Action`1)`

- `Void RenamePreset(Int32, String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockDIYPresetManager : MonoBehaviour, IDIYPresetManager, IDIYPresetProvider
{
	private Preset[] _presets; // 0x18
	private Int32 _slotCount; // 0x20
	private IDIYPreset[] m_presetItems; // 0x28

	public Int32 slotCount { get; }

	// RVA: 0x37f2edc VA: 0x7595e0aedc
	public Void Setup() { }
	// RVA: 0x37f31b0 VA: 0x7595e0b1b0
	public Int32 get_slotCount() { }
	// RVA: 0x37f31b8 VA: 0x7595e0b1b8
	public IDIYPreset GetPreset(Int32 index) { }
	// RVA: 0x37f3208 VA: 0x7595e0b208
	public Boolean SetPreset(Int32 index, IDIYPreset preset, String imageBase64, Action`1 resultHandler) { }
	// RVA: 0x37f32b4 VA: 0x7595e0b2b4
	public Void RenamePreset(Int32 index, String newName, Action`1 resultHandler) { }
	// RVA: 0x37f3304 VA: 0x7595e0b304
	public Void .ctor() { }
}
```