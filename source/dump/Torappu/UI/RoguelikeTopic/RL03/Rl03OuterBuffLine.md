# Rl03OuterBuffLine

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `UIAnimationLocation _activeAnim`

- `String _toBuffId`

- `Tween m_tween`

- `Boolean m_isActive`


## Methods

- `Void Init(Boolean)`

- `Void Render(Boolean, Direction, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffLine : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _activeAnim; // 0x18
	private String _toBuffId; // 0x28
	private Tween m_tween; // 0x30
	private Boolean m_isActive; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26ab074 VA: 0x7594cc3074
	public Void Init(Boolean isActive) { }
	// RVA: 0x26ab164 VA: 0x7594cc3164
	public Void Render(Boolean isActive, Direction direction, Single delay) { }
	// RVA: 0x26ab36c VA: 0x7594cc336c
	public Void .ctor() { }
}
```