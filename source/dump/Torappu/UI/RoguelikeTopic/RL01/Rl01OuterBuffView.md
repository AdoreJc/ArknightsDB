# Rl01OuterBuffView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `Rl01OuterBuffListView _buffListView`

- `Rl01OuterBuffSkillTreeView _skillTreeView`

- `Rl01OuterBuffItemDetailView _buffItemDetailView`

- `UIAnimationLocation _showAnim`

- `DetailViewSwitchTween m_switchTween`


## Methods

- `Void Init(Rl01TopicOuterBuffController)`

- `Void SwitchDetailView(Boolean, Boolean)`

- `Void ResetView()`

- `Void ShowView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffView : MonoBehaviour, IHotfixable
{
	private Rl01OuterBuffListView _buffListView; // 0x18
	private Rl01OuterBuffSkillTreeView _skillTreeView; // 0x20
	private Rl01OuterBuffItemDetailView _buffItemDetailView; // 0x28
	private UIAnimationLocation _showAnim; // 0x30
	private DetailViewSwitchTween m_switchTween; // 0x40
	private static DelegateBridge __Hotfix0_get_buffListView; // 0x0
	private static DelegateBridge __Hotfix0_get_skillTreeView; // 0x8
	private static DelegateBridge __Hotfix0_get_buffItemDetailView; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_SwitchDetailView; // 0x20
	private static DelegateBridge __Hotfix0_ResetView; // 0x28
	private static DelegateBridge __Hotfix0_ShowView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public DataBinder`1 buffListView { get; }
	public DataBinder`1 skillTreeView { get; }
	public DataBinder`1 buffItemDetailView { get; }

	// RVA: 0x26d1d94 VA: 0x7594ce9d94
	public DataBinder`1 get_buffListView() { }
	// RVA: 0x26d1dfc VA: 0x7594ce9dfc
	public DataBinder`1 get_skillTreeView() { }
	// RVA: 0x26d1e64 VA: 0x7594ce9e64
	public DataBinder`1 get_buffItemDetailView() { }
	// RVA: 0x26d1ecc VA: 0x7594ce9ecc
	public Void Init(Rl01TopicOuterBuffController topicController) { }
	// RVA: 0x26d1fe0 VA: 0x7594ce9fe0
	public Void SwitchDetailView(Boolean isShow, Boolean isInit) { }
	// RVA: 0x26d2240 VA: 0x7594cea240
	public Void ResetView() { }
	// RVA: 0x26d22c4 VA: 0x7594cea2c4
	public Void ShowView() { }
	// RVA: 0x26d2350 VA: 0x7594cea350
	public Void .ctor() { }
}
```