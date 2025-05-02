# StackGuard

**Namespace:** `System.Threading.Tasks`


## Fields

- `Int32 m_inliningDepth`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
internal class StackGuard
{
	private Int32 m_inliningDepth; // 0x10
	private const Int32 MAX_UNCHECKED_INLINING_DEPTH; // 0x0


	// RVA: 0x6133fdc VA: 0x759874bfdc
	internal Boolean TryBeginInliningScope() { }
	// RVA: 0x613401c VA: 0x759874c01c
	internal Void EndInliningScope() { }
	// RVA: 0x612dafc VA: 0x7598745afc
	public Void .ctor() { }
}
```