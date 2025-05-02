# CampaignFeeViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Int32 currentFee`

- `Int32 totalFee`

- `String countDownText`

- `Boolean hasUnconfirmedBreakFee`

- `Boolean isFull`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignFeeViewModel : IHotfixable
{
	public Int32 currentFee; // 0x10
	public Int32 totalFee; // 0x14
	public String countDownText; // 0x18
	public Boolean hasUnconfirmedBreakFee; // 0x20
	public Boolean isFull; // 0x21
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dcd6b0 VA: 0x75953e56b0
	public Void LoadData() { }
	// RVA: 0x2dcdac0 VA: 0x75953e5ac0
	public Void .ctor() { }
}
```