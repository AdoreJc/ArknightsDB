# Act24sideMeldingViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String <actId>k__BackingField`

- `Int32 <lightingSlotCount>k__BackingField`

- `String <curGachaBoxId>k__BackingField`

- `Boolean <isChoiceDetailOpening>k__BackingField`

- `Int32 <curMeldingPriceCount>k__BackingField`

- `Int32 <curMeldingCount>k__BackingField`

- `Int32 <playerHasMeldingPriceCount>k__BackingField`

- `Act24sideMeldingGoodGroupViewModel <curGachaBoxModel>k__BackingField`

- `Int32 m_curGachaBoxIdIndex`


## Properties

- `String actId`

- `Int32 lightingSlotCount`

- `String curGachaBoxId`

- `Boolean isChoiceDetailOpening`

- `Int32 curMeldingPriceCount`

- `Int32 curMeldingCount`

- `Int32 playerHasMeldingPriceCount`

- `Act24sideMeldingGoodGroupViewModel curGachaBoxModel`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `Int32 get_lightingSlotCount()`

- `Void set_lightingSlotCount(Int32)`

- `String get_curGachaBoxId()`

- `Void set_curGachaBoxId(String)`

- `Boolean get_isChoiceDetailOpening()`

- `Void set_isChoiceDetailOpening(Boolean)`

- `Int32 get_curMeldingPriceCount()`

- `Void set_curMeldingPriceCount(Int32)`

- `Int32 get_curMeldingCount()`

- `Void set_curMeldingCount(Int32)`

- `Int32 get_playerHasMeldingPriceCount()`

- `Void set_playerHasMeldingPriceCount(Int32)`

- `Act24sideMeldingGoodGroupViewModel get_curGachaBoxModel()`

- `Void set_curGachaBoxModel(Act24sideMeldingGoodGroupViewModel)`

- `Void LoadData(String)`

- `Void RefreshData(Boolean)`

- `Boolean CheckIfMeldingItemInput()`

- `Boolean CheckIfMeldingItemEmpty()`

- `Boolean CheckIfInputtedMeldingItemsEnoughOneDraw()`

- `Boolean TryFastInput()`

- `Boolean CheckIfAllMeldingInputOverflowMax()`

- `Boolean CheckIfCurGachaBoxAllTakeOut()`

- `Int32 GetCanAddCountWhichNotOverMaxDrawCount(String, Int32)`

- `Int32 GetCanAddCountWhichNotOverFlowRemainRewards(String, Int32)`

- `Void RefreshMeldingUseCount(Dictionary`2)`

- `Boolean CheckIfFastInputMeldingsChanged(Dictionary`2)`

- `Void TryUpdateFastInputMeldingCountDic(Dictionary`2)`

- `Boolean AddMeldingUseCount(String, Int32)`

- `Int32 GetCanAddMeldingUseCount(String, Int32)`

- `Boolean MinusMeldingUseCount(String, Int32)`

- `Int32 GetCanMinusMeldingUseCount(String, Int32)`

- `Boolean SwitchGachaBox()`

- `Void ClearAllInput()`

- `Act24sideMeldingGoodGroupViewModel GetGachaBoxById(String)`

- `Int32 GetCurGachaBoxRemainGoodMaxPriceCount()`

- `Int32 GetAllMeldingsHasPriceCount()`

- `Boolean IsCurFirstGachaBox()`

- `Void UpdateChoiceDetailOpeningState(Boolean)`

- `Int32 GetChangeTotalPrice(List`1)`

- `Void _ResetData()`

- `Void _RefreshCurGachaBoxData()`

- `Int32 _GetCurBoxIdIndex()`

- `Int32 _GetNextBoxIdIndex()`

- `String _GetNextBoxId()`

- `Void _TrySetCurGachaBoxDefaultId()`

- `Void _RefreshGoodsData(PlayerAct24SideActivity)`

- `Boolean _CheckIfCurGachaBoxValid()`

- `Int32 _GetCurGachaBoxRemainGoodCount()`

- `Void _RefreshMeldingInfosByPlayerData(PlayerAct24SideActivity)`

- `Void _ResetMeldingUseCount()`

- `Void _RefreshMeldingHasCountData(PlayerAct24SideActivity)`

- `Act24sideMeldingChoiceItemViewModel _TryGetMeldingChoiceItem(String)`

- `Int32 _GetMeldingCountByPriceCount(Int32, Int32)`

- `Void _RefreshInputMeldingChanges(Int32, Int32, Boolean, List`1)`

- `Void _RefreshInputMeldingProgressChangeList(Int32, Int32, Int32, Int32, List`1)`

- `Void _GetInputMeldingProgressListByAdd(Int32, Int32, Int32, Int32, Int32, List`1)`

- `Void _GetInputMeldingProgressListByMinus(Int32, Int32, Int32, Int32, Int32, List`1)`

- `Int32 _GetToPriceCount(Int32, Int32, Boolean)`

- `Void _ResetMeldingPriceCountAsPlayerHas()`

- `Void _RefreshMeldingCountByCurPriceCount()`

- `Void _TryAddMeldingUseCountToDic(Dictionary`2, String, Int32)`

- `Int32 _GetCurGachaBoxMaxCanDrawPriceCount(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private Int32 <lightingSlotCount>k__BackingField; // 0x18
	private String <curGachaBoxId>k__BackingField; // 0x20
	private Boolean <isChoiceDetailOpening>k__BackingField; // 0x28
	private Int32 <curMeldingPriceCount>k__BackingField; // 0x2c
	private Int32 <curMeldingCount>k__BackingField; // 0x30
	private Int32 <playerHasMeldingPriceCount>k__BackingField; // 0x34
	private Act24sideMeldingGoodGroupViewModel <curGachaBoxModel>k__BackingField; // 0x38
	public ListDict`2 gachaGoodBoxViewModelList; // 0x40
	public List`1 choiceItemViewList; // 0x48
	public List`1 inputMeldingProgressChangeInfoList; // 0x50
	private List`1 m_meldingOwnListSortedByPriceDown; // 0x58
	private Dictionary`2 fastInputMeldingCountDic; // 0x60
	private Int32 m_curGachaBoxIdIndex; // 0x68
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_lightingSlotCount; // 0x10
	private static DelegateBridge __Hotfix0_set_lightingSlotCount; // 0x18
	private static DelegateBridge __Hotfix0_get_curGachaBoxId; // 0x20
	private static DelegateBridge __Hotfix0_set_curGachaBoxId; // 0x28
	private static DelegateBridge __Hotfix0_get_isChoiceDetailOpening; // 0x30
	private static DelegateBridge __Hotfix0_set_isChoiceDetailOpening; // 0x38
	private static DelegateBridge __Hotfix0_get_curMeldingPriceCount; // 0x40
	private static DelegateBridge __Hotfix0_set_curMeldingPriceCount; // 0x48
	private static DelegateBridge __Hotfix0_get_curMeldingCount; // 0x50
	private static DelegateBridge __Hotfix0_set_curMeldingCount; // 0x58
	private static DelegateBridge __Hotfix0_get_playerHasMeldingPriceCount; // 0x60
	private static DelegateBridge __Hotfix0_set_playerHasMeldingPriceCount; // 0x68
	private static DelegateBridge __Hotfix0_get_curGachaBoxModel; // 0x70
	private static DelegateBridge __Hotfix0_set_curGachaBoxModel; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0_RefreshData; // 0x88
	private static DelegateBridge __Hotfix0_GetCurMeldingUseCountDic; // 0x90
	private static DelegateBridge __Hotfix0_CheckIfMeldingItemInput; // 0x98
	private static DelegateBridge __Hotfix0_CheckIfMeldingItemEmpty; // 0xa0
	private static DelegateBridge __Hotfix0_CheckIfInputtedMeldingItemsEnoughOneDraw; // 0xa8
	private static DelegateBridge __Hotfix0_TryFastInput; // 0xb0
	private static DelegateBridge __Hotfix0_CheckIfAllMeldingInputOverflowMax; // 0xb8
	private static DelegateBridge __Hotfix0_CheckIfCurGachaBoxAllTakeOut; // 0xc0
	private static DelegateBridge __Hotfix0_GetCanAddCountWhichNotOverMaxDrawCount; // 0xc8
	private static DelegateBridge __Hotfix0_GetCanAddCountWhichNotOverFlowRemainRewards; // 0xd0
	private static DelegateBridge __Hotfix0_RefreshMeldingUseCount; // 0xd8
	private static DelegateBridge __Hotfix0_CheckIfFastInputMeldingsChanged; // 0xe0
	private static DelegateBridge __Hotfix0_InputAllMelding; // 0xe8
	private static DelegateBridge __Hotfix0_InputSuitableMelding; // 0xf0
	private static DelegateBridge __Hotfix0_TryUpdateFastInputMeldingCountDic; // 0xf8
	private static DelegateBridge __Hotfix0__CalcMinInputMelding; // 0x100
	private static DelegateBridge __Hotfix0_AddMeldingUseCount; // 0x108
	private static DelegateBridge __Hotfix0_GetCanAddMeldingUseCount; // 0x110
	private static DelegateBridge __Hotfix0_MinusMeldingUseCount; // 0x118
	private static DelegateBridge __Hotfix0_GetCanMinusMeldingUseCount; // 0x120
	private static DelegateBridge __Hotfix0_SwitchGachaBox; // 0x128
	private static DelegateBridge __Hotfix0_ClearAllInput; // 0x130
	private static DelegateBridge __Hotfix0_GetGachaBoxById; // 0x138
	private static DelegateBridge __Hotfix0_GetCurGachaBoxRemainGoodMaxPriceCount; // 0x140
	private static DelegateBridge __Hotfix0_GetAllMeldingsHasPriceCount; // 0x148
	private static DelegateBridge __Hotfix0_IsCurFirstGachaBox; // 0x150
	private static DelegateBridge __Hotfix0_UpdateChoiceDetailOpeningState; // 0x158
	private static DelegateBridge __Hotfix0_GetChangeTotalPrice; // 0x160
	private static DelegateBridge __Hotfix0__ResetData; // 0x168
	private static DelegateBridge __Hotfix0__RefreshCurGachaBoxData; // 0x170
	private static DelegateBridge __Hotfix0__GetCurBoxIdIndex; // 0x178
	private static DelegateBridge __Hotfix0__GetNextBoxIdIndex; // 0x180
	private static DelegateBridge __Hotfix0__GetNextBoxId; // 0x188
	private static DelegateBridge __Hotfix0__TrySetCurGachaBoxDefaultId; // 0x190
	private static DelegateBridge __Hotfix0__RefreshGoodsData; // 0x198
	private static DelegateBridge __Hotfix0__CheckIfCurGachaBoxValid; // 0x1a0
	private static DelegateBridge __Hotfix0__GetCurGachaBoxRemainGoodCount; // 0x1a8
	private static DelegateBridge __Hotfix0__RefreshMeldingInfosByPlayerData; // 0x1b0
	private static DelegateBridge __Hotfix0__ResetMeldingUseCount; // 0x1b8
	private static DelegateBridge __Hotfix0__RefreshMeldingHasCountData; // 0x1c0
	private static DelegateBridge __Hotfix0__TryGetMeldingChoiceItem; // 0x1c8
	private static DelegateBridge __Hotfix0__GetMeldingCountByPriceCount; // 0x1d0
	private static DelegateBridge __Hotfix0__RefreshInputMeldingChanges; // 0x1d8
	private static DelegateBridge __Hotfix0_GetMeldingProgressChangeList; // 0x1e0
	private static DelegateBridge __Hotfix0__RefreshInputMeldingProgressChangeList; // 0x1e8
	private static DelegateBridge __Hotfix0__GetInputMeldingProgressListByAdd; // 0x1f0
	private static DelegateBridge __Hotfix0__GetInputMeldingProgressListByMinus; // 0x1f8
	private static DelegateBridge __Hotfix0__GetToPriceCount; // 0x200
	private static DelegateBridge __Hotfix0__ResetMeldingPriceCountAsPlayerHas; // 0x208
	private static DelegateBridge __Hotfix0__RefreshMeldingCountByCurPriceCount; // 0x210
	private static DelegateBridge __Hotfix0__TryAddMeldingUseCountToDic; // 0x218
	private static DelegateBridge __Hotfix0__GetCurGachaBoxMaxCanDrawPriceCount; // 0x220
	private static DelegateBridge _c__Hotfix0_ctor; // 0x228

	public String actId { get; set; }
	public Int32 lightingSlotCount { get; set; }
	public String curGachaBoxId { get; set; }
	public Boolean isChoiceDetailOpening { get; set; }
	public Int32 curMeldingPriceCount { get; set; }
	public Int32 curMeldingCount { get; set; }
	public Int32 playerHasMeldingPriceCount { get; set; }
	public Act24sideMeldingGoodGroupViewModel curGachaBoxModel { get; set; }

	// RVA: 0x32ab934 VA: 0x75958c3934
	public String get_actId() { }
	// RVA: 0x32ab99c VA: 0x75958c399c
	private Void set_actId(String value) { }
	// RVA: 0x32aba20 VA: 0x75958c3a20
	public Int32 get_lightingSlotCount() { }
	// RVA: 0x32aba88 VA: 0x75958c3a88
	private Void set_lightingSlotCount(Int32 value) { }
	// RVA: 0x32a4bc0 VA: 0x75958bcbc0
	public String get_curGachaBoxId() { }
	// RVA: 0x32abb04 VA: 0x75958c3b04
	private Void set_curGachaBoxId(String value) { }
	// RVA: 0x32a5cec VA: 0x75958bdcec
	public Boolean get_isChoiceDetailOpening() { }
	// RVA: 0x32abb88 VA: 0x75958c3b88
	private Void set_isChoiceDetailOpening(Boolean value) { }
	// RVA: 0x32a7bc8 VA: 0x75958bfbc8
	public Int32 get_curMeldingPriceCount() { }
	// RVA: 0x32abc08 VA: 0x75958c3c08
	private Void set_curMeldingPriceCount(Int32 value) { }
	// RVA: 0x32ab2f0 VA: 0x75958c32f0
	public Int32 get_curMeldingCount() { }
	// RVA: 0x32abc84 VA: 0x75958c3c84
	private Void set_curMeldingCount(Int32 value) { }
	// RVA: 0x32abd00 VA: 0x75958c3d00
	public Int32 get_playerHasMeldingPriceCount() { }
	// RVA: 0x32abd68 VA: 0x75958c3d68
	private Void set_playerHasMeldingPriceCount(Int32 value) { }
	// RVA: 0x32ab288 VA: 0x75958c3288
	public Act24sideMeldingGoodGroupViewModel get_curGachaBoxModel() { }
	// RVA: 0x32abde4 VA: 0x75958c3de4
	private Void set_curGachaBoxModel(Act24sideMeldingGoodGroupViewModel value) { }
	// RVA: 0x32a3c04 VA: 0x75958bbc04
	public Void LoadData(String activityId) { }
	// RVA: 0x32a42b8 VA: 0x75958bc2b8
	public Void RefreshData(Boolean needResetDefaultBoxId) { }
	// RVA: 0x32a4c28 VA: 0x75958bcc28
	public Dictionary`2 GetCurMeldingUseCountDic() { }
	// RVA: 0x32a6a9c VA: 0x75958bea9c
	public Boolean CheckIfMeldingItemInput() { }
	// RVA: 0x32ac760 VA: 0x75958c4760
	public Boolean CheckIfMeldingItemEmpty() { }
	// RVA: 0x32a6c20 VA: 0x75958bec20
	public Boolean CheckIfInputtedMeldingItemsEnoughOneDraw() { }
	// RVA: 0x32a6958 VA: 0x75958be958
	public Boolean TryFastInput() { }
	// RVA: 0x32ac90c VA: 0x75958c490c
	public Boolean CheckIfAllMeldingInputOverflowMax() { }
	// RVA: 0x32a6138 VA: 0x75958be138
	public Boolean CheckIfCurGachaBoxAllTakeOut() { }
	// RVA: 0x32a61cc VA: 0x75958be1cc
	public Int32 GetCanAddCountWhichNotOverMaxDrawCount(String meldingId, Int32 tryAddCount) { }
	// RVA: 0x32a62c8 VA: 0x75958be2c8
	public Int32 GetCanAddCountWhichNotOverFlowRemainRewards(String meldingId, Int32 tryAddCount) { }
	// RVA: 0x32ad80c VA: 0x75958c580c
	public Void RefreshMeldingUseCount(Dictionary`2 useDic) { }
	// RVA: 0x32ad0ac VA: 0x75958c50ac
	public Boolean CheckIfFastInputMeldingsChanged(Dictionary`2 newUseCountDic) { }
	// RVA: 0x32acc40 VA: 0x75958c4c40
	public Dictionary`2 InputAllMelding() { }
	// RVA: 0x32aceec VA: 0x75958c4eec
	public Dictionary`2 InputSuitableMelding(Int32 maxCanDrawPriceCount) { }
	// RVA: 0x32ad330 VA: 0x75958c5330
	public Void TryUpdateFastInputMeldingCountDic(Dictionary`2 useCountDic) { }
	// RVA: 0x32add4c VA: 0x75958c5d4c
	private Dictionary`2 _CalcMinInputMelding(Int32 maxCanDrawPriceCount) { }
	// RVA: 0x32a651c VA: 0x75958be51c
	public Boolean AddMeldingUseCount(String meldingId, Int32 count) { }
	// RVA: 0x32a6428 VA: 0x75958be428
	public Int32 GetCanAddMeldingUseCount(String meldingId, Int32 count) { }
	// RVA: 0x32a6848 VA: 0x75958be848
	public Boolean MinusMeldingUseCount(String meldingId, Int32 count) { }
	// RVA: 0x32a6754 VA: 0x75958be754
	public Int32 GetCanMinusMeldingUseCount(String meldingId, Int32 count) { }
	// RVA: 0x32a5dd4 VA: 0x75958bddd4
	public Boolean SwitchGachaBox() { }
	// RVA: 0x32a6bb4 VA: 0x75958bebb4
	public Void ClearAllInput() { }
	// RVA: 0x32a938c VA: 0x75958c138c
	public Act24sideMeldingGoodGroupViewModel GetGachaBoxById(String gachaId) { }
	// RVA: 0x32acb80 VA: 0x75958c4b80
	public Int32 GetCurGachaBoxRemainGoodMaxPriceCount() { }
	// RVA: 0x32aca4c VA: 0x75958c4a4c
	public Int32 GetAllMeldingsHasPriceCount() { }
	// RVA: 0x32a7ac8 VA: 0x75958bfac8
	public Boolean IsCurFirstGachaBox() { }
	// RVA: 0x32a5d54 VA: 0x75958bdd54
	public Void UpdateChoiceDetailOpeningState(Boolean open) { }
	// RVA: 0x32a944c VA: 0x75958c144c
	public Int32 GetChangeTotalPrice(List`1 changeInfoList) { }
	// RVA: 0x32ac0e0 VA: 0x75958c40e0
	private Void _ResetData() { }
	// RVA: 0x32ac52c VA: 0x75958c452c
	private Void _RefreshCurGachaBoxData() { }
	// RVA: 0x32ae1c4 VA: 0x75958c61c4
	private Int32 _GetCurBoxIdIndex() { }
	// RVA: 0x32ae2e8 VA: 0x75958c62e8
	private Int32 _GetNextBoxIdIndex() { }
	// RVA: 0x32ae0d8 VA: 0x75958c60d8
	private String _GetNextBoxId() { }
	// RVA: 0x32ac38c VA: 0x75958c438c
	private Void _TrySetCurGachaBoxDefaultId() { }
	// RVA: 0x32ac18c VA: 0x75958c418c
	private Void _RefreshGoodsData(PlayerAct24SideActivity playerData) { }
	// RVA: 0x32ac854 VA: 0x75958c4854
	private Boolean _CheckIfCurGachaBoxValid() { }
	// RVA: 0x32ad69c VA: 0x75958c569c
	private Int32 _GetCurGachaBoxRemainGoodCount() { }
	// RVA: 0x32ac618 VA: 0x75958c4618
	private Void _RefreshMeldingInfosByPlayerData(PlayerAct24SideActivity playerAct24SideActivity) { }
	// RVA: 0x32ada98 VA: 0x75958c5a98
	private Void _ResetMeldingUseCount() { }
	// RVA: 0x32ae3a4 VA: 0x75958c63a4
	private Void _RefreshMeldingHasCountData(PlayerAct24SideActivity playerData) { }
	// RVA: 0x32ad574 VA: 0x75958c5574
	private Act24sideMeldingChoiceItemViewModel _TryGetMeldingChoiceItem(String meldingId) { }
	// RVA: 0x32ad730 VA: 0x75958c5730
	private Int32 _GetMeldingCountByPriceCount(Int32 allPriceCount, Int32 gachaCost) { }
	// RVA: 0x32adbf0 VA: 0x75958c5bf0
	private Void _RefreshInputMeldingChanges(Int32 meldingPrice, Int32 meldingChangeCount, Boolean add, List`1 result) { }
	// RVA: 0x32a4a88 VA: 0x75958bca88
	public List`1 GetMeldingProgressChangeList() { }
	// RVA: 0x32aea88 VA: 0x75958c6a88
	private Void _RefreshInputMeldingProgressChangeList(Int32 fromPrice, Int32 toPrice, Int32 singleDrawCost, Int32 maxDrawCount, List`1 result) { }
	// RVA: 0x32aeb90 VA: 0x75958c6b90
	private Void _GetInputMeldingProgressListByAdd(Int32 fromPrice, Int32 toPrice, Int32 singleDrawCost, Int32 maxDrawCount, Int32 changePriceCount, List`1 result) { }
	// RVA: 0x32aefbc VA: 0x75958c6fbc
	private Void _GetInputMeldingProgressListByMinus(Int32 fromPrice, Int32 toPrice, Int32 singleDrawCost, Int32 maxDrawCount, Int32 changePriceCount, List`1 result) { }
	// RVA: 0x32ae9d8 VA: 0x75958c69d8
	private Int32 _GetToPriceCount(Int32 meldingPrice, Int32 meldingChangeCount, Boolean add) { }
	// RVA: 0x32ada24 VA: 0x75958c5a24
	private Void _ResetMeldingPriceCountAsPlayerHas() { }
	// RVA: 0x32ae72c VA: 0x75958c672c
	private Void _RefreshMeldingCountByCurPriceCount() { }
	// RVA: 0x32adf30 VA: 0x75958c5f30
	private Void _TryAddMeldingUseCountToDic(Dictionary`2 result, String meldingId, Int32 addCount) { }
	// RVA: 0x32ace3c VA: 0x75958c4e3c
	private Int32 _GetCurGachaBoxMaxCanDrawPriceCount(Boolean canOverFlow) { }
	// RVA: 0x32af3e0 VA: 0x75958c73e0
	public Void .ctor() { }
}
```