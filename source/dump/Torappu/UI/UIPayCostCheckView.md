# UIPayCostCheckView

**Namespace:** `Torappu.UI`


## Fields

- `UIPayCostCheckContent m_content`

- `Boolean m_isInited`


## Methods

- `Boolean CheckNeedBuyDiamond(Int32)`

- `Void _OnConfirmed()`

- `Void _OnCanceled()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPayCostCheckView : PageSingleComponent
{
	private UIPayCostCheckContent m_content; // 0x20
	private Boolean m_isInited; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_GetActiveInst; // 0x8
	private static DelegateBridge __Hotfix0_CheckNeedBuyDiamond; // 0x10
	private static DelegateBridge __Hotfix0__OnConfirmed; // 0x18
	private static DelegateBridge __Hotfix0__OnCanceled; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2196a7c VA: 0x75947aea7c
	protected override Void OnCreate() { }
	// RVA: 0x2196cd8 VA: 0x75947aecd8
	public static UIPayCostCheckView GetActiveInst() { }
	// RVA: 0x2196e6c VA: 0x75947aee6c
	public Boolean CheckNeedBuyDiamond(Int32 costNum) { }
	// RVA: 0x2196f40 VA: 0x75947aef40
	private Void _OnConfirmed() { }
	// RVA: 0x2196fdc VA: 0x75947aefdc
	private Void _OnCanceled() { }
	// RVA: 0x2196af0 VA: 0x75947aeaf0
	private Void _InitIfNot() { }
	// RVA: 0x219704c VA: 0x75947af04c
	public Void .ctor() { }
	// RVA: 0x21970bc VA: 0x75947af0bc
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```