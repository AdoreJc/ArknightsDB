# CampaignMissionStateBean

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Input input`

- `String rotateStageId`

- `Int32 currentFee`

- `Int32 totalFee`

- `String countDownText`

- `Boolean isShowCommonMissionRedirectButton`


## Methods

- `Void LoadData()`

- `Void _LoadPermanet()`

- `Void _LoadCommon()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignMissionStateBean : IStateBean, IHotfixable
{
	public Input input; // 0x10
	public String rotateStageId; // 0x20
	public Int32 currentFee; // 0x28
	public Int32 totalFee; // 0x2c
	public String countDownText; // 0x30
	public Boolean isShowCommonMissionRedirectButton; // 0x38
	public List`1 permanentMissions; // 0x40
	public List`1 commonMissions; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadPermanet; // 0x8
	private static DelegateBridge __Hotfix0__LoadCommon; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2dce890 VA: 0x75953e6890
	public Void LoadData() { }
	// RVA: 0x2dd0008 VA: 0x75953e8008
	private Void _LoadPermanet() { }
	// RVA: 0x2dd02fc VA: 0x75953e82fc
	private Void _LoadCommon() { }
	// RVA: 0x2dcf298 VA: 0x75953e7298
	public Void .ctor() { }
}
```