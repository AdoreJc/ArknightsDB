# StackFrame

**Namespace:** `System.Diagnostics`


## Fields

- `Int32 ilOffset`

- `Int32 nativeOffset`

- `Int64 methodAddress`

- `UInt32 methodIndex`

- `MethodBase methodBase`

- `String fileName`

- `Int32 lineNumber`

- `Int32 columnNumber`

- `String internalMethodName`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Diagnostics
public class StackFrame
{
	public const Int32 OFFSET_UNKNOWN; // 0x0
	private Int32 ilOffset; // 0x10
	private Int32 nativeOffset; // 0x14
	private Int64 methodAddress; // 0x18
	private UInt32 methodIndex; // 0x20
	private MethodBase methodBase; // 0x28
	private String fileName; // 0x30
	private Int32 lineNumber; // 0x38
	private Int32 columnNumber; // 0x3c
	private String internalMethodName; // 0x40


	// RVA: 0x6079750 VA: 0x7598691750
	private static Boolean get_frame_info(Int32 skip, Boolean needFileInfo, out MethodBase method, out Int32 iloffset, out Int32 native_offset, out String file, out Int32 line, out Int32 column) { }
	// RVA: 0x6079758 VA: 0x7598691758
	public Void .ctor() { }
	// RVA: 0x60797a8 VA: 0x75986917a8
	public Void .ctor(Int32 skipFrames, Boolean fNeedFileInfo) { }
	// RVA: 0x6079808 VA: 0x7598691808
	public virtual Int32 GetFileLineNumber() { }
	// RVA: 0x6079810 VA: 0x7598691810
	public virtual String GetFileName() { }
	// RVA: 0x6079818 VA: 0x7598691818
	internal String GetSecureFileName() { }
	// RVA: 0x60798ec VA: 0x75986918ec
	public virtual Int32 GetILOffset() { }
	// RVA: 0x60798f4 VA: 0x75986918f4
	public virtual MethodBase GetMethod() { }
	// RVA: 0x60798fc VA: 0x75986918fc
	public virtual Int32 GetNativeOffset() { }
	// RVA: 0x6079904 VA: 0x7598691904
	internal Int64 GetMethodAddress() { }
	// RVA: 0x607990c VA: 0x759869190c
	internal UInt32 GetMethodIndex() { }
	// RVA: 0x6079914 VA: 0x7598691914
	internal String GetInternalMethodName() { }
	// RVA: 0x607991c VA: 0x759869191c
	public override String ToString() { }
}
```