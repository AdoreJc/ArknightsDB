# GameCityRestingPanel

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `Text _timeText`

- `Text skipTitle`

- `Text skipInfo`

- `Button _skipButton`

- `AnimationWrapper _buttonAnimationWrapper`

- `Boolean buttonClicked`


## Methods

- `Void OnInit()`

- `Void OnUpdate(Int32)`

- `Void OnButtonClick()`

- `Void _Oncomplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCityRestingPanel : MonoBehaviour, IHotfixable
{
	private const String BUTTON_ANIMATION_KEY; // 0x0
	private Text _timeText; // 0x18
	private Text skipTitle; // 0x20
	private Text skipInfo; // 0x28
	private Button _skipButton; // 0x30
	private AnimationWrapper _buttonAnimationWrapper; // 0x38
	private Boolean buttonClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0_OnButtonClick; // 0x10
	private static DelegateBridge __Hotfix0__Oncomplete; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x33ea844 VA: 0x7595a02844
	public Void OnInit() { }
	// RVA: 0x33ea95c VA: 0x7595a0295c
	public Void OnUpdate(Int32 time) { }
	// RVA: 0x33eaa24 VA: 0x7595a02a24
	public Void OnButtonClick() { }
	// RVA: 0x33eab94 VA: 0x7595a02b94
	private Void _Oncomplete() { }
	// RVA: 0x33eacb4 VA: 0x7595a02cb4
	public Void .ctor() { }
}
```