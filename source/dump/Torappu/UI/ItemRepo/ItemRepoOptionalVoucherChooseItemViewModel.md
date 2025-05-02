# ItemRepoOptionalVoucherChooseItemViewModel

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIItemViewModel itemViewModel`

- `Int32 curPickNum`

- `Int32 perPickCount`

- `OptionalVoucherExtraData extraData`

- `Boolean isFocus`


## Methods

- `Boolean CheckIfCanAdd()`

- `Int32 GetTotalPickCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherChooseItemViewModel : IHotfixable
{
	public UIItemViewModel itemViewModel; // 0x10
	public Int32 curPickNum; // 0x18
	public Int32 perPickCount; // 0x1c
	public OptionalVoucherExtraData extraData; // 0x20
	public Boolean isFocus; // 0x28
	private static DelegateBridge __Hotfix0_CheckIfCanAdd; // 0x0
	private static DelegateBridge __Hotfix0_GetTotalPickCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d2d320 VA: 0x7595345320
	public Boolean CheckIfCanAdd() { }
	// RVA: 0x2d2d3a8 VA: 0x75953453a8
	public Int32 GetTotalPickCount() { }
	// RVA: 0x2d2d414 VA: 0x7595345414
	public Void .ctor() { }
}
```