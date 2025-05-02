# UICooperateBattleStartPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UIStageInfo _stageInfo`

- `Animation _animation`

- `AnimationClip _startClip`

- `AnimationClip _loopClip`

- `AnimationClip _endClip`

- `Boolean m_startToPlay`

- `Action m_finishCb`

- `FP m_progress`

- `AnimationState m_animationState`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void Init()`

- `Void ShowStart(Action)`

- `Void ShowLoop()`

- `Void ShowEnd(Action)`

- `Void Awake()`

- `Void Start()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleStartPanel : MonoBehaviour, IHotfixable
{
	private UIStageInfo _stageInfo; // 0x18
	private Animation _animation; // 0x20
	private AnimationClip _startClip; // 0x28
	private AnimationClip _loopClip; // 0x30
	private AnimationClip _endClip; // 0x38
	private Boolean m_startToPlay; // 0x40
	private Action m_finishCb; // 0x48
	private FP m_progress; // 0x50
	private AnimationState m_animationState; // 0x58
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_ShowStart; // 0x10
	private static DelegateBridge __Hotfix0_ShowLoop; // 0x18
	private static DelegateBridge __Hotfix0_ShowEnd; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x20c93a8 VA: 0x75946e13a8
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20c953c VA: 0x75946e153c
	public Void Init() { }
	// RVA: 0x20c95f4 VA: 0x75946e15f4
	public Void ShowStart(Action finishCb) { }
	// RVA: 0x20c96bc VA: 0x75946e16bc
	public Void ShowLoop() { }
	// RVA: 0x20c9770 VA: 0x75946e1770
	public Void ShowEnd(Action finishCb) { }
	// RVA: 0x20c98bc VA: 0x75946e18bc
	private Void Awake() { }
	// RVA: 0x20c9930 VA: 0x75946e1930
	private Void Start() { }
	// RVA: 0x20c9a28 VA: 0x75946e1a28
	private Void Update() { }
	// RVA: 0x20c9b04 VA: 0x75946e1b04
	public Void .ctor() { }
}
```