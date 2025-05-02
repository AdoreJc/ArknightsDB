# RoguelikeTopicBankState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RectTransform _rewardViewParent`

- `RoguelikeTopicBankRewardView _rewardViewPrefab`

- `RoguelikeNpcDialogView _dialogView`

- `Text _textDeposit`

- `Boolean m_hasInited`

- `RoguelikeTopicBankRewardView m_rewardView`

- `String m_topicId`

- `RoguelikeGameShopDialogProp m_dialogProp`


## Methods

- `Int32 _GetDeposit()`

- `Void _InitIfNot()`

- `Void _UpdateNpcDialog(RoguelikeGameShopDialogType)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBankState : PopupFadeState
{
	private RectTransform _rewardViewParent; // 0x70
	private RoguelikeTopicBankRewardView _rewardViewPrefab; // 0x78
	private RoguelikeNpcDialogView _dialogView; // 0x80
	private Text _textDeposit; // 0x88
	private Boolean m_hasInited; // 0x90
	private RoguelikeTopicBankRewardView m_rewardView; // 0x98
	private String m_topicId; // 0xa0
	private RoguelikeGameShopDialogProp m_dialogProp; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__GetDeposit; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__UpdateNpcDialog; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2634eec VA: 0x7594c4ceec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2634f50 VA: 0x7594c4cf50
	protected override Void OnEnter() { }
	// RVA: 0x2635280 VA: 0x7594c4d280
	private Int32 _GetDeposit() { }
	// RVA: 0x263512c VA: 0x7594c4d12c
	private Void _InitIfNot() { }
	// RVA: 0x26352f8 VA: 0x7594c4d2f8
	private Void _UpdateNpcDialog(RoguelikeGameShopDialogType dialogType) { }
	// RVA: 0x26353cc VA: 0x7594c4d3cc
	public Void .ctor() { }
	// RVA: 0x263543c VA: 0x7594c4d43c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```