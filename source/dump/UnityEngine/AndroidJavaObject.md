# AndroidJavaObject

**Namespace:** `UnityEngine`


## Methods

- `Void Dispose()`

- `Void Call(String, T[])`

- `Void Call(String, Object[])`

- `Void CallStatic(String, T[])`

- `Void CallStatic(String, Object[])`

- `FieldType Get(String)`

- `Void Set(String, FieldType)`

- `FieldType GetStatic(String)`

- `Void SetStatic(String, FieldType)`

- `IntPtr GetRawObject()`

- `IntPtr GetRawClass()`

- `AndroidJavaObject CloneReference()`

- `ReturnType Call(String, T[])`

- `ReturnType Call(String, Object[])`

- `ReturnType CallStatic(String, T[])`

- `ReturnType CallStatic(String, Object[])`

- `Void DebugPrint(String)`

- `Void DebugPrint(String, String, String, Object[])`

- `Void _AndroidJavaObject(String, Object[])`

- `Void _Call(String, Object[])`

- `ReturnType _Call(String, Object[])`

- `FieldType _Get(String)`

- `Void _Set(String, FieldType)`

- `Void _CallStatic(String, Object[])`

- `ReturnType _CallStatic(String, Object[])`

- `FieldType _GetStatic(String)`

- `Void _SetStatic(String, FieldType)`

- `IntPtr _GetRawObject()`

- `IntPtr _GetRawClass()`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : UnityEngine
public class AndroidJavaObject : IDisposable
{
	private static Boolean enableDebugPrints; // 0x0
	internal GlobalJavaObjectRef m_jobject; // 0x10
	internal GlobalJavaObjectRef m_jclass; // 0x18


	// RVA: 0x6837238 VA: 0x7598e4f238
	public Void .ctor(String className, String[] args) { }
	// RVA: 0x6837524 VA: 0x7598e4f524
	public Void .ctor(String className, AndroidJavaObject[] args) { }
	// RVA: 0x68375e4 VA: 0x7598e4f5e4
	public Void .ctor(String className, AndroidJavaClass[] args) { }
	// RVA: 0x68376a4 VA: 0x7598e4f6a4
	public Void .ctor(String className, AndroidJavaProxy[] args) { }
	// RVA: 0x6837764 VA: 0x7598e4f764
	public Void .ctor(String className, AndroidJavaRunnable[] args) { }
	// RVA: 0x6837824 VA: 0x7598e4f824
	public Void .ctor(String className, Object[] args) { }
	// RVA: 0x68369ec VA: 0x7598e4e9ec
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	public Void Call(String methodName, T[] args) { }
	// RVA: 0x6837858 VA: 0x7598e4f858
	public Void Call(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	public Void CallStatic(String methodName, T[] args) { }
	// RVA: 0x6837998 VA: 0x7598e4f998
	public Void CallStatic(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	public FieldType Get(String fieldName) { }
	// RVA: 0x VA: 0x0
	public Void Set(String fieldName, FieldType val) { }
	// RVA: 0x VA: 0x0
	public FieldType GetStatic(String fieldName) { }
	// RVA: 0x VA: 0x0
	public Void SetStatic(String fieldName, FieldType val) { }
	// RVA: 0x6836b10 VA: 0x7598e4eb10
	public IntPtr GetRawObject() { }
	// RVA: 0x6837b34 VA: 0x7598e4fb34
	public IntPtr GetRawClass() { }
	// RVA: 0x6837b6c VA: 0x7598e4fb6c
	public AndroidJavaObject CloneReference() { }
	// RVA: 0x VA: 0x0
	public ReturnType Call(String methodName, T[] args) { }
	// RVA: 0x VA: 0x0
	public ReturnType Call(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	public ReturnType CallStatic(String methodName, T[] args) { }
	// RVA: 0x VA: 0x0
	public ReturnType CallStatic(String methodName, Object[] args) { }
	// RVA: 0x6837dec VA: 0x7598e4fdec
	protected Void DebugPrint(String msg) { }
	// RVA: 0x6837e74 VA: 0x7598e4fe74
	protected Void DebugPrint(String call, String methodName, String signature, Object[] args) { }
	// RVA: 0x6837300 VA: 0x7598e4f300
	private Void _AndroidJavaObject(String className, Object[] args) { }
	// RVA: 0x68383b8 VA: 0x7598e503b8
	internal Void .ctor(IntPtr jobject) { }
	// RVA: 0x68372f8 VA: 0x7598e4f2f8
	internal Void .ctor() { }
	// RVA: 0x6838594 VA: 0x7598e50594
	protected override Void Finalize() { }
	// RVA: 0x6838634 VA: 0x7598e50634
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x683785c VA: 0x7598e4f85c
	protected Void _Call(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	protected ReturnType _Call(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	protected FieldType _Get(String fieldName) { }
	// RVA: 0x VA: 0x0
	protected Void _Set(String fieldName, FieldType val) { }
	// RVA: 0x683799c VA: 0x7598e4f99c
	protected Void _CallStatic(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	protected ReturnType _CallStatic(String methodName, Object[] args) { }
	// RVA: 0x VA: 0x0
	protected FieldType _GetStatic(String fieldName) { }
	// RVA: 0x VA: 0x0
	protected Void _SetStatic(String fieldName, FieldType val) { }
	// RVA: 0x6836d8c VA: 0x7598e4ed8c
	internal static AndroidJavaObject AndroidJavaObjectDeleteLocalRef(IntPtr jobject) { }
	// RVA: 0x6838840 VA: 0x7598e50840
	internal static AndroidJavaClass AndroidJavaClassDeleteLocalRef(IntPtr jclass) { }
	// RVA: 0x VA: 0x0
	internal static ReturnType FromJavaArrayDeleteLocalRef(IntPtr jobject) { }
	// RVA: 0x6837ad8 VA: 0x7598e4fad8
	protected IntPtr _GetRawObject() { }
	// RVA: 0x6837b50 VA: 0x7598e4fb50
	protected IntPtr _GetRawClass() { }
}
```