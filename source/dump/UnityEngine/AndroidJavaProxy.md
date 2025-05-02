# AndroidJavaProxy

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : UnityEngine
public class AndroidJavaProxy
{
	public readonly AndroidJavaClass javaInterface; // 0x10
	internal IntPtr proxyObject; // 0x18
	private static readonly GlobalJavaObjectRef s_JavaLangSystemClass; // 0x0
	private static readonly IntPtr s_HashCodeMethodID; // 0x8


	// RVA: 0x68345f0 VA: 0x7598e4c5f0
	public Void .ctor(String javaInterface) { }
	// RVA: 0x68346bc VA: 0x7598e4c6bc
	public Void .ctor(AndroidJavaClass javaInterface) { }
	// RVA: 0x6834730 VA: 0x7598e4c730
	protected override Void Finalize() { }
	// RVA: 0x6834854 VA: 0x7598e4c854
	public virtual AndroidJavaObject Invoke(String methodName, Object[] args) { }
	// RVA: 0x6835f6c VA: 0x7598e4df6c
	public virtual AndroidJavaObject Invoke(String methodName, AndroidJavaObject[] javaArgs) { }
	// RVA: 0x6836a58 VA: 0x7598e4ea58
	public virtual Boolean equals(AndroidJavaObject obj) { }
	// RVA: 0x6836bb0 VA: 0x7598e4ebb0
	public virtual Int32 hashCode() { }
	// RVA: 0x6836d18 VA: 0x7598e4ed18
	public virtual String toString() { }
	// RVA: 0x6836d7c VA: 0x7598e4ed7c
	internal AndroidJavaObject GetProxyObject() { }
	// RVA: 0x6835d1c VA: 0x7598e4dd1c
	internal IntPtr GetRawProxy() { }
	// RVA: 0x683708c VA: 0x7598e4f08c
	private static Void .cctor() { }
}
```