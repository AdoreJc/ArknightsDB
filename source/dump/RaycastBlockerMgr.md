# RaycastBlockerMgr

**Namespace:** ` `


## Fields

- `RectTransform m_blockMask`

- `Boolean <isTurnedOff>k__BackingField`


## Properties

- `Boolean isTurnedOff`


## Methods

- `Boolean get_isTurnedOff()`

- `Void set_isTurnedOff(Boolean)`

- `Boolean BlockRaycast(Boolean, RaycastBlockerSource)`

- `Boolean _UpdateBlockStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RaycastBlockerMgr
{
	private const Int32 SOURCE_TYPE_NUM; // 0x0
	private RectTransform m_blockMask; // 0x10
	private Boolean[] m_sourceChannels; // 0x18
	private Boolean <isTurnedOff>k__BackingField; // 0x20

	public Boolean isTurnedOff { get; set; }

	// RVA: 0x3565484 VA: 0x7595b7d484
	public Boolean get_isTurnedOff() { }
	// RVA: 0x356548c VA: 0x7595b7d48c
	public Void set_isTurnedOff(Boolean value) { }
	// RVA: 0x3565150 VA: 0x7595b7d150
	public Void .ctor(RectTransform blockMask) { }
	// RVA: 0x356538c VA: 0x7595b7d38c
	public Boolean BlockRaycast(Boolean isBlock, RaycastBlockerSource source) { }
	// RVA: 0x3565498 VA: 0x7595b7d498
	private Boolean _UpdateBlockStatus() { }
}
```