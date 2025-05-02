# Gyroscope

**Namespace:** `UnityEngine`


## Fields

- `Int32 m_GyroIndex`


## Properties

- `Vector3 rotationRateUnbiased`

- `Boolean enabled`

- `Single updateInterval`


## Methods

- `Vector3 get_rotationRateUnbiased()`

- `Void set_enabled(Boolean)`

- `Void set_updateInterval(Single)`


## Dump
```C#
// Dll : UnityEngine.InputLegacyModule.dll
// Namespace : UnityEngine
public class Gyroscope
{
	private Int32 m_GyroIndex; // 0x10

	public Vector3 rotationRateUnbiased { get; }
	public Boolean enabled { set; }
	public Single updateInterval { set; }

	// RVA: 0x68ce5d0 VA: 0x7598ee65d0
	internal Void .ctor(Int32 index) { }
	// RVA: 0x68ce5f8 VA: 0x7598ee65f8
	private static Vector3 rotationRateUnbiased_Internal(Int32 idx) { }
	// RVA: 0x68ce698 VA: 0x7598ee6698
	private static Void setEnabled_Internal(Int32 idx, Boolean enabled) { }
	// RVA: 0x68ce6dc VA: 0x7598ee66dc
	private static Void setUpdateInterval_Internal(Int32 idx, Single interval) { }
	// RVA: 0x68ce728 VA: 0x7598ee6728
	public Vector3 get_rotationRateUnbiased() { }
	// RVA: 0x68ce730 VA: 0x7598ee6730
	public Void set_enabled(Boolean value) { }
	// RVA: 0x68ce774 VA: 0x7598ee6774
	public Void set_updateInterval(Single value) { }
	// RVA: 0x68ce654 VA: 0x7598ee6654
	private static Void rotationRateUnbiased_Internal_Injected(Int32 idx, out Vector3 ret) { }
}
```