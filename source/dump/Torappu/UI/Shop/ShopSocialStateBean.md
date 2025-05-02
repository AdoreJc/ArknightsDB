# ShopSocialStateBean

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int64 refreshTime`

- `Boolean ableToGet`

- `Int32 socialFromAssist`

- `Int32 socialFromDorm`

- `Int32 creditUsed`

- `String creditGroup`

- `SocialGetCrisisV2ViewModel socialCrisisV2Model`


## Methods

- `Void InitSocialGetInfo()`

- `Void ApplyData(GetSocialGoodListResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopSocialStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public Int64 refreshTime; // 0x18
	public List`1 shopCreditList; // 0x20
	public Dictionary`2 charUnlockState; // 0x28
	public Boolean ableToGet; // 0x30
	public Int32 socialFromAssist; // 0x34
	public Int32 socialFromDorm; // 0x38
	public Int32 creditUsed; // 0x3c
	public String creditGroup; // 0x40
	public SocialGetCrisisV2ViewModel socialCrisisV2Model; // 0x48
	private static DelegateBridge __Hotfix0_InitSocialGetInfo; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x246e2a4 VA: 0x7594a862a4
	public Void InitSocialGetInfo() { }
	// RVA: 0x246dfac VA: 0x7594a85fac
	public Void ApplyData(GetSocialGoodListResponse response) { }
	// RVA: 0x246e8ac VA: 0x7594a868ac
	public Void .ctor() { }
}
```