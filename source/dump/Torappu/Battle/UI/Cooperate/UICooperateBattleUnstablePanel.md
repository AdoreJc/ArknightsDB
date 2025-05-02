# UICooperateBattleUnstablePanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `RectTransform _dyingPanel`

- `CanvasGroup _dyingCanvasGroup`

- `Single _dyingFadeDuration`

- `AnimationWrapper _dyingWrapper`

- `String _dyingAnimName`

- `RectTransform _warningUnstablePanel`

- `CanvasGroup _unstableCanvasGroup`

- `Single _unstableFadeDuration`

- `AnimationWrapper _unstableWrapper`

- `String _unstableEnterAnimName`

- `String _unstableLoopAnimName`

- `Tween m_loopTween`


## Methods

- `Void InitLayout()`

- `Void ShowDyingPanel()`

- `Void ClearDyingPanel()`

- `Void ShowUnstablePanel()`

- `Void ClearUnstablePanel()`

- `Void <ClearDyingPanel>b__14_0()`

- `Void <ShowUnstablePanel>b__15_0()`

- `Void <ClearUnstablePanel>b__16_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleUnstablePanel : MonoBehaviour, IHotfixable
{
	private RectTransform _dyingPanel; // 0x18
	private CanvasGroup _dyingCanvasGroup; // 0x20
	private Single _dyingFadeDuration; // 0x28
	private AnimationWrapper _dyingWrapper; // 0x30
	private String _dyingAnimName; // 0x38
	private RectTransform _warningUnstablePanel; // 0x40
	private CanvasGroup _unstableCanvasGroup; // 0x48
	private Single _unstableFadeDuration; // 0x50
	private AnimationWrapper _unstableWrapper; // 0x58
	private String _unstableEnterAnimName; // 0x60
	private String _unstableLoopAnimName; // 0x68
	private Tween m_loopTween; // 0x70
	private static DelegateBridge __Hotfix0_InitLayout; // 0x0
	private static DelegateBridge __Hotfix0_ShowDyingPanel; // 0x8
	private static DelegateBridge __Hotfix0_ClearDyingPanel; // 0x10
	private static DelegateBridge __Hotfix0_ShowUnstablePanel; // 0x18
	private static DelegateBridge __Hotfix0_ClearUnstablePanel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x20c9ba8 VA: 0x75946e1ba8
	public Void InitLayout() { }
	// RVA: 0x20c9cf8 VA: 0x75946e1cf8
	public Void ShowDyingPanel() { }
	// RVA: 0x20c9df0 VA: 0x75946e1df0
	public Void ClearDyingPanel() { }
	// RVA: 0x20c9ee8 VA: 0x75946e1ee8
	public Void ShowUnstablePanel() { }
	// RVA: 0x20ca048 VA: 0x75946e2048
	public Void ClearUnstablePanel() { }
	// RVA: 0x20ca168 VA: 0x75946e2168
	public Void .ctor() { }
	// RVA: 0x20ca1e4 VA: 0x75946e21e4
	private Void <ClearDyingPanel>b__14_0() { }
	// RVA: 0x20ca1f4 VA: 0x75946e21f4
	private Void <ShowUnstablePanel>b__15_0() { }
	// RVA: 0x20ca2a0 VA: 0x75946e22a0
	private Void <ClearUnstablePanel>b__16_0() { }
}
```