# ActMultiV3SeasonResCollector

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Sprite _entryAnimLogo`

- `Sprite _entryManualLogo`

- `Sprite _entrySeasonLogo`

- `Color _seasonThemeColor`

- `Sprite _seasonTokenSmallIcon`

- `Sprite _seasonBottomBarIcon`

- `Sprite _manualLogo`

- `GameObject _prepareLoopAnimObj`

- `Sprite _stageDetailSeasonIcon`

- `Sprite _entranceShowSeasonIcon`

- `GameObject _matchLoopAnimObj`

- `ActMultiV3MilestoneMainRewardView _mainRewardView`

- `Sprite _milestoneBg`


## Properties

- `Sprite entryAnimLogo`

- `Sprite entryManualLogo`

- `Sprite entrySeasonLogo`

- `Sprite manualLogo`

- `Color seasonThemeColor`

- `Sprite seasonTokenSmallIcon`

- `Sprite seasonBottomBarIcon`

- `GameObject prepareLoopAnimObj`

- `GameObject matchLoopAnimObj`

- `Sprite stageDetailSeasonIcon`

- `Sprite entranceShowSeasonIcon`

- `ActMultiV3MilestoneMainRewardView milestoneMainRewardView`

- `Sprite milestoneBg`


## Methods

- `Sprite get_entryAnimLogo()`

- `Sprite get_entryManualLogo()`

- `Sprite get_entrySeasonLogo()`

- `Sprite get_manualLogo()`

- `Color get_seasonThemeColor()`

- `Sprite get_seasonTokenSmallIcon()`

- `Sprite get_seasonBottomBarIcon()`

- `GameObject get_prepareLoopAnimObj()`

- `GameObject get_matchLoopAnimObj()`

- `Sprite get_stageDetailSeasonIcon()`

- `Sprite get_entranceShowSeasonIcon()`

- `ActMultiV3MilestoneMainRewardView get_milestoneMainRewardView()`

- `Sprite get_milestoneBg()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SeasonResCollector : MonoBehaviour, IHotfixable
{
	private Sprite _entryAnimLogo; // 0x18
	private Sprite _entryManualLogo; // 0x20
	private Sprite _entrySeasonLogo; // 0x28
	private Color _seasonThemeColor; // 0x30
	private Sprite _seasonTokenSmallIcon; // 0x40
	private Sprite _seasonBottomBarIcon; // 0x48
	private Sprite _manualLogo; // 0x50
	private GameObject _prepareLoopAnimObj; // 0x58
	private Sprite _stageDetailSeasonIcon; // 0x60
	private Sprite _entranceShowSeasonIcon; // 0x68
	private GameObject _matchLoopAnimObj; // 0x70
	private BillboardModeLoopAnimConfig[] _billboardModeLoopAnims; // 0x78
	private ActMultiV3MilestoneMainRewardView _mainRewardView; // 0x80
	private Sprite _milestoneBg; // 0x88
	private static DelegateBridge __Hotfix0_get_entryAnimLogo; // 0x0
	private static DelegateBridge __Hotfix0_get_entryManualLogo; // 0x8
	private static DelegateBridge __Hotfix0_get_entrySeasonLogo; // 0x10
	private static DelegateBridge __Hotfix0_get_manualLogo; // 0x18
	private static DelegateBridge __Hotfix0_get_seasonThemeColor; // 0x20
	private static DelegateBridge __Hotfix0_get_seasonTokenSmallIcon; // 0x28
	private static DelegateBridge __Hotfix0_get_seasonBottomBarIcon; // 0x30
	private static DelegateBridge __Hotfix0_get_prepareLoopAnimObj; // 0x38
	private static DelegateBridge __Hotfix0_get_matchLoopAnimObj; // 0x40
	private static DelegateBridge __Hotfix0_get_stageDetailSeasonIcon; // 0x48
	private static DelegateBridge __Hotfix0_get_entranceShowSeasonIcon; // 0x50
	private static DelegateBridge __Hotfix0_get_milestoneMainRewardView; // 0x58
	private static DelegateBridge __Hotfix0_get_milestoneBg; // 0x60
	private static DelegateBridge __Hotfix0_get_billboardModeLoopAnims; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Sprite entryAnimLogo { get; }
	public Sprite entryManualLogo { get; }
	public Sprite entrySeasonLogo { get; }
	public Sprite manualLogo { get; }
	public Color seasonThemeColor { get; }
	public Sprite seasonTokenSmallIcon { get; }
	public Sprite seasonBottomBarIcon { get; }
	public GameObject prepareLoopAnimObj { get; }
	public GameObject matchLoopAnimObj { get; }
	public Sprite stageDetailSeasonIcon { get; }
	public Sprite entranceShowSeasonIcon { get; }
	public ActMultiV3MilestoneMainRewardView milestoneMainRewardView { get; }
	public Sprite milestoneBg { get; }
	public BillboardModeLoopAnimConfig[] billboardModeLoopAnims { get; }

	// RVA: 0x30dbcdc VA: 0x75956f3cdc
	public Sprite get_entryAnimLogo() { }
	// RVA: 0x30dbd44 VA: 0x75956f3d44
	public Sprite get_entryManualLogo() { }
	// RVA: 0x30dbdac VA: 0x75956f3dac
	public Sprite get_entrySeasonLogo() { }
	// RVA: 0x30dbe14 VA: 0x75956f3e14
	public Sprite get_manualLogo() { }
	// RVA: 0x30dbe7c VA: 0x75956f3e7c
	public Color get_seasonThemeColor() { }
	// RVA: 0x30dbee4 VA: 0x75956f3ee4
	public Sprite get_seasonTokenSmallIcon() { }
	// RVA: 0x30dbf4c VA: 0x75956f3f4c
	public Sprite get_seasonBottomBarIcon() { }
	// RVA: 0x30dbfb4 VA: 0x75956f3fb4
	public GameObject get_prepareLoopAnimObj() { }
	// RVA: 0x30dc01c VA: 0x75956f401c
	public GameObject get_matchLoopAnimObj() { }
	// RVA: 0x30dc084 VA: 0x75956f4084
	public Sprite get_stageDetailSeasonIcon() { }
	// RVA: 0x30dc0ec VA: 0x75956f40ec
	public Sprite get_entranceShowSeasonIcon() { }
	// RVA: 0x30dc154 VA: 0x75956f4154
	public ActMultiV3MilestoneMainRewardView get_milestoneMainRewardView() { }
	// RVA: 0x30dc1bc VA: 0x75956f41bc
	public Sprite get_milestoneBg() { }
	// RVA: 0x30dc224 VA: 0x75956f4224
	public BillboardModeLoopAnimConfig[] get_billboardModeLoopAnims() { }
	// RVA: 0x30dc28c VA: 0x75956f428c
	public Void .ctor() { }
}
```