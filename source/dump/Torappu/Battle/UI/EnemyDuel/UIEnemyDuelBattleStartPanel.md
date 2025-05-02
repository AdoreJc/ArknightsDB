# UIEnemyDuelBattleStartPanel

**Namespace:** `Torappu.Battle.UI.EnemyDuel`


## Fields

- `Image _backgroundImage`

- `UIStageInfo _stageInfo`


## Methods

- `Void Init()`

- `Void ShowLoop()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.EnemyDuel
public class UIEnemyDuelBattleStartPanel : MonoBehaviour, IHotfixable
{
	private const String DEFAULT_LOADING_PIC; // 0x0
	private Image _backgroundImage; // 0x18
	private UIStageInfo _stageInfo; // 0x20
	private UIAnimationLocation[] _loopAnims; // 0x28
	private List`1 m_animTweens; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_ShowLoop; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x20902a4 VA: 0x75946a82a4
	public Void Init() { }
	// RVA: 0x2090550 VA: 0x75946a8550
	public Void ShowLoop() { }
	// RVA: 0x2090764 VA: 0x75946a8764
	private Void OnDestroy() { }
	// RVA: 0x2090850 VA: 0x75946a8850
	public Void .ctor() { }
}
```