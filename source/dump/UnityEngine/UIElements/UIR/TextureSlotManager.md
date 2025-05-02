# TextureSlotManager

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `Int32 m_CurrentTicket`

- `Int32 m_FirstUsedTicket`

- `Int32 <FreeSlots>k__BackingField`


## Properties

- `Int32 FreeSlots`


## Methods

- `Void Reset()`

- `Void StartNewBatch()`

- `Int32 IndexOf(TextureId)`

- `Void MarkUsed(Int32)`

- `Int32 get_FreeSlots()`

- `Void set_FreeSlots(Int32)`

- `Int32 FindOldestSlot()`

- `Void Bind(TextureId, Int32, MaterialPropertyBlock)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class TextureSlotManager
{
	private static readonly Int32 k_SlotCount; // 0x0
	internal static readonly Int32[] slotIds; // 0x8
	internal static readonly Int32 textureTableId; // 0x10
	private TextureId[] m_Textures; // 0x10
	private Int32[] m_Tickets; // 0x18
	private Int32 m_CurrentTicket; // 0x20
	private Int32 m_FirstUsedTicket; // 0x24
	private Vector4[] m_GpuTextures; // 0x28
	private Int32 <FreeSlots>k__BackingField; // 0x30
	internal TextureRegistry textureRegistry; // 0x38

	public Int32 FreeSlots { get; set; }

	// RVA: 0x69585f4 VA: 0x7598f705f4
	private static Void .cctor() { }
	// RVA: 0x6958970 VA: 0x7598f70970
	public Void .ctor() { }
	// RVA: 0x6958b04 VA: 0x7598f70b04
	public Void Reset() { }
	// RVA: 0x6958c30 VA: 0x7598f70c30
	public Void StartNewBatch() { }
	// RVA: 0x6958c9c VA: 0x7598f70c9c
	public Int32 IndexOf(TextureId id) { }
	// RVA: 0x6958d94 VA: 0x7598f70d94
	public Void MarkUsed(Int32 slotIndex) { }
	// RVA: 0x6958dec VA: 0x7598f70dec
	public Int32 get_FreeSlots() { }
	// RVA: 0x6958df4 VA: 0x7598f70df4
	private Void set_FreeSlots(Int32 value) { }
	// RVA: 0x6958dfc VA: 0x7598f70dfc
	public Int32 FindOldestSlot() { }
	// RVA: 0x6958ecc VA: 0x7598f70ecc
	public Void Bind(TextureId id, Int32 slot, MaterialPropertyBlock mat) { }
}
```