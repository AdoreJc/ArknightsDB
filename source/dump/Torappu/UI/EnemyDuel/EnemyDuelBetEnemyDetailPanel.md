# EnemyDuelBetEnemyDetailPanel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `UIAnimationLocation _animShow`

- `SimpleLayoutContent _layoutEnemyDetailList`

- `UISwitchTween m_showTween`

- `Boolean m_inited`

- `Boolean m_cachedIsLeft`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(EnemyDuelBetViewModel, Boolean)`

- `Void OnBtnHideClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetEnemyDetailPanel : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animShow; // 0x18
	private SimpleLayoutContent _layoutEnemyDetailList; // 0x28
	private UISwitchTween m_showTween; // 0x30
	private Boolean m_inited; // 0x38
	private List`1 m_cachedEnemyList; // 0x40
	private Boolean m_cachedIsLeft; // 0x48
	private Adapter m_adapter; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnHideClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x297961c VA: 0x7594f9161c
	private Void _InitIfNot() { }
	// RVA: 0x29797f8 VA: 0x7594f917f8
	public Void Render(EnemyDuelBetViewModel model, Boolean isLeft) { }
	// RVA: 0x29798f4 VA: 0x7594f918f4
	public Void OnBtnHideClicked() { }
	// RVA: 0x29799a8 VA: 0x7594f919a8
	public Void .ctor() { }
}
```