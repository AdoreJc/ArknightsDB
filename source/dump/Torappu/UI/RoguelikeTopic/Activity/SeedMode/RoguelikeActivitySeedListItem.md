# RoguelikeActivitySeedListItem

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `GameObject _emptyPanel`

- `GameObject _seedPanel`

- `GameObject _historyIconPanel`

- `UIAtlasImage _historyEndingIcon`

- `Image _historyBandIcon`

- `GameObject _predefineIconPanel`

- `Text _seedTxt`

- `GameObject _copyBtn`

- `Text _historyEndTime`

- `Text _historyGameDesc`

- `GameObject _historyDescPanel`

- `Text _predefineDesc`

- `GameObject _predefineDescPanel`

- `GameObject _selectSeedBtn`

- `GameObject _seedPlaying`

- `UIPageFinder m_pageFinder`

- `String m_cachedSeed`


## Methods

- `Void Render(RoguelikeActivitySeedItemModel, Boolean, ILoadAsset)`

- `Void _RenderHistory(RoguelikeActivityHistorySeedItemModel, ILoadAsset)`

- `Void _RenderPredefine(RoguelikeActivityPredefineSeedItemModel)`

- `Void OnClickSelectSeed()`

- `Void OnClickCopySeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedListItem : MonoBehaviour, IHotfixable
{
	private const String HISTORY_GAME_DESC_FORMAT; // 0x0
	private GameObject _emptyPanel; // 0x18
	private GameObject _seedPanel; // 0x20
	private GameObject _historyIconPanel; // 0x28
	private UIAtlasImage _historyEndingIcon; // 0x30
	private Image _historyBandIcon; // 0x38
	private GameObject _predefineIconPanel; // 0x40
	private Text _seedTxt; // 0x48
	private GameObject _copyBtn; // 0x50
	private Text _historyEndTime; // 0x58
	private Text _historyGameDesc; // 0x60
	private GameObject _historyDescPanel; // 0x68
	private Text _predefineDesc; // 0x70
	private GameObject _predefineDescPanel; // 0x78
	private GameObject _selectSeedBtn; // 0x80
	private GameObject _seedPlaying; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private String m_cachedSeed; // 0xa0
	public Action`1 onClickSelectSeed; // 0xa8
	public Action`1 onClickCopySeed; // 0xb0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderHistory; // 0x8
	private static DelegateBridge __Hotfix0__RenderPredefine; // 0x10
	private static DelegateBridge __Hotfix0_OnClickSelectSeed; // 0x18
	private static DelegateBridge __Hotfix0_OnClickCopySeed; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26e1c40 VA: 0x7594cf9c40
	public Void Render(RoguelikeActivitySeedItemModel itemModel, Boolean isPlaying, ILoadAsset iLoadAsset) { }
	// RVA: 0x26e1f1c VA: 0x7594cf9f1c
	private Void _RenderHistory(RoguelikeActivityHistorySeedItemModel historyModel, ILoadAsset iLoadAsset) { }
	// RVA: 0x26e21e0 VA: 0x7594cfa1e0
	private Void _RenderPredefine(RoguelikeActivityPredefineSeedItemModel predefineModel) { }
	// RVA: 0x26e2288 VA: 0x7594cfa288
	public Void OnClickSelectSeed() { }
	// RVA: 0x26e2310 VA: 0x7594cfa310
	public Void OnClickCopySeed() { }
	// RVA: 0x26e2398 VA: 0x7594cfa398
	public Void .ctor() { }
}
```