# GlobalJavaObjectRef

**Namespace:** `UnityEngine`


## Fields

- `Boolean m_disposed`

- `IntPtr m_jobject`


## Methods

- `Void Dispose()`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : UnityEngine
internal class GlobalJavaObjectRef
{
	private Boolean m_disposed; // 0x10
	protected IntPtr m_jobject; // 0x18


	// RVA: 0x68342c4 VA: 0x7598e4c2c4
	public Void .ctor(IntPtr jobject) { }
	// RVA: 0x68343b4 VA: 0x7598e4c3b4
	protected override Void Finalize() { }
	// RVA: 0x68344c4 VA: 0x7598e4c4c4
	public static IntPtr op_Implicit(GlobalJavaObjectRef obj) { }
	// RVA: 0x6834448 VA: 0x7598e4c448
	public Void Dispose() { }
}
```