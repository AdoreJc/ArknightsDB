# TaskInfo

**Namespace:** ` `


## Fields

- `Int32 totalProgress`

- `Int32 currProgress`

- `String taskDesc`


## Methods

- `Boolean IsCompleted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TaskInfo : IHotfixable
{
	public Int32 totalProgress; // 0x10
	public Int32 currProgress; // 0x14
	public String taskDesc; // 0x18
	private static DelegateBridge __Hotfix0_IsCompleted; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2a7f2fc VA: 0x75950972fc
	public Boolean IsCompleted() { }
	// RVA: 0x2a7f28c VA: 0x759509728c
	public Void .ctor() { }
}
```