# ReentrantFloatRef

**Namespace:** ` `


## Fields

- `Boolean m_isReleased`

- `Boolean m_isActive`

- `Action m_hideCall`


## Properties

- `Boolean isReleased`


## Methods

- `IEnumerator Show()`

- `Void Release()`

- `Boolean get_isReleased()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReentrantFloatRef : IHotfixable
{
	private Boolean m_isReleased; // 0x10
	private Boolean m_isActive; // 0x11
	private Func`1 m_showCall; // 0x18
	private Action m_hideCall; // 0x20
	private static DelegateBridge __Hotfix0_UIPopupWindow_Create; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_Release; // 0x10
	private static DelegateBridge __Hotfix0_get_isReleased; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isReleased { get; }

	// RVA: 0x224d584 VA: 0x7594865584
	public static ReentrantFloatRef UIPopupWindow_Create(Func`1 showCall, Action hideCall) { }
	// RVA: 0x2252084 VA: 0x759486a084
	public IEnumerator Show() { }
	// RVA: 0x2252158 VA: 0x759486a158
	public Void Release() { }
	// RVA: 0x2252214 VA: 0x759486a214
	public Boolean get_isReleased() { }
	// RVA: 0x2252014 VA: 0x759486a014
	private Void .ctor() { }
}
```