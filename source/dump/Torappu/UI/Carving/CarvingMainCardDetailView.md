# CarvingMainCardDetailView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAnimationLocation _animPanelSwitch`

- `UIAnimationLocation _transferAnim`

- `UIAtlasObject _atlasObject`

- `GameObject _cardUpgradeNotice`

- `UIAtlasImage _bkgCardLevel`

- `UIAtlasImage _bkgCardFaceType`

- `TwoStateToggle _cardLevelToggle`

- `UIAtlasImage _cardLevel`

- `UIAtlasImage _cardUpgradeCurLevel`

- `UIAtlasImage _cardUpgradeNextLevel`

- `Text _title`

- `GameObject _maxLevel`

- `Text _cardDesc`

- `Boolean m_inited`

- `AnimationSwitchTween m_panelSwitchTween`

- `Tween m_transferTween`

- `Int32 m_cachedSelectSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void _RenderTargetTransfer(List`1, List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainCardDetailView : DataBinder`1
{
	private const String CARD_LEVEL_IMG; // 0x0
	private const String CARD_UPGRADE_LEVEL_IMAGE; // 0x0
	private UIAnimationLocation _animPanelSwitch; // 0x20
	private UIAnimationLocation _transferAnim; // 0x30
	private UIAtlasObject _atlasObject; // 0x40
	private GameObject _cardUpgradeNotice; // 0x48
	private UIAtlasImage _bkgCardLevel; // 0x50
	private UIAtlasImage _bkgCardFaceType; // 0x58
	private TwoStateToggle _cardLevelToggle; // 0x60
	private UIAtlasImage _cardLevel; // 0x68
	private UIAtlasImage _cardUpgradeCurLevel; // 0x70
	private UIAtlasImage _cardUpgradeNextLevel; // 0x78
	private List`1 _cardTransfers; // 0x80
	private Text _title; // 0x88
	private GameObject _maxLevel; // 0x90
	private Text _cardDesc; // 0x98
	private Boolean m_inited; // 0xa0
	private AnimationSwitchTween m_panelSwitchTween; // 0xa8
	private Tween m_transferTween; // 0xb0
	private Int32 m_cachedSelectSeqNum; // 0xb8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderTargetTransfer; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2da5900 VA: 0x75953bd900
	public override Void OnValueChanged(CarvingMainProperty property) { }
	// RVA: 0x2da5d20 VA: 0x75953bdd20
	private Void _InitIfNot() { }
	// RVA: 0x2da6168 VA: 0x75953be168
	private Void _RenderTargetTransfer(List`1 inputMaterials, List`1 outputMaterials, Int32 selectSeqNum) { }
	// RVA: 0x2da6508 VA: 0x75953be508
	public Void .ctor() { }
}
```