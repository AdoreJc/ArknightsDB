# StateBeanHandler

**Namespace:** ` `


## Fields

- `DIYListViewStateBean m_closure`


## Methods

- `Void Setup(UIHandler)`

- `Void Reload()`

- `Void UpdateViewCount()`

- `Void UpdateViewExpand(UIExpandListState)`

- `Void UpdateAtmosphereText()`

- `Boolean CheckHasFuncFurnExceedLimit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StateBeanHandler : IHotfixable
{
	private DIYListViewStateBean m_closure; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0_Reload; // 0x10
	private static DelegateBridge __Hotfix0_UpdateViewCount; // 0x18
	private static DelegateBridge __Hotfix0_UpdateViewExpand; // 0x20
	private static DelegateBridge __Hotfix0_UpdateAtmosphereText; // 0x28
	private static DelegateBridge __Hotfix0_CheckHasFuncFurnExceedLimit; // 0x30


	// RVA: 0x3837390 VA: 0x7595e4f390
	public Void .ctor(DIYListViewStateBean closure) { }
	// RVA: 0x3837424 VA: 0x7595e4f424
	public Void Setup(UIHandler pageHandler) { }
	// RVA: 0x38374ac VA: 0x7595e4f4ac
	public Void Reload() { }
	// RVA: 0x383751c VA: 0x7595e4f51c
	public Void UpdateViewCount() { }
	// RVA: 0x383758c VA: 0x7595e4f58c
	public Void UpdateViewExpand(UIExpandListState expandState) { }
	// RVA: 0x3837614 VA: 0x7595e4f614
	public Void UpdateAtmosphereText() { }
	// RVA: 0x3837684 VA: 0x7595e4f684
	public Boolean CheckHasFuncFurnExceedLimit() { }
}
```