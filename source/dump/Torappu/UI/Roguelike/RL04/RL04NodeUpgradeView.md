# RL04NodeUpgradeView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _imgTitle`

- `RL04NodeUpgradeMuralView _muralPrefab`

- `RectTransform _muralContainer`

- `Single _muralPermCompleteDuration`

- `Text _textTypeName`

- `SimpleLayoutContent _permList`

- `SimpleLayoutContent _tempList`

- `UIAtlasImage _imgTempCaptionLine`

- `UIAtlasImage _imgTempCaptionIcon`

- `Text _textTempCaption`

- `GameObject _lockTempIconGo`

- `GameObject _todoTempIconGo`

- `GameObject _unlockTempIconGo`

- `UIAtlasImage _imgTempInfoLine`

- `Image _imgBtnConfirmBg`

- `GameObject _confirmToDoGo`

- `GameObject _confirmCompleteGo`

- `Text _textBtnName`

- `Text _textItemCost`

- `Text _textItemCount`

- `UIAnimationLocation _animEnter`

- `RL04NodeUpgradeConfig m_config`

- `Boolean m_hasInited`

- `PermListAdapter m_permListAdapter`

- `TempListAdapter m_tempListAdapter`

- `RL04NodeUpgradeModel m_upgradeModel`

- `RL04NodeUpgradeMuralView m_muralView`

- `Int32 m_cacheEnterSeq`

- `Int32 m_cacheCompleteSeq`

- `Tween m_enterTween`


## Methods

- `Void _PlayEnterAnimIfNeed()`

- `Void _RenderView()`

- `Void _RenderBtnConfirmPanel()`

- `Void _InitIfNot()`

- `Void SetConfig(RL04NodeUpgradeConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04NodeUpgradeView : DataBinder`1
{
	private Image _imgTitle; // 0x20
	private RL04NodeUpgradeMuralView _muralPrefab; // 0x28
	private RectTransform _muralContainer; // 0x30
	private Single _muralPermCompleteDuration; // 0x38
	private Text _textTypeName; // 0x40
	private SimpleLayoutContent _permList; // 0x48
	private SimpleLayoutContent _tempList; // 0x50
	private UIAtlasImage _imgTempCaptionLine; // 0x58
	private UIAtlasImage _imgTempCaptionIcon; // 0x60
	private Text _textTempCaption; // 0x68
	private GameObject _lockTempIconGo; // 0x70
	private GameObject _todoTempIconGo; // 0x78
	private GameObject _unlockTempIconGo; // 0x80
	private UIAtlasImage _imgTempInfoLine; // 0x88
	private Image _imgBtnConfirmBg; // 0x90
	private GameObject _confirmToDoGo; // 0x98
	private GameObject _confirmCompleteGo; // 0xa0
	private Text _textBtnName; // 0xa8
	private Text _textItemCost; // 0xb0
	private Text _textItemCount; // 0xb8
	private UIAnimationLocation _animEnter; // 0xc0
	private RL04NodeUpgradeConfig m_config; // 0xd0
	private Boolean m_hasInited; // 0xd8
	private PermListAdapter m_permListAdapter; // 0xe0
	private TempListAdapter m_tempListAdapter; // 0xe8
	private RL04NodeUpgradeModel m_upgradeModel; // 0xf0
	private RL04NodeUpgradeMuralView m_muralView; // 0xf8
	private Int32 m_cacheEnterSeq; // 0x100
	private Int32 m_cacheCompleteSeq; // 0x104
	private Dictionary`2 m_cacheMuralShowSeqNumDict; // 0x108
	private Tween m_enterTween; // 0x110
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayEnterAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__RenderView; // 0x10
	private static DelegateBridge __Hotfix0__GenerateShowAnimIdxList; // 0x18
	private static DelegateBridge __Hotfix0__RenderBtnConfirmPanel; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_SetConfig; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2b34020 VA: 0x759514c020
	public override Void OnValueChanged(RL04NodeUpgradeProp property) { }
	// RVA: 0x2b34660 VA: 0x759514c660
	private Void _PlayEnterAnimIfNeed() { }
	// RVA: 0x2b342c8 VA: 0x759514c2c8
	private Void _RenderView() { }
	// RVA: 0x2b34a8c VA: 0x759514ca8c
	private List`1 _GenerateShowAnimIdxList() { }
	// RVA: 0x2b34788 VA: 0x759514c788
	private Void _RenderBtnConfirmPanel() { }
	// RVA: 0x2b34120 VA: 0x759514c120
	private Void _InitIfNot() { }
	// RVA: 0x2b30324 VA: 0x7595148324
	public Void SetConfig(RL04NodeUpgradeConfig config) { }
	// RVA: 0x2b34d38 VA: 0x759514cd38
	public Void .ctor() { }
}
```