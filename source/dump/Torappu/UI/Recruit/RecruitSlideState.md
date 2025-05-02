# RecruitSlideState

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RecruitStateBean _stateBean`

- `RecruitGachaView _gachaView`

- `RefCountReference m_buildingRef`

- `Boolean m_isInited`

- `Boolean m_havePendingRequest`

- `Int32 m_startBuildSlotCache`

- `Int32 m_fastFinishSlotCache`

- `Int32 m_stopBuildSlotCache`

- `Int32 m_getResultSlostCache`


## Methods

- `Void SwitchPage(Boolean)`

- `Void EventOnBuildingTimeUp(Int32)`

- `Void EventOnStartBuildClick(Int32)`

- `Void EventOnLockedSlotClick(Int32)`

- `Void EventOnFastFinishClick(Int32)`

- `Void EventOnBuySlot(Int32)`

- `Void EventOnInterruptBuildClick(Int32)`

- `Void EventOnFinishBuildClick(Int32)`

- `Void OnConfirmFastFinish(Int32)`

- `Void OnBuyFastFinish(Int32)`

- `Void OnBuyFastDiamondShardFinish(Int32)`

- `Void OpenDetail(String, Boolean)`

- `Void _OnConfirmStopBuild()`

- `Void _SyncBuildStatusProceedCallback(SyncNormalGachaResponse)`

- `Void _SyncBuildStatusFinalCallback()`

- `Void _SendBuySlotService(String)`

- `Void _OnGiveDataToDetialState(IStateBean)`

- `Void _OnGiveDataToBuildConfigState(IStateBean)`

- `Void _OnReceiveDataFromBuildConfigState(IStateBean)`

- `Void _InitIfNot(Param)`

- `Void _SendSyncBuildDataService()`

- `Void _EventOnGacha(String, SingleGachaPolicy)`

- `Void _EventOnLimitGacha(String)`

- `Void _SendGachaReq(String, GachaType, String)`

- `Void EventOnGachaBtnClick(String)`

- `Void _EventOnTenGacha(String, TenGachaPolicy)`

- `Void EventOnTenGachaBtnClick(String)`

- `Void _SendTenGachaReq(String, GachaType, List`1)`

- `Void EventOnRecruitFreeClick(String)`

- `Void _SendRecruitFreeCharReq(String)`

- `Void _OnSingleAdvGachaSuc(AdvancedGachaResponse)`

- `Void _OnTenAdvGachaSuc(TenAdvancedGachaResponse)`

- `Void _OnGachaPoolBanned()`

- `Void _OnGetCharacter(GachaResult, Boolean, Boolean)`

- `Void _OnGetCharacters(GachaResult[], Boolean, Boolean)`

- `Void _PushGachaResultToGameAnalytics(GachaResult, Boolean)`

- `Void <EventOnFinishBuildClick>b__16_0(FinishNormalGachaResponse)`

- `Void <OnConfirmFastFinish>b__17_0(BoostNormalGachaResponse)`

- `Void <OnBuyFastFinish>b__18_0(BoostNormalGachaResponse)`

- `Void <_OnConfirmStopBuild>b__27_0(CancelNormalGachaResponse)`

- `Void <_SendBuySlotService>b__30_0(BuyRecruitSlotResponse)`

- `Void <RegisterToDataListener>b__34_0(IStateBean)`

- `Void <_SendGachaReq>b__41_0(AdvancedGachaResponse)`

- `Void <_SendTenGachaReq>b__45_0(TenAdvancedGachaResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSlideState : State
{
	private const String SCROLL_INDEX; // 0x0
	private RecruitStateBean _stateBean; // 0x50
	private RecruitGachaView _gachaView; // 0x58
	private RefCountReference m_buildingRef; // 0x60
	private Boolean m_isInited; // 0x68
	private ResultHandler`1 m_syncBuildStateHandler; // 0x70
	private Boolean m_havePendingRequest; // 0x78
	private Int32 m_startBuildSlotCache; // 0x7c
	private Int32 m_fastFinishSlotCache; // 0x80
	private Int32 m_stopBuildSlotCache; // 0x84
	private Int32 m_getResultSlostCache; // 0x88
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_SwitchPage; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBuildingTimeUp; // 0x28
	private static DelegateBridge __Hotfix0_EventOnStartBuildClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnLockedSlotClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnFastFinishClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBuySlot; // 0x48
	private static DelegateBridge __Hotfix0_EventOnInterruptBuildClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnFinishBuildClick; // 0x58
	private static DelegateBridge __Hotfix0_OnConfirmFastFinish; // 0x60
	private static DelegateBridge __Hotfix0_OnBuyFastFinish; // 0x68
	private static DelegateBridge __Hotfix0_OnBuyFastDiamondShardFinish; // 0x70
	private static DelegateBridge __Hotfix0_OpenDetail; // 0x78
	private static DelegateBridge __Hotfix0__OnConfirmStopBuild; // 0x80
	private static DelegateBridge __Hotfix0__SyncBuildStatusProceedCallback; // 0x88
	private static DelegateBridge __Hotfix0__SyncBuildStatusFinalCallback; // 0x90
	private static DelegateBridge __Hotfix0__SendBuySlotService; // 0x98
	private static DelegateBridge __Hotfix0__OnGiveDataToDetialState; // 0xa0
	private static DelegateBridge __Hotfix0__OnGiveDataToBuildConfigState; // 0xa8
	private static DelegateBridge __Hotfix0__OnReceiveDataFromBuildConfigState; // 0xb0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0xb8
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0xc0
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xd0
	private static DelegateBridge __Hotfix0__SendSyncBuildDataService; // 0xd8
	private static DelegateBridge __Hotfix0__EventOnGacha; // 0xe0
	private static DelegateBridge __Hotfix0__EventOnLimitGacha; // 0xe8
	private static DelegateBridge __Hotfix0__SendGachaReq; // 0xf0
	private static DelegateBridge __Hotfix0_EventOnGachaBtnClick; // 0xf8
	private static DelegateBridge __Hotfix0__EventOnTenGacha; // 0x100
	private static DelegateBridge __Hotfix0_EventOnTenGachaBtnClick; // 0x108
	private static DelegateBridge __Hotfix0__SendTenGachaReq; // 0x110
	private static DelegateBridge __Hotfix0_EventOnRecruitFreeClick; // 0x118
	private static DelegateBridge __Hotfix0__SendRecruitFreeCharReq; // 0x120
	private static DelegateBridge __Hotfix0__OnSingleAdvGachaSuc; // 0x128
	private static DelegateBridge __Hotfix0__OnTenAdvGachaSuc; // 0x130
	private static DelegateBridge __Hotfix0__OnGachaPoolBanned; // 0x138
	private static DelegateBridge __Hotfix0__OnGetCharacter; // 0x140
	private static DelegateBridge __Hotfix0__OnGetCharacters; // 0x148
	private static DelegateBridge __Hotfix0__PushGachaResultToGameAnalytics; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158


	// RVA: 0x26f6898 VA: 0x7594d0e898
	protected override Void OnEnter() { }
	// RVA: 0x26f6a28 VA: 0x7594d0ea28
	protected override Void OnResume() { }
	// RVA: 0x26f6aec VA: 0x7594d0eaec
	protected override Void OnExit() { }
	// RVA: 0x26f6b6c VA: 0x7594d0eb6c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26f37a8 VA: 0x7594d0b7a8
	public Void SwitchPage(Boolean toNormalGacha) { }
	// RVA: 0x26f6bd4 VA: 0x7594d0ebd4
	public Void EventOnBuildingTimeUp(Int32 slotIndex) { }
	// RVA: 0x26f6f9c VA: 0x7594d0ef9c
	public Void EventOnStartBuildClick(Int32 slotIndex) { }
	// RVA: 0x26f70cc VA: 0x7594d0f0cc
	public Void EventOnLockedSlotClick(Int32 slotIndex) { }
	// RVA: 0x26f7198 VA: 0x7594d0f198
	public Void EventOnFastFinishClick(Int32 slotIndex) { }
	// RVA: 0x26f731c VA: 0x7594d0f31c
	public Void EventOnBuySlot(Int32 slotIndex) { }
	// RVA: 0x26f74b4 VA: 0x7594d0f4b4
	public Void EventOnInterruptBuildClick(Int32 slotIndex) { }
	// RVA: 0x26f7764 VA: 0x7594d0f764
	public Void EventOnFinishBuildClick(Int32 slotIndex) { }
	// RVA: 0x26f7980 VA: 0x7594d0f980
	public Void OnConfirmFastFinish(Int32 slotId) { }
	// RVA: 0x26f7c74 VA: 0x7594d0fc74
	public Void OnBuyFastFinish(Int32 slotId) { }
	// RVA: 0x26f7f48 VA: 0x7594d0ff48
	public Void OnBuyFastDiamondShardFinish(Int32 slotId) { }
	// RVA: 0x26f8230 VA: 0x7594d10230
	public Void OpenDetail(String gachaPoolId, Boolean needScroll) { }
	// RVA: 0x26f8450 VA: 0x7594d10450
	private Void _OnConfirmStopBuild() { }
	// RVA: 0x26f8628 VA: 0x7594d10628
	private Void _SyncBuildStatusProceedCallback(SyncNormalGachaResponse response) { }
	// RVA: 0x26f8988 VA: 0x7594d10988
	private Void _SyncBuildStatusFinalCallback() { }
	// RVA: 0x26f8a1c VA: 0x7594d10a1c
	private Void _SendBuySlotService(String index) { }
	// RVA: 0x26f8c18 VA: 0x7594d10c18
	private Void _OnGiveDataToDetialState(IStateBean rawBean) { }
	// RVA: 0x26f8da0 VA: 0x7594d10da0
	private Void _OnGiveDataToBuildConfigState(IStateBean rawBean) { }
	// RVA: 0x26f8e74 VA: 0x7594d10e74
	private Void _OnReceiveDataFromBuildConfigState(IStateBean rawBean) { }
	// RVA: 0x26f8f54 VA: 0x7594d10f54
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x26f91b8 VA: 0x7594d111b8
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x26f9230 VA: 0x7594d11230
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x26f6960 VA: 0x7594d0e960
	private Void _InitIfNot(Param pageParam) { }
	// RVA: 0x26f6c50 VA: 0x7594d0ec50
	private Void _SendSyncBuildDataService() { }
	// RVA: 0x26f942c VA: 0x7594d1142c
	private Void _EventOnGacha(String inputPoolId, SingleGachaPolicy policy) { }
	// RVA: 0x26f9798 VA: 0x7594d11798
	private Void _EventOnLimitGacha(String inputPoolId) { }
	// RVA: 0x26f9580 VA: 0x7594d11580
	private Void _SendGachaReq(String inputPoolId, GachaType gType, String itemId) { }
	// RVA: 0x26f9878 VA: 0x7594d11878
	public Void EventOnGachaBtnClick(String inputPoolId) { }
	// RVA: 0x26f9d2c VA: 0x7594d11d2c
	private Void _EventOnTenGacha(String inputPoolId, TenGachaPolicy policy) { }
	// RVA: 0x26fa1d4 VA: 0x7594d121d4
	public Void EventOnTenGachaBtnClick(String inputPoolId) { }
	// RVA: 0x26f9f64 VA: 0x7594d11f64
	private Void _SendTenGachaReq(String inputPoolId, GachaType gType, List`1 itemList) { }
	// RVA: 0x26fa4ec VA: 0x7594d124ec
	public Void EventOnRecruitFreeClick(String inputPoolId) { }
	// RVA: 0x26fa588 VA: 0x7594d12588
	private Void _SendRecruitFreeCharReq(String inputPoolId) { }
	// RVA: 0x26fa820 VA: 0x7594d12820
	private Void _OnSingleAdvGachaSuc(AdvancedGachaResponse response) { }
	// RVA: 0x26faa54 VA: 0x7594d12a54
	private Void _OnTenAdvGachaSuc(TenAdvancedGachaResponse response) { }
	// RVA: 0x26faca0 VA: 0x7594d12ca0
	private Void _OnGachaPoolBanned() { }
	// RVA: 0x26fa948 VA: 0x7594d12948
	private Void _OnGetCharacter(GachaResult gachaResult, Boolean isAdvanced, Boolean isSkippable) { }
	// RVA: 0x26fab24 VA: 0x7594d12b24
	private Void _OnGetCharacters(GachaResult[] gachaResultList, Boolean isAdvanced, Boolean isSkippable) { }
	// RVA: 0x26fad38 VA: 0x7594d12d38
	private Void _PushGachaResultToGameAnalytics(GachaResult gachaResult, Boolean isAdvanced) { }
	// RVA: 0x26fae0c VA: 0x7594d12e0c
	public Void .ctor() { }
	// RVA: 0x26fae7c VA: 0x7594d12e7c
	private Void <EventOnFinishBuildClick>b__16_0(FinishNormalGachaResponse response) { }
	// RVA: 0x26faf14 VA: 0x7594d12f14
	private Void <OnConfirmFastFinish>b__17_0(BoostNormalGachaResponse response) { }
	// RVA: 0x26fafa4 VA: 0x7594d12fa4
	private Void <OnBuyFastFinish>b__18_0(BoostNormalGachaResponse response) { }
	// RVA: 0x26fb100 VA: 0x7594d13100
	private Void <_OnConfirmStopBuild>b__27_0(CancelNormalGachaResponse response) { }
	// RVA: 0x26fb194 VA: 0x7594d13194
	private Void <_SendBuySlotService>b__30_0(BuyRecruitSlotResponse response) { }
	// RVA: 0x26fb208 VA: 0x7594d13208
	private Void <RegisterToDataListener>b__34_0(IStateBean stateBean) { }
	// RVA: 0x26fb2c8 VA: 0x7594d132c8
	private Void <_SendGachaReq>b__41_0(AdvancedGachaResponse response) { }
	// RVA: 0x26fb2ec VA: 0x7594d132ec
	private Void <_SendTenGachaReq>b__45_0(TenAdvancedGachaResponse response) { }
	// RVA: 0x26fb310 VA: 0x7594d13310
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x26fb318 VA: 0x7594d13318
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x26fb320 VA: 0x7594d13320
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x26fb328 VA: 0x7594d13328
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x26fb330 VA: 0x7594d13330
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x26fb338 VA: 0x7594d13338
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```