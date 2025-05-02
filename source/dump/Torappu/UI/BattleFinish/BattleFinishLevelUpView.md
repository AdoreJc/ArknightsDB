# BattleFinishLevelUpView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `UIBlurFloatPanel _backImage`

- `Text _lvl`

- `Text _lvlUpText`

- `Text _lvlRecoverText`

- `GameObject _lvlUpObj`

- `MeshRenderer _circleYellow`

- `MeshRenderer _cirlceLight`

- `RectTransform _panelLvlUp`

- `Boolean <onCircleFlag>k__BackingField`

- `Int32 m_level`

- `Int32 m_targetLevel`

- `Single m_percent`

- `Action <onCloseClicked>k__BackingField`


## Properties

- `Boolean onCircleFlag`

- `Action onCloseClicked`


## Methods

- `Boolean get_onCircleFlag()`

- `Void set_onCircleFlag(Boolean)`

- `Action get_onCloseClicked()`

- `Void set_onCloseClicked(Action)`

- `Void InitLevel(Int32, Int32, Int32)`

- `IEnumerator Circle()`

- `Void EventOnCloseClicked()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _UpLevel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishLevelUpView : MonoBehaviour, IHotfixable, IValueMsgReceiver
{
	private const Single MIN_ROUND_ANGLE; // 0x0
	private UIBlurFloatPanel _backImage; // 0x18
	private Text _lvl; // 0x20
	private Text _lvlUpText; // 0x28
	private Text _lvlRecoverText; // 0x30
	private GameObject _lvlUpObj; // 0x38
	private MeshRenderer _circleYellow; // 0x40
	private MeshRenderer _cirlceLight; // 0x48
	private RectTransform _panelLvlUp; // 0x50
	private Boolean <onCircleFlag>k__BackingField; // 0x58
	private Int32 m_level; // 0x5c
	private Int32 m_targetLevel; // 0x60
	private Single m_percent; // 0x64
	private Action <onCloseClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onCircleFlag; // 0x0
	private static DelegateBridge __Hotfix0_set_onCircleFlag; // 0x8
	private static DelegateBridge __Hotfix0_get_onCloseClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onCloseClicked; // 0x18
	private static DelegateBridge __Hotfix0_InitLevel; // 0x20
	private static DelegateBridge __Hotfix0_Circle; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__UpLevel; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean onCircleFlag { get; set; }
	private Action onCloseClicked { get; set; }

	// RVA: 0x2e92d3c VA: 0x75954aad3c
	public Boolean get_onCircleFlag() { }
	// RVA: 0x2e92da4 VA: 0x75954aada4
	private Void set_onCircleFlag(Boolean value) { }
	// RVA: 0x2e92e24 VA: 0x75954aae24
	private Action get_onCloseClicked() { }
	// RVA: 0x2e92e8c VA: 0x75954aae8c
	public Void set_onCloseClicked(Action value) { }
	// RVA: 0x2e92f10 VA: 0x75954aaf10
	public Void InitLevel(Int32 level, Int32 targetLevel, Int32 exp) { }
	// RVA: 0x2e932c0 VA: 0x75954ab2c0
	public IEnumerator Circle() { }
	// RVA: 0x2e93394 VA: 0x75954ab394
	public Void EventOnCloseClicked() { }
	// RVA: 0x2e93404 VA: 0x75954ab404
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2e934ac VA: 0x75954ab4ac
	private Void _UpLevel() { }
	// RVA: 0x2e93584 VA: 0x75954ab584
	public Void .ctor() { }
}
```