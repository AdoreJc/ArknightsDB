# UICooperateScoreStatusPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Text _allyScore`

- `Text _enemyScore`

- `GameObject _leadAnimGroup`

- `UIAnimationLocation _leadAnim`


## Methods

- `Void UpdateScoreInfo(Int32[])`

- `Boolean _IsAllyScored(Int32[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateScoreStatusPanel : MonoBehaviour, IHotfixable
{
	private Text _allyScore; // 0x18
	private Text _enemyScore; // 0x20
	private GameObject _leadAnimGroup; // 0x28
	private UIAnimationLocation _leadAnim; // 0x30
	private Int32[] m_cachedScoreInfo; // 0x40
	private static DelegateBridge __Hotfix0_UpdateScoreInfo; // 0x0
	private static DelegateBridge __Hotfix0__IsAllyScored; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20d1054 VA: 0x75946e9054
	public Void UpdateScoreInfo(Int32[] scoreInfo) { }
	// RVA: 0x20d1210 VA: 0x75946e9210
	private Boolean _IsAllyScored(Int32[] scoreInfo) { }
	// RVA: 0x20d12bc VA: 0x75946e92bc
	public Void .ctor() { }
}
```