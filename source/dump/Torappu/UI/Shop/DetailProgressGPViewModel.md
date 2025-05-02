# DetailProgressGPViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int32 currentCheckInDay`

- `Int32 totalCheckInDay`


## Methods

- `Void LoadData(ShopGPCondTrigItemViewModel)`

- `Void _LoadReturnProgressReward()`

- `Void _LoadNewProgressReward()`

- `Void _LoadCommonData(ShopGPCondTrigItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class DetailProgressGPViewModel : DetailCommonViewModel, IHotfixable
{
	public Int32 currentCheckInDay; // 0x68
	public Int32 totalCheckInDay; // 0x6c
	public List`1 rewardList; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadReturnProgressReward; // 0x8
	private static DelegateBridge __Hotfix0__LoadNewProgressReward; // 0x10
	private static DelegateBridge __Hotfix0__LoadCommonData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x242b978 VA: 0x7594a43978
	public Void LoadData(ShopGPCondTrigItemViewModel itemModel) { }
	// RVA: 0x242c0a0 VA: 0x7594a440a0
	private Void _LoadReturnProgressReward() { }
	// RVA: 0x242bb80 VA: 0x7594a43b80
	private Void _LoadNewProgressReward() { }
	// RVA: 0x242ba48 VA: 0x7594a43a48
	private Void _LoadCommonData(ShopGPCondTrigItemViewModel itemModel) { }
	// RVA: 0x242c730 VA: 0x7594a44730
	public Void .ctor() { }
}
```