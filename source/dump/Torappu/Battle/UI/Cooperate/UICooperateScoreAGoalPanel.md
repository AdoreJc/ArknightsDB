# UICooperateScoreAGoalPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UIPerform _uiPerform`

- `Transform _allyImage`

- `Transform _enemyImage`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void OnUpdateScoreInfo(SideTypeIndex, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateScoreAGoalPanel : MonoBehaviour, IHotfixable
{
	public UIPerform _uiPerform; // 0x18
	private Transform _allyImage; // 0x20
	private Transform _enemyImage; // 0x28
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdateScoreInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20d0bec VA: 0x75946e8bec
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20d0d1c VA: 0x75946e8d1c
	public Void OnUpdateScoreInfo(SideTypeIndex sideTypeIndex, Action callback) { }
	// RVA: 0x20d0f28 VA: 0x75946e8f28
	public Void .ctor() { }
}
```