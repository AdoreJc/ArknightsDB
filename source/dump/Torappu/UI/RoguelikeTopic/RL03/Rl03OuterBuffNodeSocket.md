# Rl03OuterBuffNodeSocket

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `UIAnimationLocation _activeAnim`

- `Single _animLength`

- `Tween m_tween`

- `Boolean m_isActive`


## Methods

- `Void Init(Boolean)`

- `Void Render(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffNodeSocket : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _activeAnim; // 0x18
	private List`1 _fromLines; // 0x28
	private List`1 _lines; // 0x30
	private Single _animLength; // 0x38
	private Tween m_tween; // 0x40
	private Boolean m_isActive; // 0x48
	private static DelegateBridge __Hotfix0_get_fromLines; // 0x0
	private static DelegateBridge __Hotfix0_get_lines; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 fromLines { get; }
	public List`1 lines { get; }

	// RVA: 0x26a81d8 VA: 0x7594cc01d8
	public List`1 get_fromLines() { }
	// RVA: 0x26a8170 VA: 0x7594cc0170
	public List`1 get_lines() { }
	// RVA: 0x26ab594 VA: 0x7594cc3594
	public Void Init(Boolean isActive) { }
	// RVA: 0x26ab6f0 VA: 0x7594cc36f0
	public Void Render(Boolean isActive, Single delay) { }
	// RVA: 0x26ab908 VA: 0x7594cc3908
	public Void .ctor() { }
}
```