# RequestWaitForConstantSec

**Namespace:** `Torappu.UI`


## Fields

- `Int32 m_waitSec`


## Methods

- `Boolean IsWaitEnough(RequestWaitParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class RequestWaitForConstantSec : IRequestWaitStrategy, IHotfixable
{
	private Int32 m_waitSec; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_IsWaitEnough; // 0x8


	// RVA: 0x2225840 VA: 0x759483d840
	public Void .ctor(Int32 waitSec) { }
	// RVA: 0x22258c8 VA: 0x759483d8c8
	public Boolean IsWaitEnough(RequestWaitParam waitParam) { }
}
```