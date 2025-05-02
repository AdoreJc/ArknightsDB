# UIBattleSystemMenuPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _fadeInTime`

- `GameObject _debugPanel`

- `Boolean m_isStyleInited`

- `StyleController m_currentStyle`

- `CanvasGroup m_canvasGroup`


## Properties

- `StyleController currentStyle`


## Methods

- `StyleController get_currentStyle()`

- `Void Show()`

- `Void Hide()`

- `Void OnInit()`

- `BattleReward GetEstimatedReward()`

- `Void SetData()`

- `Void _InitStyleIfNot()`

- `BattleReward _GetEstimatedReward(Single)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleSystemMenuPanel : MonoBehaviour
{
	private const String REWARD_STR_FORMAT; // 0x0
	private Single _fadeInTime; // 0x18
	private StyleController[] _menuStyles; // 0x20
	private GameObject _debugPanel; // 0x28
	private Boolean m_isStyleInited; // 0x30
	private StyleController m_currentStyle; // 0x38
	private CanvasGroup m_canvasGroup; // 0x40

	protected StyleController currentStyle { get; }

	// RVA: 0x2046da0 VA: 0x759465eda0
	protected StyleController get_currentStyle() { }
	// RVA: 0x2046f9c VA: 0x759465ef9c
	public Void Show() { }
	// RVA: 0x204712c VA: 0x759465f12c
	public Void Hide() { }
	// RVA: 0x20471e0 VA: 0x759465f1e0
	public Void OnInit() { }
	// RVA: 0x20471e4 VA: 0x759465f1e4
	public BattleReward GetEstimatedReward() { }
	// RVA: 0x204704c VA: 0x759465f04c
	protected Void SetData() { }
	// RVA: 0x2046db8 VA: 0x759465edb8
	private Void _InitStyleIfNot() { }
	// RVA: 0x2047264 VA: 0x759465f264
	private BattleReward _GetEstimatedReward(Single progress) { }
	// RVA: 0x20476e0 VA: 0x759465f6e0
	private Void Awake() { }
	// RVA: 0x2047738 VA: 0x759465f738
	public Void .ctor() { }
}
```