# ResultPanel

**Namespace:** ` `


## Fields

- `CrisisV2DiagramView _diagramItemPrefab`

- `Transform _diagramHolder`

- `Text _txtScore`

- `Image _imgAppraise`

- `CrisisV2SettleRuneListAdapter _runeListAdapter`

- `GameObject _objRuneMoreTips`

- `GameObject _panelHp`

- `Text _txtHp`

- `Text _txtTimestamp`

- `Text _txtPlayerName`

- `Text _txtMapName`

- `Text _txtMapCode`

- `Transform _illustTrans`

- `CrisisV2SettleCardViewHolder _assistCardHolder`

- `CrisisV2SettleCardView _cardViewPrefab`

- `UIAnimationLocation _animResultEnter`

- `GameObject _objResultPanel`

- `CharUISkinStruct m_randomIllust`

- `Boolean m_playHardModeVoice`

- `Tween m_tweener`

- `CrisisV2DiagramView m_diagramItem`

- `UICharacterIllust m_cacheIllust`


## Methods

- `Void Render(CrisisV2SettleViewModel, UICharacterIllustLoader, ILoadAsset)`

- `Void PlayIllustVoice()`

- `Void PlayResultEnterAnim(TweenCallback)`

- `Void HidePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ResultPanel : IHotfixable
{
	private CrisisV2DiagramView _diagramItemPrefab; // 0x10
	private Transform _diagramHolder; // 0x18
	private Text _txtScore; // 0x20
	private Image _imgAppraise; // 0x28
	private CrisisV2SettleRuneListAdapter _runeListAdapter; // 0x30
	private GameObject _objRuneMoreTips; // 0x38
	private GameObject _panelHp; // 0x40
	private Text _txtHp; // 0x48
	private Text _txtTimestamp; // 0x50
	private Text _txtPlayerName; // 0x58
	private Text _txtMapName; // 0x60
	private Text _txtMapCode; // 0x68
	private Transform _illustTrans; // 0x70
	private List`1 _cardHolderList; // 0x78
	private CrisisV2SettleCardViewHolder _assistCardHolder; // 0x80
	private CrisisV2SettleCardView _cardViewPrefab; // 0x88
	private UIAnimationLocation _animResultEnter; // 0x90
	private GameObject _objResultPanel; // 0xa0
	private CharUISkinStruct m_randomIllust; // 0xa8
	private Boolean m_playHardModeVoice; // 0xb8
	private Tween m_tweener; // 0xc0
	private CrisisV2DiagramView m_diagramItem; // 0xc8
	private UICharacterIllust m_cacheIllust; // 0xd0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayIllustVoice; // 0x8
	private static DelegateBridge __Hotfix0_PlayResultEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0_HidePanel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bd3458 VA: 0x75951eb458
	public Void Render(CrisisV2SettleViewModel viewModel, UICharacterIllustLoader illustLoader, ILoadAsset assetLoader) { }
	// RVA: 0x2bd3af0 VA: 0x75951ebaf0
	public Void PlayIllustVoice() { }
	// RVA: 0x2bd3d1c VA: 0x75951ebd1c
	public Void PlayResultEnterAnim(TweenCallback onNewCompleteAnimPlayFinish) { }
	// RVA: 0x2bd1854 VA: 0x75951e9854
	public Void HidePanel() { }
	// RVA: 0x2bd3da0 VA: 0x75951ebda0
	public Void .ctor() { }
}
```