# fiDropdownMetadata

**Namespace:** `FullInspector`


## Fields

- `fiAnimBool _isActive`

- `Boolean _showDropdown`

- `Boolean _invertedDefaultState`

- `Boolean _forceDisable`

- `Boolean _serializedIsActive`


## Properties

- `Boolean IsActive`

- `Single AnimPercentage`

- `Boolean IsAnimating`

- `Boolean ShouldDisplayDropdownArrow`


## Methods

- `Boolean get_IsActive()`

- `Void set_IsActive(Boolean)`

- `Single get_AnimPercentage()`

- `Boolean get_IsAnimating()`

- `Boolean get_ShouldDisplayDropdownArrow()`

- `Void set_ShouldDisplayDropdownArrow(Boolean)`

- `Void InvertDefaultState()`

- `Void ForceHideWithoutAnimation()`

- `Void ForceDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class fiDropdownMetadata : IGraphMetadataItemPersistent, ISerializationCallbackReceiver
{
	private fiAnimBool _isActive; // 0x10
	private Boolean _showDropdown; // 0x18
	private Boolean _invertedDefaultState; // 0x19
	private Boolean _forceDisable; // 0x1a
	private Boolean _serializedIsActive; // 0x1b

	public Boolean IsActive { get; set; }
	public Single AnimPercentage { get; }
	public Boolean IsAnimating { get; }
	public Boolean ShouldDisplayDropdownArrow { get; set; }

	// RVA: 0x34d5ccc VA: 0x7595aedccc
	public Boolean get_IsActive() { }
	// RVA: 0x34d5d1c VA: 0x7595aedd1c
	public Void set_IsActive(Boolean value) { }
	// RVA: 0x34d5e78 VA: 0x7595aede78
	public Single get_AnimPercentage() { }
	// RVA: 0x34d5ec4 VA: 0x7595aedec4
	public Boolean get_IsAnimating() { }
	// RVA: 0x34d5f0c VA: 0x7595aedf0c
	public Boolean get_ShouldDisplayDropdownArrow() { }
	// RVA: 0x34d5f2c VA: 0x7595aedf2c
	public Void set_ShouldDisplayDropdownArrow(Boolean value) { }
	// RVA: 0x34d5f48 VA: 0x7595aedf48
	public Void InvertDefaultState() { }
	// RVA: 0x34d5f54 VA: 0x7595aedf54
	public Void ForceHideWithoutAnimation() { }
	// RVA: 0x34d5fc8 VA: 0x7595aedfc8
	public Void ForceDisable() { }
	// RVA: 0x34d5fd4 VA: 0x7595aedfd4
	private Void UnityEngine.ISerializationCallbackReceiver.OnBeforeSerialize() { }
	// RVA: 0x34d5ff0 VA: 0x7595aedff0
	private Void UnityEngine.ISerializationCallbackReceiver.OnAfterDeserialize() { }
	// RVA: 0x34d6060 VA: 0x7595aee060
	private Boolean FullInspector.IGraphMetadataItemPersistent.ShouldSerialize() { }
	// RVA: 0x34d6084 VA: 0x7595aee084
	public Void .ctor() { }
}
```