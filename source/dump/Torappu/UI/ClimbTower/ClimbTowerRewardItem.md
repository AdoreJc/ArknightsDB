# ClimbTowerRewardItem

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Single _itemCardScale`

- `Text _textCurr`

- `Text _textTotal`

- `Text _textDesc`

- `GameObject _panelNormal`

- `GameObject _panelAvailable`

- `SimpleLayoutContent _rewardContainer`

- `Text _textState`

- `GameObject _panelCompleted`

- `Boolean m_inited`

- `Int32 m_cachedLayerNum`

- `Adapter m_adapter`


## Methods

- `Void set_onReceiveRewardClicked(Action`1)`

- `Void _InitIfNot()`

- `Void Render(ClimbTowerRewardModel, ClimbTowerViewModel)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRewardItem : MonoBehaviour, IHotfixable
{
	private const String MAX_LAYER_FORMAT; // 0x0
	private static readonly Color COLOR_AVAILABLE; // 0x0
	private static readonly Color COLOR_NORMAL; // 0x10
	private Single _itemCardScale; // 0x18
	private Text _textCurr; // 0x20
	private Text _textTotal; // 0x28
	private Text _textDesc; // 0x30
	private GameObject _panelNormal; // 0x38
	private GameObject _panelAvailable; // 0x40
	private SimpleLayoutContent _rewardContainer; // 0x48
	private Text _textState; // 0x50
	private GameObject _panelCompleted; // 0x58
	private Boolean m_inited; // 0x60
	private List`1 m_cachedRewardList; // 0x68
	private Int32 m_cachedLayerNum; // 0x70
	private Adapter m_adapter; // 0x78
	private Action`1 m_onReceiveRewardClicked; // 0x80
	private static DelegateBridge __Hotfix0_set_onReceiveRewardClicked; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Action`1 onReceiveRewardClicked { set; }

	// RVA: 0x2c75ba0 VA: 0x759528dba0
	public Void set_onReceiveRewardClicked(Action`1 value) { }
	// RVA: 0x2c75c34 VA: 0x759528dc34
	private Void _InitIfNot() { }
	// RVA: 0x2c75da8 VA: 0x759528dda8
	public Void Render(ClimbTowerRewardModel model, ClimbTowerViewModel towerModel) { }
	// RVA: 0x2c760f0 VA: 0x759528e0f0
	public Void OnBtnClicked() { }
	// RVA: 0x2c76188 VA: 0x759528e188
	public Void .ctor() { }
	// RVA: 0x2c76210 VA: 0x759528e210
	private static Void .cctor() { }
}
```