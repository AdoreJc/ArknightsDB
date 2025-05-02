# Act20sideCartCompSelectStateBean

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCartCompSelectProperty property`


## Methods

- `Boolean GetChangeFlag()`

- `Void InitInfo(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartCompSelectStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private const CartAccessoryPos DEFAULT_SELECT_POS; // 0x0
	public Act20sideCartCompSelectProperty property; // 0x18
	private static DelegateBridge __Hotfix0_GetChangeFlag; // 0x0
	private static DelegateBridge __Hotfix0_InitInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32fb65c VA: 0x759591365c
	public Boolean GetChangeFlag() { }
	// RVA: 0x32f37d0 VA: 0x759590b7d0
	public Void InitInfo(String actId, Boolean isExhib) { }
	// RVA: 0x32fb6f0 VA: 0x75959136f0
	public Void .ctor() { }
}
```