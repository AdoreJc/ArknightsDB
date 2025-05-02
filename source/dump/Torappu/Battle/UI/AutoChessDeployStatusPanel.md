# AutoChessDeployStatusPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIAnimationLocation _exceedAnim`

- `UIAnimationLocation _fullAnim`

- `Text _deployExceedText`

- `Text _deployFullText`

- `Param m_param`

- `State m_state`


## Methods

- `Void Render(Param)`

- `Void Hide()`

- `Void _PlayAnimLocationIfNotActive(UIAnimationLocation)`

- `Void _UpdateState(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessDeployStatusPanel : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _exceedAnim; // 0x18
	private UIAnimationLocation _fullAnim; // 0x28
	private Text _deployExceedText; // 0x38
	private Text _deployFullText; // 0x40
	private Param m_param; // 0x48
	private State m_state; // 0x54
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0__PlayAnimLocationIfNotActive; // 0x10
	private static DelegateBridge __Hotfix0__UpdateState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x201ef6c VA: 0x7594636f6c
	public Void Render(Param param) { }
	// RVA: 0x201f41c VA: 0x759463741c
	public Void Hide() { }
	// RVA: 0x201f1e8 VA: 0x75946371e8
	private Void _PlayAnimLocationIfNotActive(UIAnimationLocation loaction) { }
	// RVA: 0x201f2dc VA: 0x75946372dc
	private Void _UpdateState(State state) { }
	// RVA: 0x201f4b8 VA: 0x75946374b8
	public Void .ctor() { }
}
```