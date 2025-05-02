# VoucherEvolveHomeState

**Namespace:** `Torappu.UI.VoucherEvolve`


## Fields

- `VoucherEvolveStateBean _stateBean`

- `Transform _panelIllustOld`

- `Transform _panelIllustNew`

- `Single _illustScaleFactor`

- `Color _illustNewColor`

- `Image _rarityImg`

- `Text _realNameText`

- `Text _nickNameText`

- `Text _evolvePhaseText`

- `Image _evolvePhaseImg`

- `Transform _itemCardContainer`

- `Single _itemCardScale`

- `Text _itemCountText`

- `UICharacterIllust m_illustOld`

- `UICharacterIllust m_illustNew`

- `UIItemCard m_itemCard`


## Methods

- `Void OnDestroy()`

- `Void OnDetailClick()`

- `Void OnUpgradeConfirmClick()`

- `Void OnCancelClick()`

- `Void _ClearIllusts()`

- `Void _LoadAndSetIllusts()`

- `Void _RefreshViews()`

- `Void _RefreshItemCardView()`

- `Void _OnItemClick(Int32)`

- `Void _OpenItemRepoPage()`

- `Void <OnUpgradeConfirmClick>b__21_0(EvolveCharUseItemResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherEvolve
public class VoucherEvolveHomeState : State
{
	private const Int32 REQUIRE_ITEM_COUNT; // 0x0
	private VoucherEvolveStateBean _stateBean; // 0x50
	private Transform _panelIllustOld; // 0x58
	private Transform _panelIllustNew; // 0x60
	private Single _illustScaleFactor; // 0x68
	private Color _illustNewColor; // 0x6c
	private Image _rarityImg; // 0x80
	private Text _realNameText; // 0x88
	private Text _nickNameText; // 0x90
	private Text _evolvePhaseText; // 0x98
	private Image _evolvePhaseImg; // 0xa0
	private Transform _itemCardContainer; // 0xa8
	private Single _itemCardScale; // 0xb0
	private Text _itemCountText; // 0xb8
	private UICharacterIllust m_illustOld; // 0xc0
	private UICharacterIllust m_illustNew; // 0xc8
	private UIItemCard m_itemCard; // 0xd0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x18
	private static DelegateBridge __Hotfix0_OnUpgradeConfirmClick; // 0x20
	private static DelegateBridge __Hotfix0_OnCancelClick; // 0x28
	private static DelegateBridge __Hotfix0__ClearIllusts; // 0x30
	private static DelegateBridge __Hotfix0__LoadAndSetIllusts; // 0x38
	private static DelegateBridge __Hotfix0__RefreshViews; // 0x40
	private static DelegateBridge __Hotfix0__RefreshItemCardView; // 0x48
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x50
	private static DelegateBridge __Hotfix0__OpenItemRepoPage; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x22943c4 VA: 0x75948ac3c4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x229442c VA: 0x75948ac42c
	protected override Void OnEnter() { }
	// RVA: 0x2294c74 VA: 0x75948acc74
	protected Void OnDestroy() { }
	// RVA: 0x2294e04 VA: 0x75948ace04
	public Void OnDetailClick() { }
	// RVA: 0x2294f0c VA: 0x75948acf0c
	public Void OnUpgradeConfirmClick() { }
	// RVA: 0x2295154 VA: 0x75948ad154
	public Void OnCancelClick() { }
	// RVA: 0x2294cdc VA: 0x75948accdc
	private Void _ClearIllusts() { }
	// RVA: 0x229483c VA: 0x75948ac83c
	private Void _LoadAndSetIllusts() { }
	// RVA: 0x2294b24 VA: 0x75948acb24
	private Void _RefreshViews() { }
	// RVA: 0x22951e8 VA: 0x75948ad1e8
	private Void _RefreshItemCardView() { }
	// RVA: 0x2295568 VA: 0x75948ad568
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x2295670 VA: 0x75948ad670
	private Void _OpenItemRepoPage() { }
	// RVA: 0x2295754 VA: 0x75948ad754
	public Void .ctor() { }
	// RVA: 0x22957e8 VA: 0x75948ad7e8
	private Void <OnUpgradeConfirmClick>b__21_0(EvolveCharUseItemResponse response) { }
	// RVA: 0x22959c0 VA: 0x75948ad9c0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```