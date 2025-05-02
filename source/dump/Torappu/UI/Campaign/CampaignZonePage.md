# CampaignZonePage

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `CampaignFeeViewProperty m_feeProperty`


## Properties

- `String entryZoneId`

- `Boolean isToBreakingDetail`

- `String entryStageId`

- `CampaignFeeViewProperty feeProperty`


## Methods

- `Void _ReturnPage()`

- `String get_entryZoneId()`

- `Boolean get_isToBreakingDetail()`

- `String get_entryStageId()`

- `CampaignFeeViewProperty get_feeProperty()`

- `Void <OnCreate>b__12_0(GameObject)`

- `Void <OnCreate>b__12_1()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZonePage : StateEnginePage
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private CampaignFeeViewProperty m_feeProperty; // 0xf0
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x0
	private static DelegateBridge __Hotfix0_get_entryZoneId; // 0x8
	private static DelegateBridge __Hotfix0_get_isToBreakingDetail; // 0x10
	private static DelegateBridge __Hotfix0_get_entryStageId; // 0x18
	private static DelegateBridge __Hotfix0_get_feeProperty; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String entryZoneId { get; }
	public Boolean isToBreakingDetail { get; }
	public String entryStageId { get; }
	public CampaignFeeViewProperty feeProperty { get; }

	// RVA: 0x2dccc54 VA: 0x75953e4c54
	private Void _ReturnPage() { }
	// RVA: 0x2dccd04 VA: 0x75953e4d04
	public String get_entryZoneId() { }
	// RVA: 0x2dccdc8 VA: 0x75953e4dc8
	public Boolean get_isToBreakingDetail() { }
	// RVA: 0x2dcce5c VA: 0x75953e4e5c
	public String get_entryStageId() { }
	// RVA: 0x2dccf20 VA: 0x75953e4f20
	public CampaignFeeViewProperty get_feeProperty() { }
	// RVA: 0x2dccf88 VA: 0x75953e4f88
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2dcd070 VA: 0x75953e5070
	public Void .ctor() { }
	// RVA: 0x2dcd120 VA: 0x75953e5120
	private Void <OnCreate>b__12_0(GameObject inst) { }
	// RVA: 0x2dcd1d8 VA: 0x75953e51d8
	private Void <OnCreate>b__12_1() { }
	// RVA: 0x2dcd1dc VA: 0x75953e51dc
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```