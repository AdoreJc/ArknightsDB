# RL02MenuMutationAndVirtueObject

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `MutationOnlyStatePanel _panelMutationOnly`

- `OneVirtueStatePanel _panelOneVirtue`

- `MultiVirtueStatePanel _panelMultiVirtue`

- `MutationAndVirtueStatePanel _panelMutationAndVirtue`

- `UIAnimationLocation _showAnim`

- `UISwitchTween m_showTween`

- `State m_lastState`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MenuMutationAndVirtueObject : RoguelikeMenuObject`1
{
	private const Single SHOW_TWEEN_DURATION; // 0x0
	private MutationOnlyStatePanel _panelMutationOnly; // 0x28
	private OneVirtueStatePanel _panelOneVirtue; // 0x30
	private MultiVirtueStatePanel _panelMultiVirtue; // 0x38
	private MutationAndVirtueStatePanel _panelMutationAndVirtue; // 0x40
	private UIAnimationLocation _showAnim; // 0x48
	private List`1 m_statePanelList; // 0x58
	private UISwitchTween m_showTween; // 0x60
	private State m_lastState; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_get_menuType; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b6b9a4 VA: 0x75951839a4
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b6bcf0 VA: 0x7595183cf0
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b6bd58 VA: 0x7595183d58
	public override Void Render(RL02MutationAndVirtueViewModel viewModel) { }
	// RVA: 0x2b6c16c VA: 0x759518416c
	public Void .ctor() { }
	// RVA: 0x2b6c1fc VA: 0x75951841fc
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```