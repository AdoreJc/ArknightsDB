# CrisisV2MapNodePreviewView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Text _previewTitleText`

- `Text _previewDescText`

- `SimpleLayoutContent _rewardContent`

- `SimpleLayoutContent _requiredRuneContent`

- `GameObject _requiredRuneGo`

- `TwoStateToggle _runeToggle`

- `SimpleLayoutContent _requiredBagContent`

- `GameObject _requiredBagGo`

- `TwoStateToggle _bagToggle`

- `RectTransform _previewBackBtn`

- `GameObject _panelTutorialFocus`

- `UIAnimationLocation _switchAnim`

- `Single _switchDuration`

- `CrisisV2MapModel m_mapModel`

- `CrisisV2PreviewInfo m_previewInfo`

- `Boolean m_initIfNot`

- `RewardAdapter m_rewardAdapter`

- `RelateRuneAdapter m_relateRuneAdapter`

- `RelateBagAdapter m_relateBagAdapter`

- `AnimationSwitchTween m_switchTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void RegisterTutorialGo()`

- `Void _InitIfNot()`

- `String _GetProcessedPreviewDesc(CrisisV2MapModel, ref)`

- `Void OnClosePreviewClicked()`

- `Void _OnHidePreviewComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapNodePreviewView : DataBinder`1, IHotfixable
{
	private Text _previewTitleText; // 0x20
	private Text _previewDescText; // 0x28
	private SimpleLayoutContent _rewardContent; // 0x30
	private SimpleLayoutContent _requiredRuneContent; // 0x38
	private GameObject _requiredRuneGo; // 0x40
	private TwoStateToggle _runeToggle; // 0x48
	private SimpleLayoutContent _requiredBagContent; // 0x50
	private GameObject _requiredBagGo; // 0x58
	private TwoStateToggle _bagToggle; // 0x60
	private RectTransform _previewBackBtn; // 0x68
	private GameObject _panelTutorialFocus; // 0x70
	private UIAnimationLocation _switchAnim; // 0x78
	private Single _switchDuration; // 0x88
	private CrisisV2MapModel m_mapModel; // 0x90
	private CrisisV2PreviewInfo m_previewInfo; // 0x98
	private Boolean m_initIfNot; // 0xd0
	private RewardAdapter m_rewardAdapter; // 0xd8
	private RelateRuneAdapter m_relateRuneAdapter; // 0xe0
	private RelateBagAdapter m_relateBagAdapter; // 0xe8
	private AnimationSwitchTween m_switchTween; // 0xf0
	private UIStateFinder m_stateFinder; // 0xf8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_RegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetProcessedPreviewDesc; // 0x18
	private static DelegateBridge __Hotfix0_OnClosePreviewClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnHidePreviewComplete; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c05884 VA: 0x759521d884
	public override Void OnValueChanged(CrisisV2MapProp prop) { }
	// RVA: 0x2c06090 VA: 0x759521e090
	public Void RegisterTutorialGo() { }
	// RVA: 0x2c05b1c VA: 0x759521db1c
	private Void _InitIfNot() { }
	// RVA: 0x2c05e38 VA: 0x759521de38
	private String _GetProcessedPreviewDesc(CrisisV2MapModel mapModel, ref CrisisV2PreviewInfo previewInfo) { }
	// RVA: 0x2c06374 VA: 0x759521e374
	public Void OnClosePreviewClicked() { }
	// RVA: 0x2c06418 VA: 0x759521e418
	private Void _OnHidePreviewComplete() { }
	// RVA: 0x2c064bc VA: 0x759521e4bc
	public Void .ctor() { }
}
```